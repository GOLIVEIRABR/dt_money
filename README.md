## Pré-requisitos

* Node v.18 LTS 
* npm v.9 ou superior
* docker 23.0 ou superior

## Passo a Passo
### Instalação do Ambiente de Desenvolvimento (Pré-requisitos)
Se o ambiente de desenvolvimento com o NPM já estiver instalado, prosseguir para o próximo subtópico (Instalação e Configuração do Projeto), caso contrário, siga os passos abaixo para instalar o NodeJS:
* Instalação do NVM:

O NVM permite instalar várias versões diferentes do NodeJS alternando entre elas, para instalar o nvm, basta seguir as instruções do repositório oficial:
https://github.com/nvm-sh/nvm#installing-and-updating
* Instalação da versão LTS do node:

Com o NVM instalado, basta prosseguir com a instalação LTS do node:
```bash
$ nvm install --lts
```
* Setar a instalação lts como default para execução de aplicações node:

```bash
$ nvm use --lts
```

### Instalação e Configuração do Projeto
* Clonar ou baixar a pasta do projeto.
* Entrar na raiz do projeto pelo terminal e executar os seguintes passos (um a um):
* Instalar todas as dependencias necessárias para o projeto:
```bash
$ npm install
```
* Iniciar a execução do projeto em modo de desenvolvimento com hot reload (o serviço é reiniciado sempre que o código é salvo):
```bash
$ npm run dev
```

