# flutter_web_app_to_firebase_hosting
Deploy a Flutter Web App to Firebase Hosting

    ######## #### ########  ######## ########     ###     ######  ########
     ##        ##  ##     ## ##       ##     ##  ##   ##  ##       ##
     ######    ##  ########  ######   ########  #########  ######  ######
     ##        ##  ##    ##  ##       ##     ## ##     ##       ## ##
     ##       #### ##     ## ######## ########  ##     ##  ######  ########

Passo a passo para subir aplicação ### FIREBASE HOSTING ###

* necessario node instalado para rodar comando npm

* criar uma repositorio no git

0-) faça o git clone do repositorio criado
1-) npm install -g firebase-tools - comando para utilizar habiente virtual do FIREBASE
2-) firebase login - comando para indentificar qual conta do gmail vai tulizar para enviar o deploy ( se nao aparece a conta que deseja faz o comando firebase logout para sair e depois repitar novamente firebase login
3-) firebase init  - utilizar a opção de app ja criado selecione app criado no firebase   
4-) firebase deploy --only hosting - esse comando faz o deploy para O FIREBASE HOSTING e seu app ja fica disponivel em produção.
