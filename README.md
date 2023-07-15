<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guilherme - Desenvolvedor</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #00BFFF;
            padding: 20px;
            text-align: center;
        }

        h1 {
            color: white;
        }

        main {
            padding: 20px;
        }

        section {
            margin-bottom: 20px;
        }

        h2 {
            border-bottom: 1px solid #ccc;
            padding-bottom: 5px;
        }

        .social-icons {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }

        .social-icons a {
            color: #fff;
            font-size: 24px;
            text-decoration: none;
            background-color: #333;
            padding: 10px;
            border-radius: 50%;
        }

        @media screen and (max-width: 600px) {
            .social-icons {
                flex-wrap: wrap;
            }
        }

        .technologies img {
            margin-right: 10px;
        }

        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .project-card {
            background-color: #f0f0f0;
            padding: 10px;
            border-radius: 5px;
        }
    </style>
</head>

<body>
    <header>
        <h1>Olá! Eu sou o Guilherme.</h1>
        <div>
            <a href="https://git.io/typing-svg">
                <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=00BFFF&center=falso&vCenter=falso&repeat=verdadeiro&width=435&lines=Desenvolvedor+Web;Estudante+de+Ci%C3%AAncia+da+Computa%C3%A7%C3%A3o."
                    alt="Typing SVG" />
            </a>
        </div>
    </header>

    <main>
        <section>
            <h2>Sobre Mim</h2>
            <p>Olá! Eu sou Guilherme, um desenvolvedor web apaixonado por tecnologia e programação. Atualmente, estudo Ciência da Computação e estou focado em aprender novas tecnologias e aprimorar minhas habilidades de desenvolvimento.</p>
        </section>

        <section>
            <h2>Redes Sociais</h2>
            <div class="social-icons">
                <a href="https://www.linkedin.com/in/guilherme-francisco-6938b91b4/" target="_blank">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linkedin/linkedin-original.svg" alt="LinkedIn">
                </a>
                <a href="mailto:guilhermevs@gmail.com" target="_blank">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/gmail/gmail-original.svg" alt="Gmail">
                </a>
                <a href="https://discord.com/users/#7334" target="_blank">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/discord/discord-original.svg" alt="Discord">
                </a>
            </div>
        </section>

        <section>
            <h2>Tecnologias que Utilizo</h2>
            <div class="technologies">
                <img src="https://user-images.githubusercontent.com/84246094/134066180-d11880e0-f92f-47da-9f70-1b5d7c39934b.png" alt="HTML">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="CSS3">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python">
                <img src="https://user-images.githubusercontent.com/84246094/180622105-6de2c096-27b5-4469-8189-7a0175a0a903.png" alt="Estruturas">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg" alt="MySQL">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="PostgreSQL">
            </div>
        </section>

        <section>
            <h2>Projetos</h2>
            <div class="projects">
                <!-- Aqui você pode adicionar os cards dos seus projetos -->
                <div class="project-card">
                    <h3>Projeto 1</h3>
                    <p>Descrição do projeto 1.</p>
                </div>
                <div class="project-card">
                    <h3>Projeto 2</h3>
                    <p>Descrição do projeto 2.</p>
                </div>
            </div>
        </section>
    </main>
</body>

</html>
