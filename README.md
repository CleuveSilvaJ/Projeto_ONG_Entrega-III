# 🌱 EXP. PRÁTICA 3 — ONG Raízes do Amanhã

Este projeto é uma aplicação web do tipo **SPA (Single Page Application)** desenvolvida para representar a atuação da ONG Raízes do Amanhã. A interface apresenta informações institucionais, projetos sociais e um formulário de cadastro para voluntários.  
**Esta atividade faz parte da disciplina de Desenvolvimento Front-End Para Web da Faculdade Cruzeiro do Sul.**

---

## 📁 Estrutura de Pastas

```
EXP. PRATICA 3/
├── index.html
├── assets/
│   ├── imagens/
│   │   ├── banner-raizes.jpg
│   │   ├── cadastro-banner.jpg
│   │   ├── projeto1.jpg
│   │   ├── projeto2.jpg
│   │   └── projeto3.jpg
│   ├── css/
│   │   └── style.css
│   └── js/
│       ├── app.js
│       ├── router.js
│       ├── templates.js
│       └── formValidator.js
```

---

## ⚙️ Funcionalidades

- Navegação dinâmica entre páginas via JavaScript (SPA)
- Menu responsivo com botão hambúrguer para dispositivos móveis
- Página inicial com banner e descrição dos projetos
- Página de projetos com cartões ilustrativos e tags temáticas
- Página de cadastro com formulário completo e validação
- Feedback visual para sucesso ou erro no envio do formulário
- Armazenamento local dos dados básicos com `localStorage`

---

## 🎨 Estilo e Design

- Sistema de design com variáveis CSS (`:root`) para cores, fontes e espaçamentos
- Layout responsivo com media queries
- Estilização de botões, formulários, cartões e rodapé centralizado

---

## 🚀 Como Executar

1. Abra o arquivo `index.html` em um navegador moderno.
2. Navegue pelas abas "Início", "Projetos" e "Cadastro" usando o menu.
3. Preencha o formulário de cadastro e envie para visualizar a validação.

> O projeto funciona 100% no navegador, sem necessidade de servidor ou backend.

---

## 🧹 Observações

- Os arquivos `cadastro.html` e `projetos.html` foram removidos, pois a navegação é feita via SPA.
- O projeto foi desenvolvido com foco em boas práticas de HTML, CSS e JavaScript puro.
