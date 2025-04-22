Este repositório contém dois projetos com a proposta de replicar o mesmo layout utilizando diferentes abordagens com HTML semântico, CSS Flexbox e CSS Grid. Ambos os projetos implementam uma versão responsiva.
 **Projeto 1 – HTML Semântico + CSS Flexbox**
Neste projeto, o layout foi desenvolvido utilizando apenas Flexbox para organizar os elementos da página. A estrutura foi criada com tags semânticas como header, nav, main, section, article, aside e footer, respeitando as boas práticas de acessibilidade e organização do conteúdo.
O Flexbox foi responsável por alinhar os elementos em colunas e linhas, garantindo a responsividade por meio de media queries. Foi eficiente para distribuir o espaço entre os componentes e alinhar itens horizontal e verticalmente.

 **Projeto 2 – CSS Grid + Flexbox**
Neste segundo projeto, a mesma estrutura foi mantida, mas a organização visual foi feita utilizando CSS Grid para o layout principal e Flexbox para alinhar elementos internos. O uso de Grid possibilitou um controle mais preciso da disposição das áreas da página, com uma definição clara de linhas e colunas.
O Flexbox ainda foi utilizado em blocos específicos para facilitar o alinhamento interno de elementos, como os article dentro de section. A responsividade foi aprimorada com auto-fit, minmax e grid-template-areas, permitindo uma adaptação mais fluida em diferentes tamanhos de tela.

Ao comparar as duas abordagens, foram notadas as seguintes **diferenças**:
Flexbox é mais indicado para layouts lineares, ou seja, estruturas em linha ou coluna, sendo simples de implementar, mas um pouco limitado para organizar layouts mais complexos.
CSS Grid é ideal para layouts bidimensionais, oferecendo maior controle sobre o posicionamento dos elementos, além de facilitar a criação de áreas fixas como main, aside, etc.
A combinação de Grid com Flexbox proporciona um layout mais modular, organizado e com melhor manutenção de código, especialmente em projetos com maior complexidade.
Em termos de responsividade, o Grid oferece recursos mais avançados, como o uso de minmax() e auto-fit, o que reduz a dependência de muitas media queries.

**[Clique aqui para ver o projeto publicado]( https://aliciaana.github.io/Atividade2Introducao-CSS/ )**
