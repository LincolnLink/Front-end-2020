# Navegadores antigos

No entanto, o IE8 e versões anteriores, não permitem estilizar elementos desconhecidos. Portanto, o HTML5Shiv é uma solução alternativa em JavaScript para habilitar o estilo dos elementos HTML5

- HTML5Shiv

    <blockquote>
        <!--[if lt IE 9]>
        <script src="https://oss.maxcdn.com/libs/html5shiv/3.7.0/html5shiv.js"></script>
        <![endif]-->
    </blockquote>


# Estrutura basica do HTML5

- Este exemplo mostra uma estrutura basica com a declaração do !DOCTYPE e da codificação de caracteres em HTML5

    <blockquote>

        <!DOCTYPE html>
        <html>
        <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Title of the document</title>
        </head>

            <body>
                <header>
                    <h1>Monday Times</h1>
                </header>

                <nav>
                    <ul>
                        <li>News</li>
                        <li>Sports</li>
                        <li>Weather</li>
                    </ul>
                </nav>

                <section>
                    <h2>News Section</h2>
                    <article>
                        <h2>News Article</h2>
                        <p>Lorem ipsum dolor sit amet..</p>
                    </article>
                    <article>
                        <h2>News Article</h2>
                        <p>Lorem ipsum dolor sit amet..</p>
                    </article>
                </section>

                <footer>
                    <p>&copy; 2014 Monday Times. All rights reserved.</p>
                </footer>
            </body>
        </html>
    </blockquote>


- Novos elementos semânticos

    <blockquote>
        < header>, < footer>, < article>, e < section>.        
    </blockquote>
    
- Novos elementos gráficos

    <blockquote>
        < svg>, < canvas>.        
    </blockquote>

      
- Novos elementos multimídia 

    <blockquote>
        < audio>, < video>.        
    </blockquote>

- Novas APIs HTML5 (interfaces de programação de aplicativos)
As novas APIs mais interessantes em HTML5 são:

    - -Localização geográfica em HTML
    - -Arrastar e soltar HTML
    - -Armazenamento local em HTML
    - -Cache de aplicativo HTML
    - -Trabalhadores da Web em HTML
    - -SSE HTML

    - -Dica: o armazenamento local em HTML é um poderoso substituto para os cookies.

- A diferença entre < article> < section> e < div>

    Existe uma diferença confusa (falta de) no padrão HTML5, entre < article> < section>e < div>.

    - -No padrão HTML5, o < section>elemento é definido como um bloco de elementos relacionados.

    - -O < article> elemento é definido como um bloco completo e independente de elementos relacionados.

    - -O < div>elemento é definido como um bloco de elementos filhos.

    Como interpretar isso?
    No exemplo acima, usamos < section>como contêiner para relacionados < article>.
    Mas também poderíamos ter usado < article>como contêiner para artigos.

    Outros exemplos: 

    <blockquote>        
            <body>
                <header>
                    <h1>HTML5 Skeleton</h1>
                </header>
                <nav>                
                    <ul>
                        <li>News</li>
                        <li>Sports</li>
                        <li>Weather</li>
                    </ul>
                </nav>

                <article>
                    <h2>Famous Cities</h2>
                    <article>
                        <h2>London</h2>
                        <p>Texto grande</p>
                    </article>
                    <article>
                        <h2>Paris</h2>
                        <p>Paris is the capital and most populous city of France.</p>
                    </article>
                    <article>
                        <h2>Tokyo</h2>
                        <p>Texto grande</p>
                    </article>
                </article>

                <footer>
                    <p>&copy; 2014 W3Schools. All rights reserved.</p>
                </footer>
            < /body>      

    </blockquote>
    
    <blockquote>   
        
            <body>
                <header>
                <h1>HTML5 Skeleton</h1>
                </header>
                <nav>
                <ul>
                    <li>News</li>
                    <li>Sports</li>
                    <li>Weather</li>
                </ul>
                </nav>

                <article>
                    <h2>Famous Cities</h2>

                    <div class="city">
                        <h2>London</h2>
                        <p>Texto grande</p>
                    </div>

                    <div class="city">
                        <h2>Paris</h2>
                        <p>Paris is the capital and most populous city of France.</p>
                    </div>

                    <div class="city">
                        <h2>Tokyo</h2>
                        <p>Texto grande</p>
                    </div>
                </article>

                <footer>
                    <p>&copy; 2014 W3Schools. All rights reserved.</p>
                </footer>
            </body>
    </blockquote>
    
    <blockquote>
        <body>
            <header>
            <h1>HTML5 Skeleton</h1>
            </header>
            <nav>
            <ul>
                <li>News</li>
                <li>Sports</li>
                <li>Weather</li>
            </ul>
            </nav>

            <article>
                <section>
                    <h2>Famous Cities</h2>
                    <div class="city">
                    <h2>London</h2>
                    <p>London is the capital city of England. It is the most populous city in the United Kingdom, with a metropolitan area of over 13 million inhabitants.</p>
                    </div>

                    <div class="city">
                    <h2>Paris</h2>
                    <p>Paris is the capital and most populous city of France.</p>
                    </div>

                    <div class="city">
                    <h2>Tokyo</h2>
                    <p>Tokyo is the capital of Japan, the center of the Greater Tokyo Area, and the most populous metropolitan area in the world.</p>
                    </div>
                </section>

                <section>
                    <h2>Famous Countries</h2>
                    <div class="country">
                    <h2>England</h2>
                    <p>London is the capital city of England. It is the most populous city in the United Kingdom, with a metropolitan area of over 13 million inhabitants.</p>
                    </div>

                    <div class="country">
                    <h2>France</h2>
                    <p>Paris is the capital and most populous city of France.</p>
                    </div>

                    <div class="country">
                    <h2>Japan</h2>
                    <p>Tokyo is the capital of Japan, the center of the Greater Tokyo Area, and the most populous metropolitan area in the world.</p>
                    </div>
                </section>
            </article>

            <footer>
            <p>&copy; 2014 W3Schools. All rights reserved.</p>
            </footer>
        </body>    
    </blockquote>

- Elementos < figure> e < figcaption> HTML

    Uma imagem e uma legenda podem ser agrupadas em um < figure> elemento.
    O objetivo de uma legenda é adicionar uma explicação visual a uma imagem.  

    <blockquote>
        <figure>
            <img src="pic_trulli.jpg" alt="Trulli">
            <figcaption>Fig1. - Trulli, Puglia, Italy.</figcaption>
        </figure>
    </blockquote> 

    O < img>elemento define a imagem, o < figcaption> elemento define a legenda.


# Convenções de codificação e boas praticas

- -Use nomes dos elementos do HTML em minisculo
- -Fecha todos os elementos HTML, mesmo se for o "< p>", < p> texto </ p>
- -Usar nomes de atributos minisculo
- -Atributo de imagem sempre adicione o "Alt" e informe o tamanho!

    <blockquote>
        < img src="html5.gif" alt="HTML5" style="width:128px;height:128px">
    </blockquote>
- -Não bote espaço entre os sinais de iguadade
- -Não adicione linhas em branco sem um motivo.
- -Para facilitar a leitura, adicione dois espaços de recuo. Não use a tecla tab.
- -O < title>elemento é necessário em HTML. Torne o título o mais significativo possível, Para garantir a interpretação adequada e a indexação correta do mecanismo de pesquisa, o idioma e a codificação de caracteres devem ser definidos o mais cedo possível em um documento.

# Definindo a janela de exibição

- O HTML possui um método para permitir que os web designers assumam o controle sobre a janela de exibição, por meio da < meta>tag.

    A janela de visualização é a área visível do usuário de uma página da web. Varia de acordo com o dispositivo e será menor em um telefone celular do que na tela do computador.

    Você deve incluir o seguinte < meta>elemento de janela de visualização em todas as suas páginas da web:

    <blockquote>
        < meta name="viewport" content="width=device-width, initial-scale=1.0">

    </blockquote>

    Um < meta>elemento de janela de visualização fornece instruções ao navegador sobre como controlar as dimensões e a escala da página.

    A parte width = width do dispositivo define a largura da página para seguir a largura da tela do dispositivo (que variará dependendo do dispositivo).

    A parte inicial-scale = 1.0 define o nível de zoom inicial quando a página é carregada pela primeira vez pelo navegador.

# Imagens responsivas

- Usando a propriedade max-width

    Se a max-widthpropriedade estiver definida como 100%, a imagem será reduzida, se necessário, mas nunca será maior que o tamanho original:

    <blockquote>
        < img src="img_girl.jpg" style="max-width:100%;height:auto;">
    </blockquote>

# Mostrar imagens diferentes, dependendo da largura do navegador

- O < picture>elemento HTML permite definir imagens diferentes para diferentes tamanhos de janelas do navegador.

    <blockquote>
        <picture>
            <source srcset="img_smallflower.jpg" media="(max-width: 600px)">
            <source srcset="img_flowers.jpg" media="(max-width: 1500px)">
            <source srcset="flowers.jpg">
            <img src="img_smallflower.jpg" alt="Flowers">
        </picture>
    </blockquote>

    exemplo na pratica : https://www.w3schools.com/html/tryit.asp?filename=tryhtml_responsive_picture

# Tamanho do texto responsivo

- O tamanho do texto pode ser definido com uma unidade "vw", que significa "largura da janela de exibição". Dessa forma, o tamanho do texto seguirá o tamanho da janela do navegador:

    <blockquote>
        <!DOCTYPE html>
        <html>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <body>

        <h1 style="font-size:10vw;">Responsive Text</h1>

        <p style="font-size:5vw;">Resize the browser window to see how the text size scales.</p>

        <p style="font-size:5vw;">Use the "vw" unit when sizing the text. 10vw will set the size to 10% of the viewport width.</p>

        <p>Viewport is the browser window size. 1vw = 1% of viewport width. If the viewport is 50cm wide, 1vw is 0.5cm.</p>

        </body>
        </html>

    </blockquote>

# Consultas de mídia


https://www.w3schools.com/html/tryit.asp?filename=tryhtml_responsive_media_query
