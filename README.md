## Sobre mim

Olá! Meu nome é Daniel Campos da Cruz e sou um entusiasta da tecnologia apaixonado por inteligência artificial. Com apenas 19 anos, estou no início da minha jornada na área de ciência de dados e machine learning. Atualmente, estou aprimorando minhas habilidades através do Bootcamp de Ciência de Dados na Practicum e tenho buscado conhecimento por meio de diversos cursos na plataforma Alura.

## O que você encontrará neste repositório

Neste repositório, você encontrará uma variedade de projetos e trabalhos relacionados ao meu aprendizado e exploração na área de ciência de dados e machine learning. Estou constantemente atualizando e aprimorando meu conhecimento, por isso, sinta-se à vontade para explorar e fornecer feedback construtivo.

## Principais interesses

- Ciência de Dados
- Machine Learning
- Inteligência Artificial
- Python
- Estatísticas
- Análise de Dados
- Comportamento Humano

## Como me encontrar

LinkedIn: [LinkedIn](https://www.linkedin.com/in/daniel-campos-b39881278/)

E-mail: daneilcempusprog@gmail.com

## Agradecimentos

Agradeço por visitar meu GitHub e por acompanhar minha jornada de aprendizado em ciência de dados e inteligência artificial. Fique à vontade para entrar em contato comigo por meio do LinkedIn ou e-mail para discutir colaborações, projetos ou apenas para trocar ideias. Seu apoio e feedback são muito bem-vindos!
-->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        /* Estilos CSS para o conteúdo expansível */
        .conteudo-expansivel {
            display: none;
        }
    </style>
</head>
<body>
    <!-- Aba clicável -->
    <div id="aba" onclick="toggleConteudo()">Clique para Expandir</div>
    
    <!-- Conteúdo expansível -->
    <div id="conteudo" class="conteudo-expansivel">
        <p>Aqui estão algumas informações adicionais que podem ser expandidas ou minimizadas.</p>
    </div>

    <script>
        // Função para expandir/minimizar o conteúdo
        function toggleConteudo() {
            var conteudo = document.getElementById("conteudo");
            if (conteudo.style.display === "none") {
                conteudo.style.display = "block";
                document.getElementById("aba").textContent = "Clique para Minimizar";
            } else {
                conteudo.style.display = "none";
                document.getElementById("aba").textContent = "Clique para Expandir";
            }
        }
    </script>
</body>
</html>
