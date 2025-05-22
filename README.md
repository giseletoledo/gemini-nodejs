# Gemini API: Gerador de Conteúdo com Google Generative AI

Este projeto é um exemplo simples de como utilizar a API **Google Generative AI (Gemini)** com Node.js para gerar conteúdo com base em um prompt de texto.

## 🧠 O que o código faz?

O script realiza as seguintes tarefas:

1. Carrega variáveis de ambiente com `dotenv`.
2. Inicializa a API `GoogleGenerativeAI` com uma chave fornecida pelo usuário.
3. Usa o modelo `gemini-1.5-flash` para gerar uma resposta baseada no prompt: **"Me fale sobre Typescript"**.
4. Imprime a resposta gerada no console.

## 📦 Requisitos

* Node.js (v18 ou superior recomendado, por suporte ao top-level `await`)
* Conta e chave de API ativa na [Google Generative AI](https://ai.google.dev/)
* Token da API (API\_KEY)
* Dependências do projeto:

```bash
npm install dotenv @google/generative-ai
```

## 🔧 Como usar

1. Clone ou copie este repositório.
2. Crie um arquivo `.env` na raiz do projeto e adicione sua chave de API:

```
API_KEY=your_google_gen_ai_api_key_here
```

3. Execute o script com suporte a top-level `await` (ex: com Node.js v18+ ou usando `--input-type=module`):

```bash
node index.js
```

> Certifique-se de que o arquivo tem extensão `.mjs` ou que seu `package.json` tenha `"type": "module"` para permitir o uso de `import` e `await` no topo.

## 📝 Exemplo de saída

```txt
TypeScript é uma linguagem de programação desenvolvida pela Microsoft que é um superconjunto do JavaScript...
```

## 📚 Referências

* [Google Generative AI Node.js SDK](https://github.com/google/generative-ai-js)
* [Documentação da Gemini API](https://ai.google.dev/)
* [Dotenv](https://www.npmjs.com/package/dotenv)

