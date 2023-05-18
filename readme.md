# Aprendendo a aprender

## Descrição do projeto

Este projeto cria um website que apresenta um conteúdo cujo o tema principal é o aprendizado eficaz. Toda a página apre abordando técnicas e exercícios para, não apenas acelerar, mas também melhorar o processo de aprendizagem, trazendo mais qualidade e eficiência, tornando processo educacional cada vez mais cativante.
Em conjunto com dados, que mostram a veracidade do conhecimento abordado, e com indicações de materiais adicionais que funcionarão como reforço, o leitor será guiado a uma jornada que o fará entender que é possivel, sim, ter prazer no aprender.

## Tecnologia

Para a criação do website foram usadas diversas técnicas HTML e CSS avançado, e todo o código foi estruturado conforme a metodologia BEM.

### HTML

#### Tags Semânticas

Nesta parte do código foram aplicadas as tags semânticas de acordo com a necessidade. Foram usadas:

1. Tags para título, h1 ao h5, conforme os níveis de textos de cada uma das seções;
2. As tags 'header' para o cabeçalho, 'main', para o corpo do conteúdo, composta da tag 'section' para as diferentes seções, e, por fim, 'footer' para o rodapé;
3. A tag 'p' para textos em parágrafos, e quando link, a tag 'a' acompanhada de um valor 'href';
4. A inserção de imagens com a tag 'img' composta de um valor 'alt';
5. As tags 'ul' e 'li' para a criação de cada uma das tabelas que compõe o projeto;

#### Classes

1. À cada uma das seções foram atribuídas classes: para blocos e para blocos+elementos, de acordo com a regra de nomenclatura de classes da metodologia BEM;
2. Foram usadas também a mistura de classes para as animações;

### CSS

Toda a estilização dos blocos e elementos foi feita com o uso de suas respectivas classes. O código foi estruturado conforme a regra flat de estruturação de arquivos da metodologia BEM. Foram criado um stylesheet para cada bloco, contendo dentro deste a regra de estilização para o bloco e seus modificadores e para os elementos dos respectivos blocos e seus modificadores. Logo, todos os arquivos bloco.css são importados pelo '@import' no arquivo 'index.css', que abrange o estilo geral do website, o qual é linkado ao arquivo 'index.html'.

#### Animações

Foram usadas animações de rotação para as formas geométricas dentro da projeto, em conjunto com a mistura de classes, criando assim uma regra geral para a animação.

#### Posicionamento e Alinhamento

Para a maioria dos blocos foi usado o posicionamento pelo flexbox, e logo as propriedades usadas foram para alinhar e justificar elementos, juntamente com a direção (flex-direction). Foram também usadas as propriedades margem e preenchimentos entre uma seção e outra e entre um elemento e outro.

### Metodologia BEM flat

Além da aplicação de estruturação flat no CSS, a regra da metodologia foi aplicada aos demais diretórios contidos dentro do diretório raiz do projeto. Todas as imagens foram reunidas na pasta 'image', os códigos externos na pasta 'vendor', e o arquivo 'index.css' na pasta 'page'.
