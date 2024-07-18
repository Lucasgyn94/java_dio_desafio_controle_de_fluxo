<div style="text-align: center;">
  <h1>Desafio Controle de Fluxo</h1>
  <p><em>Bem-vindo ao projeto <strong>DesafioControleFluxo</strong>!</em></p>
</div>

## Sobre o Projeto

Solução do desafio imposto pelo expert da DIO sobre controle de Fluxo. O sistema recebe dois números inteiros como parâmetros via terminal e realiza a impressão de números incrementados, respeitando a quantidade de interações determinadas pela diferença entre os dois números. Se o primeiro número for maior que o segundo, uma exceção personalizada `ParametrosInvalidosException` é lançada.

## Funcionalidades

<ul>
  <li><strong>Leitura de parâmetros via terminal:</strong> O sistema solicita dois números inteiros ao usuário.</li>
  <li><strong>Validação de parâmetros:</strong> Verifica se o primeiro número é maior que o segundo, lançando uma exceção personalizada se for o caso.</li>
  <li><strong>Contagem e impressão:</strong> Realiza a contagem e impressão dos números incrementados com base na diferença entre os dois parâmetros.</li>
</ul>

## Tecnologias Utilizadas

<ul>
  <li><strong>Java:</strong> Linguagem de programação utilizada para desenvolver o projeto.</li>
  <li><strong>Scanner:</strong> Utilizado para leitura de dados do terminal.</li>
  <li><strong>Exceções personalizadas:</strong> Implementação da classe <code>ParametrosInvalidosException</code> para validação de regras de negócio.</li>
</ul>

## Como Executar

<ol>
  <li>Clone o repositório:
    <pre><code>git clone https://github.com/seu-usuario/DesafioControleFluxo.git
cd DesafioControleFluxo</code></pre>
  </li>
  <li>Compile as classes:
    <pre><code>javac ParametrosInvalidosException.java Contador.java</code></pre>
  </li>
  <li>Execute o programa:
    <pre><code>java Contador</code></pre>
  </li>
</ol>

## Exemplo de Uso

<p>Ao executar o programa, você será solicitado a inserir dois números inteiros:</p>

<pre><code>Digite o primeiro parâmetro:
12
Digite o segundo parâmetro:
30
Imprimindo o número 1
Imprimindo o número 2
...
Imprimindo o número 18</code></pre>

<p>Se o primeiro parâmetro for maior que o segundo:</p>

<pre><code>Digite o primeiro parâmetro:
30
Digite o segundo parâmetro:
12
O segundo parâmetro deve ser maior que o primeiro</code></pre>

## Contato

Para mais informações sobre o projeto ou para entrar em contato comigo, envie um email para <a href="mailto:seu-email@exemplo.com">needslucas944@gmail.com</a>.

---
<div style="text-align: center;">
  <p><strong >DesafioControleFluxo</strong> &copy; 2024</p>
</div>
