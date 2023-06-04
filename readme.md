# Desafio de Desenvolvimento Fullstack Pleno - Aplicativo de Gravação de Vídeo "Blind Interview"

## Objetivo:

O objetivo deste desafio é criar um aplicativo Vue.js com Typescript que permita aos usuários gravar um vídeo de entrevista. A interface deve mostrar apenas um temporizador, mas não o feed de vídeo, para simular nosso conceito de "blind interview". Além disso, a aplicação deve alterar a voz do usuário em tempo real durante a gravação para evitar a identificação baseada na voz. O vídeo gravado deve ser carregado automaticamente para um backend PHP quando a gravação for concluída.

## Requisitos:

### Frontend (Vue.js + TypeScript):

1. **Gravação de vídeo:** O aplicativo deve permitir aos usuários gravar um vídeo diretamente do navegador. Você pode usar qualquer biblioteca ou API de sua escolha para isso, mas a interface deve incluir um botão para iniciar/parar a gravação e um temporizador mostrando a duração da gravação.

2. **Modificação de voz:** Durante a gravação, o aplicativo deve modificar a voz do usuário em tempo real para mascarar a identidade do usuário. Novamente, você pode usar qualquer biblioteca ou API de sua escolha para isso.

3. **Upload de vídeo:** Quando a gravação terminar, o aplicativo deve enviar automaticamente o vídeo para um servidor backend PHP. Você pode assumir que o servidor já possui uma API RESTful para aceitar uploads de vídeos.

### Backend (PHP):

1. **API de upload de vídeo:** O servidor deve aceitar uploads de vídeos, armazenar os vídeos em algum lugar (por exemplo, no disco local ou em um serviço como o AWS S3) e armazenar metadados sobre o vídeo (por exemplo, duração, data de upload, candidato ID) em um banco de dados MySQL.

## Recomendações:

- Crie uma boa experiência de usuário. Embora o feed de vídeo não seja mostrado para o usuário durante a gravação, ainda é importante fornecer feedback visual suficiente (por exemplo, mudanças de estado do botão de gravação, contagem regressiva do temporizador) para que o usuário saiba o que está acontecendo.

- Trate a modificação da voz como um "extra". Embora seja um requisito, estamos principalmente interessados em suas habilidades de desenvolvimento Vue.js/PHP. Se a modificação da voz for muito desafiadora, você ainda poderá passar no desafio sem ela.

- Priorize a qualidade do código sobre a quantidade de recursos. Estamos mais interessados em como você estrutura e organiza seu código do que em quantos recursos você pode adicionar ao aplicativo.

## Avaliação:

Você será avaliado pela qualidade do código, estrutura do projeto, uso de boas práticas de programação, uso do controle de versão (Git), design da API RESTful e capacidade de resolver problemas. A modificação da voz será considerada um "bônus", mas é uma boa oportunidade para demonstrar suas habilidades e criatividade.