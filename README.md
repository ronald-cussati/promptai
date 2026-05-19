# PromptAI — Gerador de Prompts

Transforme descrições simples em prompts otimizados para inteligência artificial em segundos.

**Acesse:** [ronald-cussati.github.io/promptai](https://ronald-cussati.github.io/promptai/)

## Sobre o Projeto

PromptAI é uma aplicação web 100% frontend que resolve um problema real: formular prompts eficientes para IA. Basta descrever sua necessidade em linguagem natural, ajustar os parâmetros desejados e o PromptAI gera um prompt estruturado e pronto para uso.

O projeto foi desenvolvido com foco em usabilidade, performance e privacidade — sem backend, sem vazamento de dados, tudo armazenado localmente no navegador.

## Funcionalidades

- **Múltiplos modelos de IA** — ChatGPT, Claude, Gemini, Perplexity, Copilot, MidJourney, DALL-E e outros
- **Controle total do prompt** — ajuste tom, tamanho e idioma de saída
- **Geração com 1 clique** — ou use o atalho `Ctrl + Enter`
- **Histórico local** — prompts salvos no navegador (localStorage)
- **Tema dark/light** — alternância entre modo escuro e claro
- **Tutorial integrado** — onboarding em 5 passos para configuração rápida
- **100% frontend** — zero backend, zero servidor externo, seus dados ficam com você
- **API Gemini** — integração com limite gratuito incluso (60 requisições/minuto)

## Tecnologias Utilizadas

| Tecnologia | Finalidade |
|------------|------------|
| JavaScript (Vanilla) | Lógica da aplicação |
| HTML5 | Estrutura das páginas |
| CSS3 | Estilização e design responsivo |
| Gemini API | Geração dos prompts |
| localStorage | Armazenamento local do histórico |

## Como Usar

### 1. Obtenha sua chave da API Gemini

Acesse [aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey) e gere sua chave gratuitamente.

### 2. Configure o aplicativo

Clique no ícone de engrenagem ⚙ e cole sua chave no campo **"Chave da API Gemini"**.

### 3. Selecione os parâmetros

Escolha o modelo de IA desejado, tom, tamanho e idioma de saída.

### 4. Descreva sua necessidade

Escreva no campo de texto o que você precisa gerar (ex: "um e-mail de follow-up para cliente que não respondeu").

### 5. Gere e use o prompt

Clique em **"Gerar Prompt"** ou pressione `Ctrl + Enter` e copie o resultado.

## Estrutura do Projeto
```
promptai/
├── index.html          # Página principal
├── styles.css          # Estilos da aplicação
├── script.js           # Lógica JavaScript
└── assets/
    ├── favicon.ico     # Favicon do projeto
    └── ...             # Imagens e recursos
```

## Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

## Autor

**Ronald Cussati** — [rc.dev](https://ronald-cussati.github.io/)

Estudante de Sistemas de Informação | Desenvolvedor Front-end | Suporte Técnico

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/ronald-cussati)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/ronald-cussati)
