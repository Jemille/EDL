
<h1>A Linguagem de programação Julia</h1>

<h2>Introdução</h2>

<p> O presente artigo tem como objetivo tratar da linguagem de programação Julia.Uma linguagem de propósito geral com foco em computação científica e matemátiva.Ela foi construída com heranças das linguagens de programação matemática, mas também herda muito de outras linguagens populares, incluindo Lisp, Perl, Python, Lua e Ruby.Julia começou a ser desenvolvida em 2009 e, atualmente, se encontra na versão 1.0.</p>
<p>Versões anteriores:  
<ul>
  <li>0.1.2 </li>
  <li>0.3 </li>
  <li>0.6.0 </li>
</ul>
Também há uma versão beta chamada 0.5.0-dev e é atualizada constantemente.
</p>

<p>A linguagem teve a contribuição de Stefan Karpinski,Jeff Bezanson, Alan Edelman e Viral Shah.</p>


<h2>Características e classificação</h2>

<p>Linguagem multi-paradigma, com características de programação imperativa,funcional e orientada a objetos.É uma linguagem open source, de alto nível e compilada(JIT).Esse compilador utiliza um método no qual o código fonte é traduzido para código de máquina em tempo de execução na CPU.</br>
Julia é uma linguagem com tipagem opcional.Seus tipos são objetos em tempo de execução, na ausência da declaração dos tipos,mas também podem ser definidos em tempo de compilação,resultando em um codigo mais eficiente.</p>
<p>
Exemplo:
<pre><code>function soma(x::Int8,y::Int8)
    return x+ y 
end</code></pre>
</p>
<p>Julia aceitas os seguintes tipos de dados:</p>
<ul>  
  <li>Int8 - Número inteiro 8-bit com ou sem sinal</li>
  <li>Int16 — Número inteiro 16-bit com ou sem sinal</li>
  <li>Int32 — Número inteiro 32-bit com ou sem sinal</li>
  <li>Int64 — Número inteiro 64-bit com ou sem sinal</li>
  <li>Int128 — Número inteiro 128-bit com ou sem sinal</li>
  <li>Float32 — Números de ponto flutuante 32-bit</li>
  <li>Float64 — Números de ponto flutuante 64-bit</li>
  <li>Bool — true (verdadeiro) ou false (falso), que correspondem numericamente a 1 ou 0, respectivamente.</li>
  <li>Char — um tipo numérico de 32 bits representando um caracter Unicode.</li>
 </ul>
 <p>Julia possui tipagem forte</br>
    4.0 (float) e 1 (inteiro) são diferentes 
</p>
<p>A linguagem aceita funções e comandos de controle de fluxo (if, for, while...) que são terminadas com "end";</p> 

<p>Julia apresenta diversas funções matemáticas e com alta precisão dos valores numéricos,recursos para computação paralela e distribuída.Uma extensa bibliotecas padrão escritas na própria linguagem.Possui um alto desempenho para a computação científica,possui ,ainda, sintaxe facil de escrever, semelhante ao python.
 
<h4>A expressividade de Julia em relação a Java</h4>

<p>O despacho multiplo é uma das principais características e o diferencial da linguagem julia.As funções em Julia podem ter vários métodos definidos e o comportamento da execução depende dos argumentos que são passados. Quando uma função é chamada, Julia fará uma pesquisa na sua vtable (tabela de métodos virtual) em tempo de execução para descobrir qual método correto deve ser chamado com base nos
tipos de todos os seus argumentos.Em contrapartida temos a linguagem java que possui despacho único.A seguir temos um código em julia ,com o uso de despacho multiplo, e outro em java estruturado de uma forma se aproximar do despacho multiplo de julia. </p>
<p>Codigo em Julia  
<pre><code>function produtoVet(vetor,num)
    return vetor*num
end</code></pre>
</p>

<p>Codigo em java
<pre><code>def prod_vet(vet,num):
    res=[0]*len(vet)
    for i in range(0,len(vet)):
        res[i]=vet[i]*num
    print (res)
end</code></pre>
</p>

<h5>Exemplos de código</h5>

<p>Todo operador é função , veja a seguir:
<pre><code>
>>f=+
>>f(1,2,3)
</pre><code>
O resultado é 3 que corresponde a soma dos numeros 1,2 e 3.</p>
  
 <h4>Bibliografia</h4>

<https://julia-cn.readthedocs.io/pt_BR/latest/manual/>

<http://www.cienciaedados.com/julia-a-princesinha-do-cientista-de-dados/>

<https://pt.wikipedia.org/wiki/Julia_(linguagem_de_programa%C3%A7%C3%A3o)>
