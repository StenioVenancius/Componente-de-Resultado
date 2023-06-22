## Pt-Br
------------------------------------------------------------------------------------------------------------------------------------------------ 
# Frontend Mentor - Componente de Resumo de Resultados
Olá! <br>
Seja muito bem-vindo(a) a minha solução para o desafio do Componente de Resumo de Resultados no Frontend Mentor (https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV/hub). Este Readme servirá como seu guia para o entendimento deste projeto; ele terá como base o template disponiblizado pela própria plataforma do Frontend Mentor.
<br>
<br>
Sem mais delongas, quero agradeço por disponibiliziar um pouco do seu tempo visitando o meu projeto!

------------------------------------------------------------------------------------------------------------------------------------------------

## Índice

- [Visão Geral](#visão-geral)
    -[Captura de Tela](#captura-de-tela)
- [Meu processo](#meu-processo)
    -[Construído com](#construído-com)
    -[O que aprendi](#o-que-aprendi)
    -[Desenvolvimento Contínuo](#desenvolvimento-contínuo)
- [Autor](#autor)
- [Agradecimentos](#agradecimentos)

------------------------------------------------------------------------------------------------------------------------------------------------

## Visão Geral
### Captura de tela
![](./Design/Solu%C3%A7%C3%A3o.png)

------------------------------------------------------------------------------------------------------------------------------------------------

## Meu Processo 
### Construído com 
- HTML 
- CSS

### O que aprendi 
Neste desafio utilizei a pseudo-classe :root. Segundo o site MDN (Mozilla Developer Network) "A pseudo-classe CSS :root se equipara à raiz de uma árvore, que por sua vez representa o documento". <br>

O root foi utilizado com a finalidade de facilitar a aplicação das cores ao longo do projeto.

``` Pseudo-classe :root
:root {
    /* primary colors */
    --reaction: hsl(0, 100%, 67%);
    --memory: hsl(39, 100%, 56%);
    --verbal: hsl(166, 100%, 37%);
    --visual: hsl(234, 85%, 45%);

    /* gradients */
    --slate_blue_background: hsl(252, 100%, 67%);
    --royal_blue_background: hsl(241, 81%, 54%);
    --violet_blue_circle: hsla(256, 72%, 46%, 1);
    --persian_blue_circle: hsla(241, 72%, 46%, 0);

    /* neutral */
    --white: hsl(0, 0%, 100%);
    --pale_blue: hsl(221, 100%, 96%);
    --light_lavender: hsl(241, 100%, 89%);
    --dark_gray_blue: hsl(224, 30%, 27%);

}
``` 

Outra funcionalidade que foi utilizada foi a Media Queries para criar uma responsidade para dispositivos móveis. Segundo a MDN "Uma media query consiste de um media type e pelo menos uma expressão que limita o escopo das folhas de estilos usando media features, tal como largura, altura e cor".

``` Media Query
@media (min-width: 375px) and (max-width: 414px) {
    main {
        width: 100vw;
        height: 100vh;
        flex-direction: column;
        border-radius: 0;
    }

    /*Configurando Cards*/
    /* Card Result */
    div#Result {
        width: 100vw;
        height: auto;
        border-radius: 0 0 20px 20px;
    }

    /* Título: your result*/
    #Result span {
        margin-top: 5px;
    }

    #score h2 {
        font-size: 3.6em;
    }
    
    #score p {
        font-size: .9em;
    }

    #information h3 {
        font-size: 1.8em;
    }
    
    #information p {
        font-size: .9em;
        padding: 0 50px 10px;
    }

    /* Card Summary */
    div#Summary {
        width: 100vw;
        height: auto;
    }

    li {
        width: auto;
        height: 50px;
        margin-bottom: 10px;
    }

    li p{
        margin-left: auto;
        font-size: 1em;
    }

    li > span {
        font-size: 1em;
    }

    li img {
        width: 40px;
    }

    input {
        height: 55px;
        border-radius: 100px;
        border: none;
        font-size: 1em;
        font-weight: 500;
    }
}
```

### Desenvolvimento Contínuo
Com esse projeto pude colocar em prática meus conhecimentos de responsividade. Ainda não estão na sua melhor forma, mas pretendo continuar implementando e aperfeiçoando em projetos futuros. Também gostei da ideia de utilizar a pseudo-classe :root e quero utiliza-la em outros projetos.

------------------------------------------------------------------------------------------------------------------------------------------------

## Autor 
- Frontend Mentor [@StenioVenancius](frontendmentor.io/profile/StenioVenancius)
- Twitter [@veennix](https://twitter.com/veennix)

------------------------------------------------------------------------------------------------------------------------------------------------

## Agradecimentos 
Muito Obrigado por ter lido até aqui ❣️
Sinta-se avontade para enviar seu feedback!

------------------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------------------
## EN
------------------------------------------------------------------------------------------------------------------------------------------------

# Frontend Mentor - Results Summary Component
Hello! <br>
Welcome to my solution to the Results Summary Component challenge in Frontend Mentor (https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV/hub). This Readme will serve as your guide to understanding this project; it will be based on the template provided by the Frontend Mentor platform itself.
<br>
<br>
Without further ado, I want to thank you for taking the time to visit my project!

------------------------------------------------------------------------------------------------------------------------------------------------

## Table of contents
- [Overview](#Overview)
    -[Screenshot](#screenshot)
- [My process](#my-process)
    -[Built with](#built-with)
    -[What I Learned](#What-I-Learned)
    -[Continuous-Development](#Continuous-Development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

------------------------------------------------------------------------------------------------------------------------------------------------

## Overview
### Print Screen
![](./Design/Solu%C3%A7%C3%A3o.png)

------------------------------------------------------------------------------------------------------------------------------------------------

## My Process
### Built with
- HTML
- CSS

### What I learned
In this challenge I used the :root pseudo-class. According to the website MDN (Mozilla Developer Network) "The CSS pseudo-class :root is likened to the root of a tree, which in turn represents the document". <br>

The root was used in order to facilitate the application of colors throughout the project.

``` Pseudo-classe :root
:root {
    /* primary colors */
    --reaction: hsl(0, 100%, 67%);
    --memory: hsl(39, 100%, 56%);
    --verbal: hsl(166, 100%, 37%);
    --visual: hsl(234, 85%, 45%);

    /* gradients */
    --slate_blue_background: hsl(252, 100%, 67%);
    --royal_blue_background: hsl(241, 81%, 54%);
    --violet_blue_circle: hsla(256, 72%, 46%, 1);
    --persian_blue_circle: hsla(241, 72%, 46%, 0);

    /* neutral */
    --white: hsl(0, 0%, 100%);
    --pale_blue: hsl(221, 100%, 96%);
    --light_lavender: hsl(241, 100%, 89%);
    --dark_gray_blue: hsl(224, 30%, 27%);

}
```

Another feature that was used was the Media Queries to create a response for mobile devices. According to MDN "A media query consists of a media type and at least one expression that limits the scope of style sheets using media features such as width, height and color".

``` Media Query
@media (min-width: 375px) and (max-width: 414px) {
    main {
        width: 100vw;
        height: 100vh;
        flex-direction: column;
        border-radius: 0;
    }

    /*Configurando Cards*/
    /* Card Result */
    div#Result {
        width: 100vw;
        height: auto;
        border-radius: 0 0 20px 20px;
    }

    /* Título: your result*/
    #Result span {
        margin-top: 5px;
    }

    #score h2 {
        font-size: 3.6em;
    }
    
    #score p {
        font-size: .9em;
    }

    #information h3 {
        font-size: 1.8em;
    }
    
    #information p {
        font-size: .9em;
        padding: 0 50px 10px;
    }

    /* Card Summary */
    div#Summary {
        width: 100vw;
        height: auto;
    }

    li {
        width: auto;
        height: 50px;
        margin-bottom: 10px;
    }

    li p{
        margin-left: auto;
        font-size: 1em;
    }

    li > span {
        font-size: 1em;
    }

    li img {
        width: 40px;
    }

    input {
        height: 55px;
        border-radius: 100px;
        border: none;
        font-size: 1em;
        font-weight: 500;
    }
}
```

### Continuous Development
With this project I was able to put into practice my knowledge of responsiveness. They are still not in their best shape, but I intend to continue implementing and improving them in future projects. I also like the idea of ​​using the :root pseudo-class and want to use it in other projects.

------------------------------------------------------------------------------------------------------------------------------------------------

## Author
- Frontend Mentor [@StenioVenancius](frontendmentor.io/profile/StenioVenancius)
- Twitter [@veennix](https://twitter.com/veennix)

------------------------------------------------------------------------------------------------------------------------------------------------

## Acknowledgments
Thank you so much for reading this far ❣️
Feel free to submit your feedback!

------------------------------------------------------------------------------------------------------------------------------------------------
