# Projeto de API Básica usando Node, Npm e Express.

## Iniciando o npm e criando o package.json

O que é NPM:

NPM (Node Package Manager) é só um pacote de gerenciamento de módulos de códigos JS para instalar junto ao NodeJs e poder usar nas suas

aplicações, ou até mesmo suas aplicações que precisam ser incluídas junto ao Node.

A grosso modo é um instalador cuidando das dependências evitando ter que mantê-las junto da sua aplicação e cuidar das atualizações.

O que nem sempre funciona como o esperado. Além disso é um repositório de módulos.

no terminal, para iniciar o Npm digite:

```
npm init -y
```

Package.json é um pacote de informações sobre a nossa aplicação, lá ficarão armazenadas diversas informações.

## Instalando o express

O que é o Express: 

Express é um framework oara web con um conjunto de recursos para aplicativos web e mobile.

Framework são um conjunto de bibliotecas e sua palavra chave é reusabilidade. Não reinvente a roda!

Em um site tradicional baseado em dados, um aplicativo da Web aguarda pedidos HTTP do navegador da Web (ou outro cliente). Quando um

pedido é recebido, o aplicativo descreve quais ações são necessárias com base no padrão de URL e possivelmente informações associadas

contidas em dados POST ou GET. Dependendo do que é necessário, pode ler ou escrever informações de um banco de dados ou executar outras

tarefas necessárias para satisfazer a solicitação. O aplicativo retornará uma resposta ao navegador da Web, criando, de forma dinâmica, 

uma página HTML para o navegador, exibindo inserindo os dados recuperados em espaços reservados em um modelo HTML.


Express fornece métodos para especificar qual função é chamada quando chega requisição HTTP (GET, POST, SET, etc.) e de rotas e métodos

para especificar o mecanismo de modelo ("view") usado, onde o modelo arquivos estão localizados e qual modelo usar para renderizar uma

resposta. Você pode usar o middleware Express para adicionar suporte para cookies, sessões e usuários, obtendo parâmetros POST / GET,

etc. Você pode usar qualquer mecanismo de banco de dados suportado por Node (o Express não define nenhum comportamento relacionado a 

banco de dados).

As seções a seguir explicam algumas das coisas comuns que você verá ao trabalhar com o código Express e Node.


