# Markdown Tutorial 
![](http://i.imgur.com/IMTN5cy.png)  

Olá, bem vindos ao meu tutorial de Markdown.  
Neste tutorial você aprenderá o básico sobre Markdown. 
Versão em espanhol disponível [aqui](https://github.com/LewisVo/Markdown-Tutorial/blob/master/Translation:Spanish.md).

*******
Tabelas de conteúdo 
 1. [O que é Markdown?](#whatismarkdown)
 2. [Porque usar Markdown?](#why)
 3. [Ferramentas para Markdown](#tools)
 4. [Sintaxe de Markdown](#syntax)

*******

<div id='whatismarkdown'/>  

## O que é Markdown ?  
De acordo com a Wikipedia :  

  >*Markdown é uma linguagem de marcação leve com sintaxe de formatação de texto simples projetada para que ela possa ser convertida em HTML e muitos outros formatos usando uma ferramenta com o mesmo nome. Markdown é usado frequentemente para formatar arquivos readme, para escrever mensagens em fóruns de discussão on-line e para criar texto rico usando um editor de texto simples.*   


`SIMPLESMENTE: É APENAS OUTRO TIPO DE ARQUIVO DE TEXTO, COMO .txt .doc .... (agora é .md :risos:) E COM UMA SINTAXE ESPECIAL.`  
<div id='why'/>  

*Não existe um padrão de Markdown claramente definido. Isso levou à fragmentação, pois fornecedores diferentes escrevem suas próprias variantes do idioma para corrigir falhas ou adicionar recursos faltantes. Uma lista de versões de Markdown está disponível [aqui](https://github.com/jgm/CommonMark/wiki/Markdown-Flavors).*

A partir de agora, este guia se concentrará principalmente na versão Markdown para Github .

## Porque usar Markdown?
Porque é :
 * **FÁCIL** : A sintaxe é tão fácil que você pode aprender em um minuto ou dois, em seguida, escreva sem perceber nada estranho ou nerd.
 * **RÁPIDO** : Ele economiza tempo em comparação com outros tipos de arquivos / formatos de texto. Isso ajuda a aumentar a produtividade e os fluxos de trabalho do escritor.
 * **LIMPO** : Tanto a sintaxe como a saída são limpas, sem confusão com nossos olhos e simples de gerenciar.
 * **FLEXÍVEL** : Com apenas algumas configurações, o seu texto será traduzido atravessando qualquer plataforma lá fora, editável em qualquer software de edição de texto e conversível para uma ampla variedade de formatos.
<br></br>
**Em resumo**, os usuários comuns acharão útil em todos os casos, especialmente quando você precisar de algo melhor que o texto simples, mas menos funcional do que o Microsoft Word.  
**Para desenvolvedores**, Se você é preguiçoso para escrever código HTML, você vai adorar o markdown. **Além disso**, **Github** e muitos sites favorecem o markdown para o arquivo readme de projetos. Isso significa que você vai encontrar o markdown em sua vida de uma forma ou de outra.  
<div id='tools'/>  

## Ferramentas para markdown
Conforme mencionado acima, qualquer editor pode ser usado para editar o markdown. No entanto, existem algumas ferramentas que podem ser úteis para você quando se trata de editar markdown.
 * **[*Stackedit*](https://stackedit.io)** : Ok, você pode parar de ler agora. Clique no link e, em seguida, comece o seu turno de markdown de uma maneira mais rápida. Basta digitar o texto normal e depois usar o mouse, clique no botão. Você não precisa saber a sintaxe. É bom, mas fará você dependende, e a maioria dos desenvolvedores prefere os teclados.
 * **[*Dillinger*](http://dillinger.io/)** : Ferramenta on-line, suporte em exibição ao vivo (tela dividida) e exportação para html. Nada muito especial, mas muito limpo e acessível.
 * **[*Typora*](https://www.typora.io/)** : Disponível para Mac e Windows, mínimo, livre de distração, vista ao vivo sem parecer, empacotada com muitas outras coisas como Imagens, Listas, Tabelas, Cercas de Código, Blocos de Matemática, YAML, Front Matters, Toc, ...
 * **[*Atom*](https://atom.io/)** : Editor de texto popular hackeável (você pode estar usando isso). Sim, isso é versátil. Suporte Markdown? Apenas uma parte disso, mas é muito construído.
 * **[*Minimalist Markdown*](https://chrome.google.com/webstore/detail/minimalist-markdown-edito/pghodfjepegmciihfhdipmimghiakcjf?hl=en)** : Aplicativo do Google Chrome. Funciona em todos os lugares se você tiver o Chrome instalado (este é o meu favorito).
 * **[*Macdown*](http://macdown.uranusjr.com/)** : O Melhor para Mac.
 * **[*MarkdownPad*](http://markdownpad.com/)** : O Melhor para Windows.
 * **[*Remarkable*](https://remarkableapp.github.io/)** : O Melhor para Linux. 
 * **[*GITBOOK*](http://www.gitbook.com/)** : O GitBook é uma ferramenta de publicação moderna. Facilitando a escrita e a colaboração. Ambos suportam a Markdown e têm uma estreita relação com o amado Github.
<div id='syntax'/>  


## Sintaxe do Markdown  
Toda a sintaxe pode ser encontrada [aqui](https://daringfireball.net/projects/markdown/syntax) . Seria necessário muito esforço para descrever a sintaxe no texto (eles serão formatados), então, considere esta tabela abaixo para toda a sintaxe básica.  

| Formato        | Sintaxe      | Exemplo |
| ------|-----|-----|
| Itálico  	| \*Text\* 	| *Isto está em itálico* 	|
| Negrito  	| \*\*Bold\*\* 	| **Isto está em negrito** 	|
| Links Inline 	| \[texto\](url aqui) 	| Um [link](http://www.github.com) 	|
| Imagens 	| \![Legenda\](url da img) 	| Uma imagem ![image](http://i.imgur.com/hRLuez2.png) 	|
| Link + Imagens 	| \[\![Legenda\](url da img)\](url para a pagina)\] 	| Me clique [![me](http://i.imgur.com/hRLuez2.png)](https://www.youtube.com) 	|
| Quebras de Linha 	| Double space + enter 	|  	|
| Listas Não Ordenadas 	| \* Item1     \*Item 2 	| <ul><li>item1</li><li>item2</li> 	|
| Listas Ordenadas  	| 1. Item a    2. Item b 	| <ol><li>itema</li><li>itemb</li>  	|
| Listas Mistas 	| 1. Item 1      * item 1a 	|  <ol><li>item1</li></ol><ul><li> item1a</li></ul>	|
| Citação 	| \> Texto citado 	|  <blockquote>Stay Hungry Stay Foolish</blockquote> 	|
| Preformatted 	| Comece cada linha com, dois espaços ou mais, faça o look do texto, e x a t a m e n t e, como, você, tipo i, s, t, o. 	|   Comece cada linha com, dois espaços ou mais, faça o look do texto, e x a t a m e n t e, como, você, tipo i, s, t, o. 	|
| Código 	| \`Insira o código\` 	| `cout<<"Hello world";` 	|
| Bloco de Código/ Destaque de Sintaxe 	| \`\`\`Insira o código\`\`\` 	|  <a href="#section1">Ei, leia a nota abaixo desta tabela. 	|
| Títulos 	| \#, \##, \###, \####, \#####, \###### (from h1 to h6) 	|  <h3>Isso é um título h3</h3>	|
| Riscado 	| \~~Insira o texto aqui\~~ 	| ~~Eu estou morto~~ 	|
| Tabelas 	| \| Tables   \|      Are      \|  Cool \| \|\----------\|\:\-------------\:\|------\:\| \| col 1 is\|  left-aligned \| $1600 \| | ![](http://i.imgur.com/EItt7mh.png) |
|Notas de Rodapé| Notas de rodapé[\^1\] <br> [\^1\]: Refêrencia | Aqui está uma simples nota de rodapé[^1]. Com um texto adicional. | 
[^1]: Minha Referencia favorita.
 
<br></br>
 <br></br>
 <p id="section1">Nota: **Nota de rodapé** atualmente não renderiza direito na tabela, mas se parece com isso: </p>  
 
 ![](http://i.imgur.com/pmeBr28.png)  
   <br></br>
   O mesmo vale para **Bloco de código/destaque de sintaxe**. Sua aparência é igual a da imagem abaixo:
  
![](http://i.imgur.com/z8KrxAz.png).    

Estas características dependem de cada versão de markdown.

## Notas úteis  :
 * O Markdown permite que você use escapes de barra invertida para gerar caracteres literais que
de outra forma teria um significado especial na sintaxe de formatação da Markdown. Um personagem de escape de barra invertida comumente usado é : \     
 `Assim? \ * Este \ * não é mais itálico, mas é cercado por asteriscos literais.`

 * Os vídeos do Youtube requerem algum trabalho adicional. 
  ```
  Eles não podem ser adicionados diretamente, mas você pode adicionar uma imagem com um link para o vídeo como este:
  <a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
  " target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
  alt="Texto ALT da imagem aqui" width="240" height="180" border="10" /></a>
  ```
 * Markdown suporta Emoji :laughing: :laughing: :kissing_heart: :innocent: :green_heart: ( obter alguns emojis [aqui](http://www.emoji-cheat-sheet.com/) )
 * Você pode usar a tag \<br/> para forçar uma quebra de linha. 
 * O espaço duplo, em seguida, se você quiser fazer uma nova linha se houver problemas para criar novas linhas.
 * Ver não é tão bom como praticar. Você pode criar um arquivo de markdown para você praticar ou fazê-lo online [aqui](http://www.markdowntutorial.com).
 *  As notas de rodapé e o destaque de sintaxe não fazem parte do Markdown original e são apenas suportados por certas versões de markdown (Feedback de [Sean Brody](https://goo.gl/ASZwEn))
 *  Qualquer URL (Como http://www.github.com/) será automaticamente convertido em um link clicável.  
 *  O suporte à tabela Markdown é projetado para lidar com a maioria das tabelas para a maioria das pessoas; não cobre todas as tabelas para todas as pessoas. Se você precisa de tabelas complexas, você precisará criá-las manualmente ou com uma ferramenta especificamente projetada para o formato de saída.  
 * Usando imagens e links, você pode criar alguns recursos coloridos no momento da renderização. Badges como este são exemplos típicos que você pode encontrar em todo o Github [![Java](https://img.shields.io/badge/Java-%23FFac45.svg?&style=for-the-badge&logo=java&logoColor=white&color=yellow)](https://github.com/)  [![HTML](https://img.shields.io/badge/HTML-%23FFac45.svg?&style=for-the-badge&logo=html5&logoColor=white&color=orange)](https://github.com/)
[![CSS](https://img.shields.io/badge/CSS-%23FFac45.svg?&style=for-the-badge&logo=css3&logoColor=white&color=blue)](https://github.com/)
[![JavaScript](https://img.shields.io/badge/JAVASCRIPT-%23FFac45.svg?&style=for-the-badge&logo=javascript&logoColor=white&color=yellow)](https://github.com/) 
[![Linkedin](https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/)
[![Github](http://img.shields.io/badge/github-%231877F2.svg?&style=for-the-badge&logo=github&logoColor=white&color=black)](https://github.com/)
( get some badges [here](https://shields.io/) )

* Usando a sintaxe do bloco de código diff para gerar texto colorido. Ainda existem algumas limitações como não conseguir estilizar o texto dentro da caixa diff e poucas cores para a formatação. Isso pode ser aplicável quando você deseja destacar alguma nota ou mostrar a diferença entre dois blocos de código

```diff
- texto em vermelho
+ texto em verde
! texto em laranja
# texto em cinza
@@ texto em roxo (e negrito)@@
```

* Em arquivo markdown no Github, com sintaxe de bloco de código e linguagem Mermaid, podemos desenhar vários tipos de diagrama. Mais sintaxe e diagramas de exemplo [aqui](https://mermaid-js.github.io/)

  - Diagrama de classe
   ```mermaid
   classDiagram
       class Pato{
        -peso
         +nada()
         +quack()
       }
   ```
  - Diagrama de sequência
   ```mermaid
   sequenceDiagram
       participant dotcom
       participant iframe
       dotcom->>iframe: carrega html com url do iframe
   ```
  - Fluxograma
   ```mermaid
     graph TD;
         A-->B;
         A-->C;
         B-->D;
         C-->D;
   ```

###### Author: *Vo Tran Thanh Luong*. Also, I would like to thank all the contributors/translators for your work making this greater.
 
###### Autor: *Vo Tran Thanh Luong*.
###### Tradução: *Héricles Emanuel*.
###### Correções: [*Alexander Santos*](https://github.com/Ronkiro).
