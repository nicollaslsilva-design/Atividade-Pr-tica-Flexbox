# Atividade-Pratica-Flexbox

Objetivo: desenvolver uma página completa utilizando HTML e CSS, praticando os conceitos de Flexbox
vistos em aula. O desafio é identificar corretamente os containers Flexbox, seus elementos filhos e como
cada propriedade altera o layout.

1. Cabeçalho
Crie um &lt;header&gt; com três grupos: nome da plataforma, menu de navegação e botão de entrada.
 Logo/nome: Escola Tech
 Menu: Início, Cursos, Professores e Contato
 Botão: Entrar
O cabeçalho deverá organizar os três grupos na mesma linha. O menu também deverá ser um container
Flexbox independente.
Representação aproximada:
Escola Tech Início Cursos Professores Contato Entrar

2. Área de destaque
Crie uma seção principal dividida em duas partes.
 Lado esquerdo: título, parágrafo e dois botões.
 Lado direito: uma caixa representando uma imagem ou ilustração.
As duas partes deverão permanecer lado a lado utilizando. Dentro do lado esquerdo, os dois botões também
deverão ser organizados com um novo container.

3. Categorias
Crie a seção “Explore por categoria” com pelo menos cinco categorias:
 Front-end
 Back-end
 Banco de Dados
 Mobile
 DevOps
As categorias deverão ficar centralizadas, com espaço entre elas e quebrar para uma nova linha quando não
houver espaço suficiente.

4. Cursos disponíveis

HTML &amp; CSS | Atividade Prática

Flexbox — Plataforma Escola Tech

Crie no mínimo 8 cards de cursos. Sugestões: HTML, CSS, JavaScript, React, Node.js, Python, Banco de
Dados e Git/GitHub.
Cada card deverá conter:
 Nome do curso
 Pequena descrição
 Carga horária
 Nível
 Botão “Ver curso”
Organização dos cards:
Defina também uma largura para cada card para que o efeito de quebra de linha possa ser observado.

5. Flexbox dentro do card
Dentro de cada card, crie uma pequena área de informações com carga horária e nível em lados opostos.

6. Estilização e interação
Todos os cards deverão possuir uma sombra. Ao passar o mouse, a sombra deverá ficar mais evidente.
Você também pode alterar a cor do botão ou do card no :hover, desde que não utilize recursos fora do
conteúdo visto em aula.

7. Área de benefícios
Crie a seção “Por que estudar na Escola Tech?” com quatro benefícios:
 Professores especializados
 Aulas práticas
 Projetos reais
 Certificado de conclusão
Os quatro benefícios deverão ficar lado a lado no container principal. Dentro de cada benefício, organize o
conteúdo verticalmente utilizando flex-direction: column.

8. Rodapé
Crie um rodapé dividido em três partes:
 Escola Tech + pequena descrição
 Cursos: HTML, CSS e JavaScript
 Contato: contato@escolatech.com
As três áreas deverão ficar distribuídas horizontalmente utilizando Flexbox.

HTML &amp; CSS | Atividade Prática

Flexbox — Plataforma Escola Tech
9. Desafio principal — Flexbox dentro de Flexbox
A página deverá possuir vários containers Flexbox com objetivos diferentes.

11. Resultado aproximado
----------------------------------------------------------------
Escola Tech Início Cursos Professores Contato Entrar
----------------------------------------------------------------
APRENDA TECNOLOGIA +----------------+
DE VERDADE | IMAGEM |
Cursos para quem quer +----------------+
entrar na programação.
[Ver cursos] [Saiba mais]
EXPLORE POR CATEGORIA
[Front-end] [Back-end] [Banco] [Mobile] [DevOps]
CURSOS DISPONÍVEIS
[ HTML ] [ CSS ] [ JavaScript ] [ React ]
[ Node ] [ Python ] [ Banco ] [ Git ]
POR QUE ESTUDAR NA ESCOLA TECH?
[Professores] [Aulas] [Projetos] [Certificado]
----------------------------------------------------------------
Escola Tech Cursos Contato
----------------------------------------------------------------

12. Questões para responder
Responda ao final do arquivo style.css utilizando comentários CSS.
1. Qual é a função do display: flex?
2. Qual é a diferença entre flex-direction: row e flex-direction: column?
3. Para que serve justify-content?
4. Para que serve align-items?
5. Qual é a função do flex-wrap: wrap?
6. Qual é a diferença entre gap e margin?
7. Identifique três elementos da sua página que são containers Flexbox e diga quais elementos eles
organizam.

HTML &amp; CSS | Atividade Prática

Flexbox — Plataforma Escola Tech

13. Entrega
Entregue os dois arquivos abaixo:
index.html
style.css
