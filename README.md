# Markdown Tutorial 
![](http://i.imgur.com/IMTN5cy.png)  

Hello, welcome to my tutorial for markdown.  
In this tutorial you will learn the most basics things about Markdown.  
Spanish version available [here](https://github.com/LewisVo/Markdown-Tutorial/blob/master/Translation:Spanish.md).
Portuguese version available [here](https://github.com/LewisVo/Markdown-Tutorial/blob/master/README_pt-BR.md).
French version available [here](https://github.com/luongvo209/Markdown-Tutorial/blob/master/README_fr.md).

*******
Tables of contents  
 1. [What is Markdown?](#whatismarkdown)
 2. [Why use Markdown?](#why)
 3. [Tools for Markdown](#tools)
 4. [Markdown Syntax](#syntax)

*******

<div id='whatismarkdown'/>  

## What is markdown ?  
According to Wikipedia :  

  >*Markdown is a lightweight markup language with plain text formatting syntax designed so that it can be converted to HTML and many other formats using a tool by the same name. Markdown is often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor.*   


`SIMPLY: IT'S JUST ANOTHER TYPE OF TEXT FILE, LIKE .txt .doc ....( now it's .md :laughing:) AND IT HAS SOME SPECIAL SYNTAX.`  
<div id='why'/>  

*There is no clearly defined Markdown standard. This has led to fragmentation as different vendors write their own variants of the language to correct flaws or add missing features.. A list of markdown flavour is available [here](https://github.com/jgm/CommonMark/wiki/Markdown-Flavors).*

From now, this guide will mainly focus on Github Flavoured Markdown.

## Why use markdown?
Because it's :
 * **EZ** : The syntax is so easy that you can learn in a minute or two then write without noticing anything weirdo  or geeky.
 * **FAST** : It saves time compared to other types of text files/formats. It helps boost the productivity and workflows of writer.
 * **CLEAN** : Both the syntax and output are clean, not messy with our eyes and simple to manage.
 * **FLEXIBLE** : With just a little set-up, your text will be translated cross any platform out there, editable in any text-editing software and convertible to a wide array of formats.
<br></br>
**In short**, normal users will find it useful in any cases, especially when you are in need of something better than plain text but less functional than Microsoft Word.  
**For Developers**, if you are lazy to write HTML code , you will love markdown. **Moreover**, **Github** and many sites favor markdown for readme file of projects. That means you gonna meet markdown in your life one way or another.  
<div id='tools'/>  

## Tools for markdown
As said above, any editors can be used to edit markdown. However, there are a few tools that may be useful for you when it comes to edit markdown.
 * **[*Stackedit*](https://stackedit.io)** : Ok, you can stop reading right now. Click the link then start your markdown tour in an eziest way ever. Just type normal text then use your mouse, click click done. You dont have to know the syntax.  It's good, but it will make you reliant and most developers prefers keyboards.
 * **[*Dillinger*](http://dillinger.io/)** : Online tool, support live view (split screen) and export to html. Nothing too special but very neat and handy.
 * **[*Typora*](https://www.typora.io/)** : Available for Mac and Windows, minimal, distraction free, live view seemlessly, bundled with a lot of other stuffs like Images, Lists, Tables, Code Fences, Math Blocks, YAML, Front Matters,Toc,...
 * **[*Atom*](https://atom.io/)** : popular hackable text editor (you may be using this). Yeah, this is versatile. Markdown Support? Just a part of it but is greatly built in.
 * **[*Minimalist Markdown*](https://chrome.google.com/webstore/detail/minimalist-markdown-edito/pghodfjepegmciihfhdipmimghiakcjf?hl=en)** : Chrome app. Works everywhere if you have Chrome installed ( this is my favorite one).
 * **[*Macdown*](http://macdown.uranusjr.com/)** : best for Mac.
 * **[*MarkdownPad*](http://markdownpad.com/)** : best for Windows.
 * **[*Remarkable*](https://remarkableapp.github.io/)** : best for Linux. 
 * **[*GITBOOK*](http://www.gitbook.com/)** : GitBook is a modern publishing toolchain. Making both writing and collaboration easy. It does both support Markdown and have a close relation with the beloved Github.
<div id='syntax'/>  

## Markdown Syntax  
All Syntax can be found [here](https://daringfireball.net/projects/markdown/syntax) . It would take a lot of effort to describe syntax in text (they will be formatted) so please consider this table below for the whole basics syntax.  

| Format        | Syntax      | Example |
| ------|-----|-----|
| Italic  	| \*Text\* 	| *This is italic* 	|
| Bold  	| \*\*Bold\*\* 	| **This is bold** 	|
| Inline links 	| \[Description text\](url here) 	| A [link](http://www.github.com) 	|
| List Links | `<li> <a href="url here"> Description Text </a> `| <li> <a href="https://github.com">A link</a>|
| Images 	| \![Caption\](url to img) 	| An image ![image](http://i.imgur.com/hRLuez2.png) 	|
| Link+images 	| \[\![Caption\](url to img)\](url to a page)\] 	| Click me [![me](http://i.imgur.com/hRLuez2.png)](https://www.youtube.com) 	|
| Footnotes  	| I have more \[^1\] to say.   \[^1\]: say it down here. 	| <a href="#section1">Hey,Please read the note below this table.  	|
| Line breaks 	| Double space + enter 	|  	|
| Unordered Lists 	| \* Item1     \*Item 2 	| <ul><li>item1</li><li>item2</li><li>item3</li><li>item4</li></ul> 	|
| Ordered Lists 	| 1. Item a    2. Item b 	| <ol><li>itema</li><li>itemb</li><li>itemc</li><li>itemd</li></ol>  	|
| Mixed Lists 	| 1. Item 1      * item 1a 	|  <ol><li>itema</li></ol><ul><li> item1</li></ul>	|
| Block quote 	| \> Quoted text 	|  <blockquote>Stay Hungry Stay Foolish</blockquote> 	|
| Preformatted 	| Begin each line with,two spaces or more to,make text look,e x a c t l y,like,you,type i,t. 	|   Begin each line with,two spaces or more to,make text look,e x a c t l y,like,you,type i,t. 	|
| Code 	| \`Insert Code\` 	| `cout<<"Hello world";` 	|
| Code block/ Syntax highlighting 	| \`\`\`insert code\`\`\` 	|  <a href="#section1">Hey,Please read the note below this table. 	|
| Headers 	| \#, \##, \###, \####, \#####, \###### (from h1 to h6) 	|  <h3>This is a h3 header</h3>	|
| Strike through 	| \~~Insert text here\~~ 	| ~~I am dead~~ 	|
| Tables 	| \| Tables   \|      Are      \|  Cool \| \|\----------\|\:\-------------\:\|------\:\| \| col 1 is\|  left-aligned \| $1600 \| | ![](http://i.imgur.com/EItt7mh.png) |

<br></br>
 <br></br>
 <p id="section1">Note: **Footnote** actually doesnt render properly in table (and github preview), but it kinda looks like this </p>  
 
 ![](http://i.imgur.com/pmeBr28.png)  
   <br></br>
   The same goes for **block code/syntax hightlighting**. It kinda looks like this picture :
  
![](http://i.imgur.com/z8KrxAz.png).    

These characteristics are dependent upon each markdown flavour.  


## Useful notes  :
 * Markdown allows you to use backslash escapes to generate literal characters which
would otherwise have special meaning in Markdown’s formatting syntax. One commonly used backslash escape character is : \     
 `So? \*This\* isnt italic  anymore but is surrounded by literal asterisks.`

 * Youtube videos require some additional work. 
  ```
  They can't be added directly but you can add an image with a link to the video like this:
  <a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
  " target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
  alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
  ```
 * Markdown does support Emojii :laughing: :laughing: :kissing_heart: :innocent: :green_heart: ( get some emojies [here](http://www.emoji-cheat-sheet.com/) )
 * You can use \<br/> tag to force line break. 
 * Double space then enter if you want to make a new line if there is trouble making new lines.
 * Seeing is not as good as practicing. You can either create a markdown file for yourself to practice or do it online [here](http://www.markdowntutorial.com).
 *  Footnotes and syntax highlighting are not part of the original markdown and are only supported by certain flavors of markdown (Feedback from [Sean Brody](https://goo.gl/ASZwEn))
 *  Any URL (like http://www.github.com/) will be automatically converted into a clickable link.  
 *  Markdown table support is designed to handle most tables for most people; it doesn’t cover all tables for all people. If you need complex tables you will need to create them by hand or with a tool specifically designed for your output format.  
```I had such a pain making the above table possible```
 
###### Author: *Vo Tran Thanh Luong*. Also, I would like to thank all the contributors/translators for your work making this greater.
   
