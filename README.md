# Dojo - Landing Page

Boas-Vindas ao repositório do Dojo Landing Page!

Neste Dojo, vamos desenvolver uma Landing Page para a confeitaria LGPDoces. Utilize os arquivos `index.html` e `style.css` para escrever seu código. 

## Requisitos

1. Crie um cabeçalho para a página:
    - Adicione um `id` para seu cabeçalho;
    - Faça com que a cor de fundo seja `#FFC5E5`;
    - Faça com que a posição seja absoluta; 
    - Use as propriedades `left` e `top` para retirrar espaços em branco. 
  
2. Crie um menu para o cabeçalho:
    - Adicione 3 elementos `h3` com os nomes *"SOBRE"*, *"SERVIÇOS"* e *"CONTATO"*, que deverão ficar à esquerda do cabeçalho; 
    - Adicione um elemento `h1` com o nome *"LGPDoces"*, que deverá ficar à direita do cabeçalho;
    - **Dica:** Use o `display: inline-block`.
  
3. Faça com que **todas** as fontes sejam da família **Arial** e da cor `#1f1c0d`.
   
4. Faça com que o `body` seja da cor `#FEE9FC`.
   
5. Crie uma **seção** e atribua uma `classe` e um `id` a ela:
    - Faça com que essa seção tenha margens em relação ao **topo**, **direita** e **esquerda**;
    - Crie um `h2` com o texto *"Sobre nós"* dentro da seção e adicione um `id` para ele;
    - Crie um parágrafo com o texto *"Somos a LGPDoces, uma confeitaria que está há 10 anos no mercado oferecendo o melhor da confeitaria. Nossa missão é levar         mais   sabor e alegria para todas as pessas consumidoras e você pode ser uma delas! Veja o que nós oferecemos."* e adicione um `id` para ele;
    - Faça com que o título tenha uma **margem** em relação à esquerda e um tamanho de `32px`;
    - Faça com que o **parágrafo** tenha um tamanho de `20px`. 
  
6. Crie uma **seção** e atribua uma `classe` e um `id` a ela:
    - Faça com que essa seção tenha margens em relação ao **topo**, **direita** e **esquerda**;
    - Crie um `h2` dentro dessa seção com fonte de `32px` e margem em relação à **esquerda**;
    - Dentro da pasta `img`, há 4 imagens de produtos oferecidos. Para cada imagem, dentro da seção criada neste passo (6), crie um `article` e coloque dentro dele a imagem e o texto a ela relacionado. Para o bolo *"Temos deliciosos bolos para você!"*; para os brigadeiros *"Experimente nossos famosos brigadeiros gourmet"*; para os cupcakes *"Os melhores cupcakes para suas festas e dia a dia"*; para a torta *"Experimente também nossas saborosas tortas"*. Exemplo de código:

      ```
       <section>
          <h2 id="services-title">Nossos serviços</h2>
            <article>
                <img src="./img/bolo.jpg" alt="foto bolo de chocolate com morangos" class="right">
                <h3 class="product">Temos deliciosos bolos para você!</h3>
            </article> 
       </section
      ```  

7. Faça com que as imagens fiquem lado a lado com os seus respectivos textos. Exemplo: ao lado da imagem do bolo deve estar o texto referente a ele.
    
8. Crie uma **seção** e atribua uma `classe` e um `id` a ela:
    - Dentro dessa seção, adicione um `h2` com o texto *"Entre em contato através de nossas redes sociais!"* ;
    - Na pasta `img` há 3 imagens referentes a ícones de redes sociais. Para cada um dos ícones, dentro da seção criada neste passo (8), crie um elemento `a` que irá receber o ícone da rede social para que, quando for cliacado, redirecione para uma nova página. Exemplo de código:
  
    ```
    <a href="https://www.whatsapp.com/?lang=pt_br" target="_blank">
        <img src="./img/whatsapp.png" alt="Ícone do whatsapp" class="socialmedia-icon">
    </a>
    ```

    - Faça com que os ícones tenham largura de `64px`;
    - Retire o atributo `text-decoration` de todas as tags `a`.
  
9.  Crie um `footer` para a página:
    - Faça com que esse footer tenha um `id`; 
    - Crie um parágrafo dentro do footer com o texto *"Todos os direitos reservados | LGPDoces | 2022"*;
    - Defina uma `altura` para o footer; 
    - Defina que sua largura ocuperá 100% da tela;
    - Faça com que sua posição seja absoluta e use a propriedade `left` para retirar espaços em branco; 
    - Defina uma margem em relação ao **topo**;
    - Faça com que a cor de fundo do footer seja `#FFC5E5`;
    - Defina uma margem em relação à **esquerda** e ao **topo** para o **parágrafo**.
  
10. Cire uma navegação interna no site:
    - Utilize a tage `a` para criar uma navegação interna através do menu do cabeçalho do site. Ao clicar em "SOBRE", a pessoa deve ser redirecionada para a primeira seção (que fala sobre a confeitaria); ao clicar em "SERVIÇOS", deverá ser redirecionada para a seção que lista os doces produzidos; ao clicar em "CONTATO", deverá ser redirecionada para a seção com os links para as redes sociais. 
