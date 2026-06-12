### 📊 Status do Player

<div align="center">
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=AlvexGR777&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true" />
  <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AlvexGR777&layout=compact&theme=tokyonight" />
</div>

### Quem seria esse tal de Gustavo?
Um estudante de desenvolvimento web, focado em criar interfaces modernas e funcionais. Estou sempre buscando evoluir minhas habilidades e transformar ideias em código, tenho mais apreço pela parte dos "bastidores" desse show de inovação e surpresas que é a área de tecnologia!

---

### 🛠️ Hard Skills

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)


## 🧠 Soft Skills
💬 Comunicativo
🤝 Colaboração em equipe
🎯 Pensamento Crítico
🧠 Adaptabilidade
🫶 Empatia


---

## 🚀 Meus Projetos

### 🎧 Nightnotes
> "Plataforma desktop de culturas audiovisuais de forma em que abranja com foco um público mais introspectivo que prefere pegar seu fone e viajar, entrar em seu próprio mundo pela música."

* **Tecnologias:** ![HTML5](https://img.shields.io/badge/html-E34F26?style=flat-square) ![CSS3](https://img.shields.io/badge/css-1572B6?style=flat-square)
* 🔍 *Bateu a curiosidade de saber como ou o que é essa plataforma?* [Acesse o repositório do projeto aqui]( https://github.com/AlvexGR777/NIGHTNOTES.git))


---

## 📬 Despertei seu interesse? Entre em contato e vamos fazer uma conexão!

* **LinkedIn:** [Gustavo Alves](https://www.linkedin.com/in/gustavo-alves-r2026/?utm_source=share_via&utm_content=profile&utm_medium=android)
* **E-mail:** guh0908@gmail.com

* <section class="contato-container">
    <h2>Vamos nos conectar?</h2>
    
    <div class="cards-contato">
        <!-- Card 1: LinkedIn (A Carta) -->
        
  <a href="https://www.linkedin.com/in/gustavo-alves-r2026/?utm_source=share_via&utm_content=profile&utm_medium=android)" target="_blank" class="card-conexao card-linkedin">
            <div class="icone-animado">
                <div class="envelope">
                    <div class="aba"></div>
                    <div class="carta">
                        <i class="fab fa-linkedin-in"></i> 
                    </div>
                </div>
            </div>
            <h3>LinkedIn</h3>
            <p>Envie uma carta profissional para a minha rede.</p>
        </a>

        Card 2: E-mail (O Celular) 

  <a href="mailto:guh0908@gmail.com" class="card-conexao card-email">
            <div class="icone-animado">
                <div class="celular">
                    <div class="tela">
                        <div class="mensagem">Mensagem Enviada!</div>
                        <div class="botao-enviar"></div>
                    </div>
                </div>
            </div>
            <h3>E-mail</h3>
            <p>Me mande uma mensagem direta no celular.</p>
        </a>
    </div>
</section>


<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

/* Container Geral de Contatos */
.contato-container {
    text-align: center;
    padding: 60px 20px;
    background-color: #13141f; /* Fundo escuro combinando com o tema dark */
    color: #ffffff;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

.contato-container h2 {
    font-size: 2.5rem;
    margin-bottom: 40px;
    color: #00e676; /* Tom verde brilhante ou a cor do seu tema */
}

.cards-contato {
    display: flex;
    justify-content: center;
    gap: 40px;
    flex-wrap: wrap;
}

/* Estilo Base dos Cards */
.card-conexao {
    background: #1c1d2e;
    border: 2px solid #2a2b45;
    border-radius: 15px;
    padding: 30px;
    width: 260px;
    text-decoration: none;
    color: #fff;
    transition: all 0.4s ease;
    display: flex;
    flex-direction: column;
    align-items: center;
    cursor: pointer;
}

.card-conexao:hover {
    transform: translateY(-10px);
    border-color: #00e676;
    box-shadow: 0 10px 20px rgba(0, 230, 118, 0.2);
}

.card-conexao h3 {
    margin: 20px 0 10px 0;
    font-size: 1.4rem;
}

.card-conexao p {
    font-size: 0.9rem;
    color: #a0a5c1;
    text-align: center;
    line-height: 1.4;
}

/* ========================================================
   ANIMACAO 1: A CARTA DO LINKEDIN
   ======================================================== */
.envelope {
    width: 60px;
    height: 40px;
    background: #0077b5; /* Azul LinkedIn */
    position: relative;
    border-radius: 0 0 5px 5px;
    margin-top: 20px;
}

/* Aba do envelope */
.envelope::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    border-left: 30px solid transparent;
    border-right: 30px solid transparent;
    border-top: 25px solid #005a8a;
    transform-origin: top;
    transition: transform 0.4s ease;
    z-index: 3;
}

/* A folha/carta dentro */
.carta {
    position: absolute;
    width: 50px;
    height: 35px;
    background: #ffffff;
    bottom: 5px;
    left: 5px;
    z-index: 2;
    transition: transform 0.4s ease;
    display: flex;
    justify-content: center;
    align-items: center;
}

.carta i {
    color: #0077b5;
    font-size: 1.2rem;
}

/* Efeito Hover da Carta voando */
.card-linkedin:hover .envelope::before {
    transform: rotateX(180deg); /* Abre a aba */
}

.card-linkedin:hover .carta {
    transform: translateY(-25px); /* A carta sobe para fora */
    animation: flutuarCarta 1.5s infinite ease-in-out 0.4s;
}

@keyframes flutuarCarta {
    0%, 100% { transform: translateY(-25px); }
    50% { transform: translateY(-32px); }
}


.celular {
    width: 45px;
    height: 80px;
    border: 3px solid #a0a5c1;
    border-radius: 8px;
    position: relative;
    padding: 4px;
    background: #111;
    transition: border-color 0.4s;
}

.tela {
    width: 100%;
    height: 100%;
    background: #222;
    border-radius: 4px;
    position: relative;
    overflow: hidden;
}

/* Botão de enviar simulado */
.botao-enviar {
    width: 12px;
    height: 12px;
    background: #00e676;
    border-radius: 50%;
    position: absolute;
    bottom: 8px;
    left: 50%;
    transform: translateX(-50%);
    transition: transform 0.2s;
}


.mensagem {
    position: absolute;
    width: 80%;
    background: #00e676;
    color: #000;
    font-size: 0.5rem;
    font-weight: bold;
    text-align: center;
    padding: 4px 2px;
    border-radius: 3px;
    bottom: -30px;
    left: 10%;
    opacity: 0;
    transition: all 0.4s ease;
}


.card-email:hover .celular {
    border-color: #00e676;
}

.card-email:hover .botao-enviar {
    transform: translateX(-50%) scale(0.8);
}

.card-email:hover .mensagem {
    opacity: 1;
    bottom: 30px; /* Mensagem sobe na tela simulando o envio */
}
