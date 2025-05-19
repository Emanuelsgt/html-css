# html-css
atividades escolares 

 1. Estrutura Textual em Páginas Web (com exemplos)
Sites analisados:
CNN Brasil – Artigo de notícias

MDN Web Docs – Documentação técnica

Viver de Blog – Página inicial de blog

Elementos de texto encontrados:
  <p> – Parágrafo
Função: Define blocos de texto. Cada parágrafo é tratado como uma unidade distinta.
Exemplo real (CNN):

html
<p>O presidente fez um pronunciamento nesta quarta-feira, destacando a importância das reformas.</p>
Contribuição: Organiza o texto em trechos curtos, facilitando a leitura e a escaneabilidade.

 <h1> a <h6> – Títulos e subtítulos
Função: Estabelecem hierarquia de informações no conteúdo.

Exemplo real (MDN):

html
<h1>String</h1>
<h2>Constructor</h2>
<h3>Examples</h3>
Contribuição:

<h1> é o título principal da página.

<h2> representa seções importantes.

<h3> e inferiores dividem ainda mais o conteúdo.
Essa organização melhora tanto a navegação quanto a estrutura para SEO e leitores de tela.

 <strong> – Ênfase com peso semântico
Função: Indica que o conteúdo é importante, e não apenas visualmente em negrito.

Exemplo real (Viver de Blog):

html
<p><strong>Produzir conteúdo de qualidade</strong> é o principal fator para aumentar sua audiência.</p>
Contribuição: Além de destacar visualmente, informa ao navegador e tecnologias assistivas que o texto é relevante.

 <em> – Ênfase contextual
Função: Indica ênfase verbal ou de contexto, geralmente com itálico.

Exemplo real (MDN):

html
<p>You can <em>optionally</em> use a fallback value.</p>
Contribuição: Ajuda o leitor a compreender nuances de tom ou intenção, especialmente em instruções.

 <br> – Quebra de linha
Função: Insere uma quebra de linha sem iniciar novo parágrafo.

Exemplo (Blog):

html
<p>Inscreva-se agora<br>e receba conteúdo exclusivo!</p>
Contribuição: Usado quando queremos que o conteúdo apareça em duas linhas, sem espaçamento extra.

 <hr> – Linha divisória
Função: Representa uma mudança de assunto ou seção.

Exemplo (MDN):

html
<p>Veja a documentação completa abaixo.</p>
<hr>
<h2>Exemplos de uso</h2>
Contribuição: Cria separações visuais claras que ajudam o usuário a navegar pelo conteúdo com mais facilidade.

 2. Uso de Listas para Organização (com exemplos)
Tipos de listas e exemplos:
 <ul> e <li> – Lista não ordenada
Função: Agrupa itens sem ordem definida.

Exemplo real (Blog):

html
<ul>
  <li>Mais visitas no site</li>
  <li>Maior autoridade online</li>
  <li>Mais vendas de produtos</li>
</ul>
Contribuição: Ideal para enumerar características, recursos ou benefícios sem hierarquia.

 <ol> e <li> – Lista ordenada
Função: Organiza itens em uma sequência lógica ou numérica.

Exemplo (CNN):

html
<ol>
  <li>O presidente discursou às 14h.</li>
  <li>Após o discurso, ministros se reuniram.</li>
  <li>A reforma será votada na sexta-feira.</li>
</ol>
Contribuição: Ajuda o leitor a seguir uma ordem cronológica, de passos ou prioridade.

 <dl>, <dt>, <dd> – Lista de definição
Função: Lista de termos seguidos de suas definições.

Exemplo real (MDN):

html
<dl>
  <dt>Syntax</dt>
  <dd>The syntax for includes is: string.includes(value)</dd>
  
  <dt>Parameters</dt>
  <dd>The value to search for within the string.</dd>
</dl>
Contribuição: Excelente para glossários, tutoriais ou FAQ técnico, tornando o conteúdo mais didático.

 3. Uso de Citações na Web (com exemplos)
Elementos de citação:
 <blockquote> – Citação em bloco
Função: Apresenta uma citação longa, geralmente com recuo visual.

Exemplo real (CNN):

html
<blockquote>
  "É fundamental garantir os direitos da população durante o processo", disse o ministro da Justiça.
</blockquote>
Contribuição: Destaca falas importantes ou trechos de outros autores. Visualmente chama atenção e ajuda na distinção entre o conteúdo original e o citado.

 <q> – Citação curta
Função: Representa uma citação curta embutida no texto.

Exemplo (MDN):

html
<p>O método <q>includes()</q> verifica se um valor está presente em uma string.</p>
Contribuição: Aspas são adicionadas automaticamente, destacando trechos sem quebrar o fluxo da leitura.

 Resumo das diferenças semânticas:
Elemento	Indicado para	Exibição	Relevância
<blockquote>	Citações longas ou de destaque	Bloco	Visual e semântica
<q>	Trechos curtos dentro do texto	Inline	Menor, mas ainda semântica


