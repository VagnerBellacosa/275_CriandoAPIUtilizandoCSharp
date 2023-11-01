# 275_CriandoAPIUtilizandoCSharp
Criando uma API Utilizando C#



[*
*](https://web.dio.me/lab/criando-uma-api-utilizando-c/learning/2be70a52-0f3e-4611-b128-b2ec2fa8d755)[**](https://web.dio.me/lab/criando-uma-api-utilizando-c/learning/3c66966c-164c-4768-b270-6725c8b70ab4)



- CONTEÚDOS
- INFORMAÇÕES

###### DESCRIÇÃO

Neste projeto prático vai te ensinar como criar uma API robusta com C# e .NET, abrangendo desde a configuração do ambiente de desenvolvimento até a implantação, incluindo autenticação, documentação e otimização, proporcionando habilidades essenciais em desenvolvimento de APIs. O objetivo desse projeto é capacitar os participantes a desenvolver APIs funcionais e escaláveis usando C# e .NET, abordando todas as etapas do processo de desenvolvimento.

**C#****.NET****API Rest**

------

###### Back-End

###### Intermediário

------

###### ESPECIALISTA

![author](https://hermes.dio.me/users/author/photos/7c6aae89-ee27-412e-a0d4-d2802c7ac12f.png)

###### Danilo Aparecido

Fundador, Didox Business & Technology[**](https://www.linkedin.com/in/danilo-aparecido-dos-santos-03101034/)



https://web.dio.me/lab/criando-uma-api-utilizando-c/learning/2be70a52-0f3e-4611-b128-b2ec2fa8d755





[**](https://web.dio.me/play)

##### Criando uma API Utilizando C#

**

[**](https://web.dio.me/lab/criando-uma-api-utilizando-c/learning/2be70a52-0f3e-4611-b128-b2ec2fa8d755)[**](https://web.dio.me/lab/criando-uma-api-utilizando-c/learning/27951f6c-ee2a-46b5-ac78-c9c3ba16631f)

<iframe id="ytc44" frameborder="0" allowfullscreen="1" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" title="Configurando ambiente" width="100%" height="100%" src="https://www.youtube.com/embed/ov6hOTCjF7M?controls=0&amp;disablekb=1&amp;enablejsapi=1&amp;fs=0&amp;iv_load_policy=3&amp;modestbranding=1&amp;showinfo=0&amp;rel=0&amp;html5=1&amp;cc_load_policy=0&amp;origin=https%3A%2F%2Fweb.dio.me&amp;widgetid=1" data-gtm-yt-inspected-16="true" style="box-sizing: inherit; max-width: none; float: none; margin: 0px; padding: 0px; border: 0px; font-style: inherit; font-variant: inherit; font-weight: inherit; font-stretch: inherit; line-height: inherit; font-family: inherit; font-optical-sizing: inherit; font-kerning: inherit; font-feature-settings: inherit; font-variation-settings: inherit; font-size: 14px; vertical-align: baseline;"></iframe>



00:24

 

21:39









normal

auto

- CONTEÚDOS
- INFORMAÇÕES

[Introdução](https://web.dio.me/lab/criando-uma-api-utilizando-c/learning/2be70a52-0f3e-4611-b128-b2ec2fa8d755)[Configurando ambiente](https://web.dio.me/lab/criando-uma-api-utilizando-c/learning/3c66966c-164c-4768-b270-6725c8b70ab4)[Entendendo estrutura do projeto](https://web.dio.me/lab/criando-uma-api-utilizando-c/learning/27951f6c-ee2a-46b5-ac78-c9c3ba16631f)[Organizando projeto e criando Rota Home](https://web.dio.me/lab/criando-uma-api-utilizando-c/learning/56bc0bb2-be8f-4ba8-b88c-2c1c77e0a49a)[Configurando MySql](https://web.dio.me/lab/criando-uma-api-utilizando-c/learning/6d8dd9d8-c457-411a-8efb-1cd8bfe10e4c)[Configurando Entity Framework](https://web.dio.me/lab/criando-uma-api-utilizando-c/learning/8239af49-7b73-4b07-9d7e-2edf81073779)[Criando Controlador de Tarefas](https://web.dio.me/lab/criando-uma-api-utilizando-c/learning/eaed0470-8acc-4fee-b220-371134930553)[Criando uma tarefa](https://web.dio.me/lab/criando-uma-api-utilizando-c/learning/e583f324-2c31-4bc9-90e2-d5e6fc22dfb0)[Atualizando uma tarefa](https://web.dio.me/lab/criando-uma-api-utilizando-c/learning/fb7b74a5-b22c-4177-b7f2-e16c31046ea1)[Mostrando uma única tarefa e excluindo tarefa](https://web.dio.me/lab/criando-uma-api-utilizando-c/learning/583203fe-3990-44f7-b936-29b7e76ca952)[Refatorando código utilizando DTO](https://web.dio.me/lab/criando-uma-api-utilizando-c/learning/8aa1239d-0438-40d1-903d-78521f849b5a)[Criando Serviço de tarefas](https://web.dio.me/lab/criando-uma-api-utilizando-c/learning/209acc14-662b-46fc-911b-2dc05295a1cf)[Utilizando interface no serviço de tarefas - Paginação - Conclusão](https://web.dio.me/lab/criando-uma-api-utilizando-c/learning/9f17b5dc-f1d3-4fcd-b276-3aef3cca7615)[Entendendo o Desafio](https://web.dio.me/lab/criando-uma-api-utilizando-c/learning/ac19d19a-6c90-4a5c-9a9f-b95c8c1d00fd)



[**](https://web.dio.me/play)

##### Criando uma API Utilizando C#

**

[**](https://web.dio.me/lab/criando-uma-api-utilizando-c/learning/9f17b5dc-f1d3-4fcd-b276-3aef3cca7615)[**](https://web.dio.me/lab/criando-uma-api-utilizando-c/learning/undefined)

# Entendendo o Desafio

 

**Agora é a sua hora de brilhar e construir um perfil de destaque na DIO! Explore todos os conceitos explorados até aqui e replique (ou melhore, porque não?) este projeto prático. Para isso, crie seu próprio repositório e aumente ainda mais seu portfólio de projetos no GitHub, o qual pode fazer toda diferença em suas entrevistas técnicas** 😎

 

**Neste repositório, insira todos os links e arquivos necessários para seu projeto, seja um arquivo de banco de dados ou um link para o template no Figma.**

 

*Dica: Se o expert forneceu um repositório Github, você pode dar um "fork" no repositório dele para organizar suas alterações e evoluções mantendo uma referência direta ao código-fonte original.*

 

### **Repositório Git**

 

O Git é um conceito essencial no mercado de trabalho atualmente, por isso sempre reforçamos sua importância em nossa metodologia educacional. Por isso, todo código-fonte desenvolvido durante este conteúdo foi versionado no seguinte endereço para que você possa consultá-lo a qualquer momento:

 

https://github.com/digitalinnovationone/api-tarefas-csharp

 

 

Bons estudos 😉



