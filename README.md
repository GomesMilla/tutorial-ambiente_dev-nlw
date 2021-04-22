sistema utilizado linux mint 20.1

Primeiramente, precisa baixar o node.js:

curl -fsSL https://deb.nodesource.com/setup_14.x | sudo -E bash -
sudo apt-get install -y nodejs

instale o cli do expo:
sudo npm install --global expo-cli

criar um novo projeto expo
expo init plantmanager

entrar na pasta do projeto:
cd plantmanager

iniciar o aplivativ
expo start
