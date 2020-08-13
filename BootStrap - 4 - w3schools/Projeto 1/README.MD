# BootStrap 4 

- Base de estudo: https://www.w3schools.com/bootstrap4/default.asp


# Principais classes 

- https://www.w3schools.com/bootstrap4/bootstrap_utilities.asp


# Existem duas classes de contêineres

- classe ".container"

    - A .containerclasse fornece um contêiner de largura fixa responsivo.

    - A .container-fluidclasse fornece um contêiner de largura total , abrangendo toda a largura da viewport.

# O exemplo de página básica do Bootstrap 4

- Exemplo

    <blockquote>

        <!DOCTYPE html>    
        <html lang="en">
            <head>
                <title>Bootstrap 4 Example</title>
                <meta charset="utf-8">

                <meta name="viewport" content="width=device-width, initial-scale=1">

                <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css">
                
                <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
                
                <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
                
                <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js"></script>
                
            </head>
            <body>

                <div class="container">

                    <h1>My First Bootstrap Page</h1>
                    <p>This is some text.</p>
                    
                </div>

            </body>
        </html>


    </blockquote>



# Container fixo

- largura máxima

    - Extra pequeno <576px ,         100%
    - ≥576px pequeno,                540px
    - Médio ≥768px,                  720px
    - Grande ≥992px,                 960px
    - Extra Grande ≥1200px,          1140px

# Contentores responsivos

- Você também pode usar as .container-sm|md|lg|xlclasses para criar contêineres responsivos.

    - .container-sm	100%	540px	720px	960px	1140px
    - .container-sm	100%	540px	720px	960px	1140px
    - .container-lg	100%	100%	100%	960px	1140px
    - .container-lg	100%	100%	100%	960px	1140px

# Sistema de grade do Bootstrap 4

- O sistema de grade do Bootstrap é construído com flexbox e permite até 12 colunas na página.
    Se você não quiser usar todas as 12 colunas individualmente, poderá agrupá-las para criar colunas mais amplas.

    - O sistema de grade do Bootstrap 4 possui cinco classes:

    - .col- (dispositivos pequenos demais - largura da tela menor que 576 px)
    - .col-sm- (dispositivos pequenos - largura da tela igual ou superior a 576 px)
    - .col-md- (dispositivos médios - largura da tela igual ou superior a 768 px)
    - .col-lg- (dispositivos grandes - largura da tela igual ou superior a 992 px)
    - .col-xl- (dispositivos ampliados - largura da tela igual ou superior a 1200 px)

    As classes acima podem ser combinadas para criar layouts mais dinâmicos e flexíveis.

    Dica: Cada classe aumenta de escala; portanto, se você deseja definir as mesmas larguras para sme md, é necessário apenas especificar sm.

    Cria uma div com a classe "row", depois define o valor da coluna "col-sm-x"


# Bootstrap 4 Text/Typography









