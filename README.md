<div align="center">
  <img src="./assets/demo.gif" alt="Demonstração Animada do Clone do Disney+" width="800">
</div>

# 🎬 Disney+ Landing Page Clone

[![Repo Size](https://img.shields.io/github/repo-size/gugainglez2/clone_disneyplus?style=for-the-badge&color=8A2BE2)](https://github.com/gugainglez2/clone_disneyplus)
[![Language](https://img.shields.io/github/languages/top/gugainglez2/clone_disneyplus?style=for-the-badge&color=0099FF)](https://github.com/gugainglez2/clone_disneyplus)

Este projeto é um clone da **Landing Page oficial de assinatura do Disney+**. O objetivo principal foi recriar com máxima fidelidade a página de conversão e venda do serviço, aplicando técnicas avançadas de desenvolvimento frontend.

> 🎓 **Projeto Acadêmico:** Desenvolvido como parte do programa de formação em Frontend da **EBAC (Escola Britânica de Artes Criativas e Tecnologia)**.

---

## 🚀 Tecnologias Utilizadas

* **HTML5** – Estruturação semântica da página de vendas.
* **SASS (SCSS)** – Organização de estilos de forma modular, uso de variáveis para a identidade visual da marca e mixins para responsividade.
* **JavaScript (ES6+)** – Adição de interatividade na página (efeitos de scroll, abas e sanfonas de dúvidas).
* **Gulp** – Automação de tarefas para compilação do SASS, minificação de arquivos de script e otimização das imagens de divulgação.

---

## ✨ Funcionalidades Recriadas

* **Seção Hero de Conversão:** O topo clássico da página com a chamada para ação (CTA) e planos de assinatura bem destacados.
* **Grid de Combos e Planos:** Apresentação visualmente limpa dos pacotes disponíveis (*Disney+, Star+, Lionsgate+*, etc.).
* **Seção de FAQ (Perguntas Frequentes):** Sistema de *Accordion* (sanfona) interativo via JavaScript para expandir e recolher as dúvidas mais comuns.
* **Efeito de Scroll no Header:** O menu superior ganha opacidade dinamicamente à medida que o usuário rola a página para baixo, melhorando a legibilidade.
* **Design Totalmente Responsivo:** Interface otimizada para smartphones, tablets e desktops.

---

## 🛠️ Como Executar o Projeto Localmente

### Pré-requisitos
Você precisará ter o [Node.js](https://nodejs.org/) instalado.

### Passo a Passo

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/gugainglez2/clone_disneyplus.git
Entre na pasta do projeto:

Bash
cd clone_disneyplus
Instale as dependências do projeto:

Bash
npm install
Inicie o ambiente de desenvolvimento (Gulp):

Bash
npm run dev
(Nota: Caso seu script principal use outro comando, execute gulp ou o comando configurado em seu package.json)

📂 Estrutura Estrutural
Plaintext
clone_disneyplus/
├── src/
│   ├── assets/        # Imagens publicitárias, logos e ícones oficiais
│   ├── scripts/       # Lógica JavaScript (FAQ, Efeitos de Scroll)
│   └── styles/        # Estilização organizada com SASS (.scss)
├── dist/              # Arquivos finais otimizados gerados pelo Gulp
├── index.html         # Estrutura principal da Landing Page
└── package.json       # Dependências de desenvolvimento
🧠 Principais Aprendizados (EBAC)
Organização BEM: Criação de classes CSS limpas e fáceis de dar manutenção seguindo a metodologia Block, Element, Modifier.

Automação de Workflow: Configuração do Gulp para automatizar processos repetitivos de desenvolvimento, simulando o dia a dia do mercado.

Manipulação Limpa do DOM: Implementação de componentes nativos de UI (abas e accordion) usando JS puro (Vanilla JS).

⚠️ Aviso Legal
Este é um projeto estritamente para fins acadêmicos e de portfólio. Todos os direitos de imagem, marcas registradas, logos e identidade visual pertencem à The Walt Disney Company.
