---
layout: post
title: Clonei o Falecido Google Podcasts
lang: pt
image: podcasts-graveyard.webp
lang-ref: gpodcasts_clone
---

##### **TL;DR**

- \- Bastidores da criação de um app tocador de podcasts inspirado no Google
  podcasts.
- \- Resultados obtidos 3 meses após o lançamento alpha.

<br />
Quem nunca ficou frustrado em utilizar um serviço descontinuado que atire a primeira pedra. Essa foi a desculpa que eu precisava para criar um app que minimamente chegasse perto da experiência que o Google Podcast oferecia. Mesmo que criar mais um app tocador de podcasts em pleno 2024 com tantas opções disponíveis pareça uma péssima ideia.

<br />
Apps minimalistas me atraem, acho que foi por isso que o fim do app me incomodou tanto, não gosto de experiencias truncadas, ficar travado entre muitas funcionalidades e escolhas. Diante disso a ideia era clara, trazer a aparente simplicidade do falecido app e adicionar um tempero extra de minimalismo, buscando o público que quer ouvir o que gosta com apenas um clique, sem precisar ter que passar por uma dezena de escolhas até chegar a seu conteúdo favorito. Estou falando de spotify, youtube, netflix e tantos outros que agregam tantos serviços para te manter preso, que as vezes sem perceber, estamos lá há minutos/horas somente folhando o cardápio de opções.

<br />
Para meter a mão na massa fui pelo caminho que fazia mais sentido com as stacks que conheço, utilizei Flutter no desenvolvimento dos aplicativos Android e iOS. Para o backend escolhi desenvolver as funcionalidades utilizando o Supabase, uma alternativa ao firebase que oferece vários serviços de backend como plataforma. Isso me fez ter uma velocidade grande na criação das telas e cruds necessários.

<br />
Um desafio no meio dessa jornada era de onde puxar a base de podcasts, vou tentar explicar de forma simples como isso funciona: para se ter um programa de podcast público na internet, basta você fazer o upload de um arquivo de áudio com o programa e adicionar os meta dados desse programa num arquivo xml, isso é suficiente para que algum serviço indexador de podcasts encontre seu programa e passe a exibi-lo em apps públicos de podcasts. Há exceções a este fluxo, como no caso de spotify e youtube, porém a origem dos podcasts são no formato que mencionei, e isso permite que podcasts não se tornem um monopólio como youtube e apps similares criaram com o segmento de vídeos.

<br />
Por isso, não posso deixar de agradecer ao time por trás do Podcast Index. Esse projeto independente é dedicado a proteger e preservar o ecossistema de podcasts, garantindo que criadores de conteúdo tenham um espaço livre e acessível para compartilhar suas vozes. Graças a eles, consegui acessar uma base de dados robusta, com milhões de podcasts, o que foi essencial para o lançamento do app. Sem eles, criar um indexador de podcasts do zero com o tempo que eu tinha disponível, teria sido praticamente impossível, e o app certamente não teria alcançado a mesma qualidade e abrangência.

<br />
Foi assim que consegui transformar a frustração de perder um serviço amado em uma oportunidade. O <a href="https://minimalpodcast.app">Minimal Podcast</a> não é apenas um clone do Google Podcasts; é uma resposta ao inconformismo de ver produtos legais desaparecerem.

<br />
Claro que comparar um app desenvolvido em um mês por uma só pessoa contra um app que teve bilhões de usuários e foi mantido por uma das maiores empresas de tecnologia do planeta seria uma tremenda arrogância de minha parte, por isso deixo claro que o mesmo teve apenas sua aparência usada como inspiração e ainda faltam muitas melhorias no motor de recomendações, e outras funcionalidades… mas aos poucos vamos chegando lá.

<br />
Em um mês de lançamento, o Minimal atingiu 2 mil downloads nas lojas play store e app store, com pouquíssimo esforço em marketing, o que é uma baita dificuldade para mim, o que prova que não sou o único que sentiu falta de uma experiência de podcast minimalista e direta.

<br />
Mas isso é só o começo, vou compartilhar de tempos em tempos as dores e glorias que vou enfrentar ao continuar desenvolvendo o app, e já deixo um spoiler, criar e manter um canal de aquisição de usuários e rentabilizar estas pessoas para que as contas fechem é o meu próximo e gigante marco, aos poucos vamos chegando lá.
