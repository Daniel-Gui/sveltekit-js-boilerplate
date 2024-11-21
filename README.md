# SvelteKit 5 JS Boilerplate 🚀
Um boilerplate eficiente para SvelteKit, projetado para agilizar o desenvolvimento de aplicações modernas. Inclui configurações otimizadas para deploy na Cloudflare Pages e ferramentas essenciais para um fluxo de trabalho produtivo.

📋 Funcionalidades
- Configuração inicial simplificada: Comece rapidamente com uma estrutura pronta para uso.
- Deploy na Cloudflare Pages: Configurações ajustadas para implementação fácil e eficiente.
- Bibliotecas essenciais: Ferramentas populares já integradas para maximizar sua produtividade.

## 📦 Libs
- Tailwindcss + typography & forms
- Lucide Icons

## 🚀 Começando
Pré-requisitos
Certifique-se de ter o **Node.js e o npm instalados** em sua máquina.

Instalação
Clone o repositório:

```bash
git clone https://github.com/Daniel-Gui/sveltekit-js-boilerplate
cd sveltekit-js-boilerplate
```
Instale as dependências:

```bash
npm install
```
Inicie o servidor local:

```bash
npm run dev
```

## 🌐 Deploy
Para publicar sua aplicação na Cloudflare Pages, siga estas etapas:

Conecte o repositório GitHub:
- Acesse a seção Pages no painel da Cloudflare.
- Escolha "Conectar ao GitHub" e selecione o repositório deste projeto.

Configure o build:
- Diretório de saída
```bash
.svelte-kit/cloudflare
```
- Comando de build
```bash
npm run build
```
- Ou escolha a predefinição de SvelteKit (opcional):
Na seleção de tecnologias, escolha a predefinição SvelteKit para configurar automaticamente as opções de build.


