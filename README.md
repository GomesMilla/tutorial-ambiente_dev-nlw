SO utilizado durante o tutorial, linux mint 20.1

Primeiramente, é necessário ter o node.js instalado na máquina, caso não o tenha, abra o terminal e exacute os seguintes comandos:

```
curl -fsSL https://deb.nodesource.com/setup_14.x | sudo -E bash -
sudo apt-get install -y nodejs
```

Logo após, é necessário ter o expo cli instalado, caso não o tenha:

```
sudo npm install --global expo-cli
```

Para criar um novo projeto expo, é necessário rodar o seguinte comando:

```
expo init plantmanager
```

Entre na pasta do projeto com o seguinte comando:

```
cd plantmanager
```

Para rodar o projeto, rode o seguinte comando:

```
expo start
```
