# Desafio de Desenvolvimento Fullstack Pleno - Aplicativo de Gravação de Vídeo

## Objetivo:
O objetivo deste desafio é criar um aplicativo Vue.js com Typescript que permita aos usuários gravar um vídeo de entrevista. A interface deve mostrar um temporizador de um minuto para resposta de cada pergunta. O vídeo gravado deve ser carregado automaticamente para um backend PHP quando a gravação for concluída.

## Requisitos:
### Frontend (Vue.js + TypeScript):
- **Gravação de vídeo:** O aplicativo deve permitir aos usuários gravar um vídeo diretamente do navegador. Você pode usar qualquer biblioteca ou API de sua escolha para isso, mas a interface deve incluir um botão para iniciar/parar a gravação e um temporizador regressivo de um minuto.

- **Upload de vídeo:** Quando a gravação terminar, o aplicativo deve enviar automaticamente o vídeo para um servidor backend PHP. Você pode assumir que o servidor já possui uma API RESTful para aceitar uploads de vídeos.

### Backend (PHP):
- **API de upload de vídeo:** O servidor deve aceitar uploads de vídeos, armazenar os vídeos em algum lugar (por exemplo, no disco local ou em um serviço como o AWS S3) e armazenar metadados sobre o vídeo (por exemplo, duração, data de upload, candidato ID) em um banco de dados MySQL.

## Recomendações:
- Crie uma boa experiência de usuário. É importante fornecer feedback visual suficiente (por exemplo, mudanças de estado do botão de gravação, contagem regressiva do temporizador) para que o usuário saiba o que está acontecendo.

- Priorize a qualidade do código sobre a quantidade de recursos. Estamos mais interessados em como você estrutura e organiza seu código do que em quantos recursos você pode adicionar ao aplicativo.

## Avaliação:
Você será avaliado pela qualidade do código, estrutura do projeto, uso de boas práticas de programação, uso do controle de versão (Git), design da API RESTful e capacidade de resolver problemas.

**Bônus:** Fazer o upload direto para um bucket na nuvem no frontend e enviando só os dados do vídeo para o backend salvar no banco

Boa sorte!
