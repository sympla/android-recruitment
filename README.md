# Recrutamento Android

[https://www.sympla.com.br/trabalhe-conosco](https://www.sympla.com.br/trabalhe-conosco#job-70855 "Descrição da vaga Android")

Parabéns! Você chegou até o nosso teste para desenvolvedores Android! Caso ainda não conheça a Sympla ou não saiba detalhes sobre a vaga, por favor entre no link a cima. Se está tudo ok e deseja continuar o teste, ficamos muito feliz por escolher a Sympla 🙂

Fazer parte da Sympla envolve ser parte essencial da nossa cultura e do nosso negócio. Quando pensamos em nosso time de desenvolvimento, fazer parte da Sympla também significa estar alinhado com nossas convicções sobre os alicerces de um bom processo de desenvolvimento. Nada melhor para mostrar do que um desenvolvedor é feito do que escrever código 🤘  

## Sobre o exercício

Esta etapa do processo consiste em criar um projeto de uma app que vai emular a nova home do app Android da Sympla. É apenas uma tela, mas é mais do que suficiente para nos introduzir a quem você é escrevendo código: seu estilo de organização de projeto, suas convenções de nomenclatura e de formatação, suas noções de arquitetura e, claro, seu grau de intimidade com os conceitos fundamentais do desenvolvimento Android.  

## Referência de design

Vamos usar como referência o design do nosso novo App.

![Referência de design](https://raw.githubusercontent.com/sympla/android-recruitment/master/device-2017-09-05-175822.png)  

## Endpoints

Vamos usar dados reais que resultam de chamadas à API da Sympla. Queremos conhecer seu código de networking mas não vamos acessar a API da Sympla diretamente (também por motivos de praticidade). Pensando nisso, estamos disponibilizando via AWS S3 dois JSONs contendo os dados que serão necessários para renderizar as duas listagens horizontais de eventos.  

**Front page**

[https://s3.amazonaws.com/sympla-ios-recruitment/endpoints/featured_events.json](https://s3.amazonaws.com/sympla-ios-recruitment/endpoints/featured_events.json)  

**Destaques**

[https://s3.amazonaws.com/sympla-ios-recruitment/endpoints/highlighted_events.json](https://s3.amazonaws.com/sympla-ios-recruitment/endpoints/highlighted_events.json)

## Recursos

O design é apenas uma referência, mas é desejável que se atinja o máximo de aderência possível à especificação. Por isso, também vamos disponibilizar as [imagens](https://github.com/sympla/android-recruitment/blob/master/images.zip?raw=true) e as [fontes](https://s3.amazonaws.com/sympla-ios-recruitment/fonts/fonts.zip) usadas na referência, já com os tamanhos para renderização correta nas diferentes densidades de tela.

## Requisitos

O app que esperamos ver ao final do processo consiste basicamente em duas listagens horizontais de eventos renderizadas de acordo com a referência, então acreditamos que o design e os endpoints são suficientes. O que a gente quer é justamente conhecer você como profissional e, acima de tudo, como programador. Por isso, não vamos estabelecer nenhum tipo de restrição sobre padrões de projeto, gerenciamento de dependências, construção de UI ou boas práticas. Queremos que você esteja à vontade para programar da maneira que mais gosta, e que você tenha autonomia para construir o projeto do seu jeito, com as suas regras e imprimindo o seu estilo.

Só temos um pedido: encare este projeto como algo que você encontraria em seu dia-a-dia profissional, ou como um projeto de estimação. Em outras palavras, queremos que você sinta prazer programando e que você se dedique ao projeto como se fosse seu. O resto é por sua conta 😬

## Submissão

- Criar um repositório privado com o nome `android-recruitment` em seu host de projetos favorito e entrar em contato através do e-mail [duanniston.cabral@sympla.com.br](mailto:duanniston.cabral@sympla.com.br) para prosseguirmos com o acesso ao código.

## Contato

Buscamos o máximo de clareza possível ao documentar o exercício, e esperamos que todas as dúvidas possam ser solucionadas com este `README`. Mas as dúvidas virão, e estamos prontos! Fique à vontade para entrar em contato conosco através do endereço [duanniston.cabral@sympla.com.br](mailto:duanniston.cabral@sympla.com.br) para tirar dúvidas e pedir ajuda. Pedimos apenas que as dúvidas sejam pertinentes ao exercício, para que possamos dar toda a atenção necessária a todos os candidatos.  
