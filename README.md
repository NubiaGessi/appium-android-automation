Automação de Testes Android com Appium – My Demo App

Este repositório contém um projeto de automação de testes para aplicativos Android utilizando Appium.

Estrutura do Projeto
•	app/: Contém o aplicativo Android a ser testado.
•	test/: Inclui os scripts de teste automatizados.
•	wdio.conf.js: Arquivo de configuração do WebdriverIO para execução dos testes.

Pré-requisitos
Antes de executar os testes, certifique-se de ter as seguintes ferramentas instaladas:
•	Node.js: Plataforma JavaScript necessária para executar o Appium e o WebdriverIO.
•	Java Development Kit (JDK): Necessário para o Android SDK.
•	Android Studio: Inclui o Android SDK e ferramentas para emular dispositivos Android.
•	Appium: Ferramenta para automação de aplicativos móveis.

Configuração do Ambiente
1.	Instale o Node.js:
o	Baixe e instale a versão mais recente do Node.js a partir do site oficial.
2.	Instale o JDK:
o	Baixe e instale o JDK 8 ou superior.
o	Configure a variável de ambiente JAVA_HOME apontando para o diretório de instalação do JDK.
3.	Instale o Android Studio:
o	Baixe e instale o Android Studio a partir do site oficial.
o	Durante a instalação, certifique-se de incluir o Android SDK e o AVD Manager.
o	Configure a variável de ambiente ANDROID_HOME apontando para o diretório do SDK.
4.	Instale o Appium:
o	No terminal, execute:
npm install -g appium
npm install -g appium-doctor
o	Verifique a instalação com:
appium-doctor --android
5.	Instale as dependências do projeto:
o	No diretório raiz do projeto, execute:
npm install

Executando os Testes
1.	Inicie o Appium Server:
o	No terminal, execute:
appium
2.	Inicie o emulador Android ou conecte um dispositivo físico:
o	Utilize o Android Studio ou o AVD Manager para iniciar um emulador.
o	Para dispositivos físicos, ative a depuração USB e conecte-o ao computador.
3.	Execute os testes:
o	No diretório raiz do projeto, execute:
npx wdio

Este projeto foi desenvolvido com base em práticas comuns de automação de testes para aplicativos Android.
