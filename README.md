# Frontend Mentor - Solução de componente de código QR

Esta é uma solução para o [desafio do componente de código QR no Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Os desafios do Frontend Mentor ajudam você a melhorar suas habilidades de codificação criando projetos realistas.

## Índice

- [Visão geral](#visão geral)
   - [Captura de tela](#captura de tela)
   - [Links](#links)
- [Meu processo](#meu-processo)
   - [Construído com](#construído com)
   - [O que aprendi](#o-que-aprendi)
   - [Desenvolvimento contínuo](#desenvolvimento contínuo)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./images/screenshot.png)

### Links

- Solution URL: [https://github.com/devaramnye/qr-code-component-challange]
- Live Site URL: [https://devaramnye.github.io/qr-code-component-challange/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

```<body>
  <div class="conteiner">

    <div class="content">
      <img src="/images/image-qr-code.png" alt="image qr code"> 
      <h1>Improve your front-end skills by building projects </h1>
      <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    </div>

  </div>

  <div class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>.
    Coded by <a href="#">Richard M. Alba</a>.
  </div>
</body>
```
```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    background-color:hsl(212, 45%, 89%);
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    font-family: 'Outfit', sans-serif;

}

.conteiner {
    background-color: hsl(0, 0%, 100%);
    max-width: 18rem;
    margin: 1rem auto;
    border-radius: 20px;
    padding: 10px;
}

.content{
    align-items: center;
}

.content img {
    max-width: 100%;
    border-radius: 15px; 
}

.content h1 {
    color: hsl(218, 44%, 22%);
    text-align: center;
    padding: 1rem 0.8rem;
    font-weight: 800;
    font-size: 1.25rem;
}

.content p {
    color: hsl(212, 45%, 89%);
    font-size: 0.8rem;
    margin: 0 1rem 1rem;
    text-align: center;
}


.attribution { 
    font-size: 11px; text-align: center; 
}

.attribution a {
     color: hsl(228, 45%, 44%); 
    }
```

### Continued development

I am currently working on responsive coding. Currently doing the 2 challange from Kevinpowell. Day one started (03.08.2023) and already day one helped me extremly by understanding that CSS is responsive by default and we are mainly causing the problems of the responsive threatment of CSS. I will continue working on my knowledge of grid and flexbox.