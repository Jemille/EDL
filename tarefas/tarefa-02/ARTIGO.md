
<h1>A Linguagem de programação Julia</h1>

<h2>Introdução</h2>

<p> O presente artigo trata da linguagem de programação Julia.Uma linguagem de propósito geral com foco em computação científica e matemátiva.Ela foi construída com heranças das linguagens de programação matemática, mas também herda muito de outras linguagens dinâmicas populares, incluindo Lisp, Perl, Python, Lua e Ruby.Julia começou a ser desenvolvida em 2009 e, atualmente, se encontra na versão 1.0.</p>
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

<p>Linguagem multi-paradigma, com características de programação imperativa,funcional e orientada a objetos.
Julia é uma linguagem dinâmica, seus tipos são objetos em tempo de execução, e podem também ser definidos em tempo de compilação,resultando em um codigo mais eficiente.</p>
<p>
Exemplo :
<pre><code>function soma(x::Int,y::Int)
    return x+ y 
end</code></pre>
</p>
<p>Julia apresenta diversas funções matemáticas e com alta precisão dos valores numéricos,recursos para computação paralela e distribuída.Uma extensa bibliotecas padrão escritas na própria linguagem.Possui um alto desempenho para a computação científica,possui ,ainda, sintaxe facil de escrever, semelhante ao python.
 
<h4>A expressividade de Julia em relação a Python</h4>
<p>De acordo com a definição de expressividade, podemos concluir que as operações matemáticas encontradas em Julia a torna mais expressiva em relação a linguagem Python.A seguir,encontra-se alguns exemplos.</p>
  
<p>Codigo em Julia  
<pre><code>function produtoVet(vetor,num)
    return vetor*num
end</code></pre>
</p>

<p>Codigo em python
<pre><code>def prod_vet(vet,num):
    res=[0]*len(vet)
    for i in range(0,len(vet)):
        res[i]=vet[i]*num
    print (res)
end</code></pre>
</p>

<h.5>Exemplos de código</h5>

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
