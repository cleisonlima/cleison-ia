# Cleison IA

Assistente inteligente para produtividade, automação e interação multimodal no computador.

<p align="center">
  <img 
    src="./Captura%20de%20tela%202026-08-23%20175645.png" 
    alt="Captura de tela da aplicação Cleison IA"
    width="900"
  />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Node.js-20-339933?style=for-the-badge&logo=nodedotjs" alt="Node.js" />
  <img src="https://img.shields.io/badge/Vite-5-646CFF?style=for-the-badge&logo=vite" alt="Vite" />
</p>

## Visão geral

O **Cleison IA** é um assistente inteligente desenvolvido para aumentar a produtividade, automatizar tarefas e permitir uma interação multimodal com o computador.

```


A Cleison IA e uma aplicacao de assistente pessoal com foco em produtividade, automacao e percepcao visual. Ela combina inteligencia artificial, comandos por voz, analise de camera e acoes automaticas no ambiente do usuario.

O objetivo do projeto e criar uma experiencia onde o usuario possa interagir com o sistema por texto ou voz e receber apoio em tarefas do dia a dia, como:

- responder perguntas e executar instrucoes em linguagem natural;
- controlar acoes por voz;
- analisar imagens da camera e da tela;
- automatizar cliques, digitacao e abertura de aplicacoes;
- manter historico e memoria contextual das interacoes.

## Proposito da aplicacao

A Cleison IA foi desenvolvida para funcionar como um copiloto digital local, unindo:

- conversa inteligente;
- automacao de tarefas no computador;
- visao computacional;
- interacao multimodal com voz, texto e imagem.

Ela foi pensada para facilitar uso cotidiano, reduzindo esforco manual e tornando a interacao com o computador mais natural e inteligente.

## Tecnologias utilizadas

- React + TypeScript + Vite para a interface
- Express + Node.js para o backend local
- Gemini API para inteligencia conversacional e processamento de instrucoes
- Web Speech API para reconhecimento e sintese de voz
- MediaDevices / getUserMedia para microfone e camera
- APIs de captura de tela para monitoramento visual
- RobotJS para automacao de mouse e teclado
- Arquitetura local com memoria, historico e contexto de uso

## Funcionalidades principais

- Assistente conversacional em interface web
- Comandos por voz e respostas em audio
- Captura de camera e analise visual
- Captura de tela e monitoramento do desktop
- Automacao de acoes no sistema
- Historico e memoria contextual
- Experiencia local com integracao de IA

## Requisitos

- Node.js instalado
- Chave da Gemini configurada no arquivo .env.local
- Permissoes do navegador para microfone e camera

## Como rodar localmente

1. Instale as dependencias:
   npm install

2. Configure a variavel de ambiente no arquivo .env.local:
   GEMINI_API_KEY=sua_chave_aqui

3. Inicie a aplicacao:
   npm run dev

4. Abra a URL exibida no terminal, normalmente:
   http://localhost:3000

## Observacoes

A aplicacao depende de permissoes do navegador para microfone e camera e de uma chave valida da API Gemini para fornecer respostas inteligentes em nuvem. Caso a API esteja indisponivel ou sem quota, o sistema pode continuar funcionando em um modo local de fallback.

## Licenca

Este projeto tem finalidade de estudo, desenvolvimento e uso pessoal em solucoes de IA e automacao.
