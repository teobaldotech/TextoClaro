# ✍️ Corretor Inteligente PRO ULTRA

> Uma ferramenta web moderna, elegante e de alta performance para correção gramatical, ortográfica e análise inteligente de textos em tempo real.

---

## 🚀 Funcionalidades

* **🔍 Correção Inteligente:** Integração com a API do **LanguageTool** para detecção avançada de erros gramaticais e ortográficos em vários idiomas.
* **⚡ Correção em Massa:** Aplique todas as sugestões válidas de uma só vez de forma otimizada.
* **📊 Estatísticas em Tempo Real:** Acompanhe contagens dinâmicas de caracteres, palavras, frases e erros identificados.
* **🌓 Tema Escuro / Claro:** Alternância fluida de tema com persistência de preferência via `localStorage`.
* **↩️ Desfazer / Refazer:** Suporte completo a histórico de alterações (`Ctrl + Z` / `Ctrl + Y`).
* **🕘 Histórico de Análises:** Salve e consulte análises anteriores diretamente num modal dedicado.
* **📂 Importação e Exportação:** Carregue ficheiros de texto (`.txt`, `.md`) ou faça o download do texto editado instantaneamente.
* **🔊 Leitura por Voz:** Recurso de síntese de voz para audição do conteúdo.

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi desenvolvido utilizando tecnologias web nativas, sem dependências de frameworks pesados, garantindo leveza e rapidez:

* **HTML5** (Estruturação semântica)
* **CSS3** (Variáveis CSS, Flexbox, Grid Layout, Design Responsivo e Modo Escuro)
* **JavaScript (ES6+)** (Manipulação de DOM, Async/Await, Fetch API, LocalStorage)
* **LanguageTool API** (Motor de verificação gramatical)

---

## 📦 Como Usar

Como se trata de uma aplicação web de ficheiro único (Single-Page Application), a utilização é extremamente simples:

1. Faça o download ou copie o código fonte do ficheiro HTML (`corretor_inteligente_pro_ultra.html`).
2. Abra o ficheiro em qualquer navegador web moderno (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari).
3. Digite ou cole o seu texto na área designada, escolha o idioma desejado e clique em **"Analisar texto"**.

---

## ⚙️ Configuração e Personalização

No cabeçalho do script JavaScript da aplicação, pode ajustar parâmetros como:

```javascript
const MAX_TEXT_LENGTH = 60000; // Limite máximo de caracteres por análise
const MAX_HISTORY = 20;        // Limite de itens salvos no histórico
const MAX_UNDO = 30;           // Limite de passos na pilha de desfazer
