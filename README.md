# 💼 Portfólios Profissionais — Programação para Internet I

## 👥 Integrantes da Equipe
- **Álvaro Miguel Rodrigues Aquino Costa**
- **Francisco de Cássio da Silva Mourão Júnior**

---

## 🎯 Tema Escolhido
**Desenvolvedor Full Stack**
*(Foco em estruturação semântica com design moderno responsivo em Dark Mode).*

---

## 📝 Breve Descrição do Portfólio
O projeto consiste em uma plataforma web composta por uma página principal (`index.html`) que atua como um hub central. A partir dela, é possível navegar de forma fluida para os portfólios individuais de cada desenvolvedor. 

Ambos os portfólios apresentam informações sobre a trajetória acadêmica e profissional dos integrantes, uma grade detalhada de competências técnicas (skills), histórico de experiências, exibição de projetos hospedados no GitHub e um formulário funcional para envio de mensagens.

---

## 🧠 Principais Desafios Encontrados
1. **Responsividade sem Frameworks:** Ajustar as tabelas de dados e o alinhamento dos cards para que quebrassem e se empilhassem corretamente em telas de celulares pequenos, utilizando exclusivamente CSS Puro.
2. **Modularização e Especificidade do CSS:** Organizar a folha de estilos globais (`global.css`) e as folhas específicas de cada portfólio (`portfolios.css` e `style.css`) de modo que as regras de estilização não gerassem conflitos de especificidade, mantendo uma identidade visual coesa em todo o projeto.
3. **Integração de Formulário Nativo (`mailto:`):** Mapear os inputs do formulário de contato para os parâmetros nativos do cliente de e-mail, mantendo a formatação e quebras de linha limpas.

---

## 🛠️ O que cada Integrante Fez

### **Francisco de Cássio**
- Estruturação semântica e desenvolvimento arquitetural da página central (`index.html`).
- Desenvolvimento dos textos e escolha dos icons da sua página individual (`portfolios/cassio.html`).
- Alteração nas visitas das páginas e passeio pelas próprias páginas.
- Correção dos formulários de contato integrado ao e-mail dos portfólios individuais.

### **Álvaro Miguel**
- Estruturação e desenvolvimento do modelo das portfólios individuais (`portfolios/alvaro.html`, `portfolios/cassio.html`).
- Correção de bugs de links e escolha do icon da logo das páginas.
- Estruturação semântica, catalogação de habilidades e preenchimento de tabelas do seu portfólio individual (`portfolios/alvaro.html`).

---

## 🔗 Link do GitHub Pages
O projeto publicado pode ser acessado diretamente através do link:  
👉 [Página do GitHub Pages](https://francisco-cassio.github.io/trabalho_portfolio/)

---

## 🎥 Link do Vídeo de Apresentação
O vídeo explicativo detalhando o código-fonte, a estrutura das folhas de estilo e a responsividade em múltiplos dispositivos pode ser assistido aqui:  
👉 [Assista ao vídeo de apresentação](LINK_DO_VIDEO)

---

## 🛠️ Tecnologias Utilizadas e Restrições

De acordo com as diretrizes do projeto, não foram utilizadas frameworks ou bibliotecas externas (como Bootstrap ou Tailwind). Todo o ecossistema visual foi construído de forma nativa:

- **HTML5:** Estruturação semântica (uso de `<header>`, `<main>`, `<section>`, `<article>`, `<footer>`).
- **CSS3 Puro:** Customização estética com variáveis (`:root`), animações (`@keyframes`), efeitos de brilho em néon e layouts modernos.
- **Responsividade Nativa:** Uso estratégico de *Media Queries* e unidades fluídas (`clamp()`, `rem`) para adaptação total a smartphones, tablets e desktops.
- **Fontes Google Fonts:** Uso das famílias tipográficas *Space Mono* e *Sora*.

---

## 📂 Organização dos Arquivos

```text
.
├── css/
│   ├── global.css        # Variáveis de cores, fontes e estilos globais
│   ├── portfolios.css    # Estilização das páginas individuais dos portfólios
│   └── style.css         # Estilização da página principal
├── img/
│   ├── projetos/
│   │   ├── alvaro/       # Capturas de tela dos projetos do Álvaro
│   │   │   ├── projeto_agendamento.jpeg
│   │   │   ├── projeto_api.jpeg
│   │   │   └── projeto_remicao.jpeg
│   │   └── cassio/       # Capturas de tela dos projetos do Cássio
│   │       ├── projeto-jogo.png
│   │       ├── projeto-lavanderia.png
│   │       └── projeto-rapa.png
│   ├── alvaro.jpeg       # Foto de perfil do Álvaro
│   ├── cassio.jpeg       # Foto de perfil do Cássio
│   └── favicon.png       # Ícone da aba do navegador
├── portfolios/
│   ├── alvaro.html       # Página de portfólio do Álvaro Miguel
│   └── cassio.html       # Página de portfólio do Francisco de Cássio
└── index.html            # Página principal
```

---

## 🔧 Como Executar Este Projeto Localmente

1. **Clone este repositório:**

```bash
git clone https://github.com/Francisco-Cassio/trabalho_portfolio.git
```

2. **Acesse a pasta raiz do projeto:**

```bash
cd trabalho_portfolio
```

3. **Abra a aplicação**

Abra o arquivo `index.html` diretamente em qualquer navegador web ou utilize a extensão Live Server do VS Code para rodar a aplicação localmente.

---

**Desenvolvido por:** Álvaro Miguel Rodrigues Aquino Costa e Francisco de Cássio da Silva Mourão Júnior.

**Instituição:** Instituto Federal de Educação, Ciência e Tecnologia do Piauí (IFPI) - Campus Teresina Central.