# Automação de Testes Android com Appium – My Demo App

Este repositório contém um projeto de automação de testes utilizando Appium para o aplicativo Android My Demo App, um app fictício de e-commerce desenvolvido pela Sauce Labs.

## Estrutura do Projeto

•	app/: Contém o aplicativo Android a ser testado.

•	test/: Inclui os scripts de teste automatizados.

•	wdio.conf.js: Arquivo de configuração do WebdriverIO para execução dos testes.

## Pré-requisitos

Antes de executar os testes, certifique-se de ter as seguintes ferramentas instaladas:

•	Node.js: Plataforma JavaScript necessária para executar o Appium e o WebdriverIO.

•	Java Development Kit (JDK): Necessário para o Android SDK.

•	Android Studio: Inclui o Android SDK e ferramentas para emular dispositivos Android.

•	Appium: Ferramenta para automação de aplicativos móveis.

## Configuração do Ambiente
1.	Instale o Node.js:

•	Baixe e instale a versão mais recente do Node.js a partir do site oficial.

2.	Instale o JDK:

•	Baixe e instale o JDK 8 ou superior.

•	Configure a variável de ambiente JAVA_HOME apontando para o diretório de instalação do JDK.

3.	Instale o Android Studio:
   
•	Baixe e instale o Android Studio a partir do site oficial.

•	Durante a instalação, certifique-se de incluir o Android SDK e o AVD Manager.

•	Configure a variável de ambiente ANDROID_HOME apontando para o diretório do SDK.

4.	Instale o Appium:

•	No terminal, execute:

```bash
npm install -g appium
npm install -g appium-doctor
```

•	Verifique a instalação com:

```bash
appium-doctor --android
```

5.	Instale as dependências do projeto:

•	No diretório raiz do projeto, execute:

```bash
npm install
```

## Executando os Testes

1.	Inicie o Appium Server:

•	No terminal, execute:

```bash
appium
```

2.	Inicie o emulador Android ou conecte um dispositivo físico:

•	Utilize o Android Studio ou o AVD Manager para iniciar um emulador.

•	Para dispositivos físicos, ative a depuração USB e conecte-o ao computador.

3.	Execute os testes:

•	No diretório raiz do projeto, execute:

```bash
npx wdio
```

Este projeto foi desenvolvido com base em práticas comuns de automação de testes para aplicativos Android.
