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
        <header>, <footer>, <article>, e <section>.        
    </blockquote>
    
- Novos elementos gráficos

    <blockquote>
        <svg>, <canvas>.        
    </blockquote>

      
- Novos elementos multimídia 

    <blockquote>
        <audio>, <video>.        
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

    No padrão HTML5, o < section>elemento é definido como um bloco de elementos relacionados.

    O < article> elemento é definido como um bloco completo e independente de elementos relacionados.

    O < div>elemento é definido como um bloco de elementos filhos.

    Como interpretar isso?

    No exemplo acima, usamos < section>como contêiner para relacionados < article>.

    Mas também poderíamos ter usado < article>como contêiner para artigos.

    Outros exemplos: 

    <blockquote>

        < !DOCTYPE html>
        < html lang="en">
            <head>
                <title>HTML5</title>
                <meta charset="utf-8"> 
            </head>
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
                        <p>London is the capital city of England. It is the most populous city in the United Kingdom, with a metropolitan area of over 13 million inhabitants.</p>
                    </article>

                    <article>
                        <h2>Paris</h2>
                        <p>Paris is the capital and most populous city of France.</p>
                    </article>

                    <article>
                        <h2>Tokyo</h2>
                        <p>Tokyo is the capital of Japan, the center of the Greater Tokyo Area, and the most populous metropolitan area in the world.</p>
                    </article>
                </article>

                <footer>
                    <p>&copy; 2014 W3Schools. All rights reserved.</p>
                </footer>

            < /body>
        < /html> 

    </blockquote>
    
    <blockquote>
    
        <!DOCTYPE html>
        <html lang="en">
            <head>
            <title>HTML5</title>
            <meta charset="utf-8">
            </head>
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
                </article>

                <footer>
                <p>&copy; 2014 W3Schools. All rights reserved.</p>
                </footer>

            </body>
        </html>

    </blockquote>
    
    <blockquote></blockquote>


