# Desafio 01 - Docker

> Agora que você sabe os conceitos básicos de containers, o que é o Docker e como utilizar o Docker pra criarimagens e containers, chegou a hora de botar na pŕatica o que você aprendeu. Então eu preparei uma série de questões pra você assimilar o entendimento e alguns desafios práticos pra você por em prática.

>  Qual o seu nome ?
>> Danilo O. Pinheiro

> Qual o seu email ? (Coloca o mesmo email do cadastro na Iniciativa Kubernetes, ele vai ser usado como base para o certificado).
>> danilopinheiro88@icloud.com

> Hoje uso de containers tem sido adotado cada vez mais. Mas muitos profissionais não conseguem ver o ganho no seu uso. Então vamos imaginar que você está em uma equipe onde todos estão familiarizados e utilizam máquinas virtuais no seu dia a dia, mas existe o desejo de adotar DevOps e utilizar arquitetura de microsserviços. A sua função é esclarecer as dúvidas da galera em relação ao uso de containers e ajudar na adoção.Como a equipe não faz a menor ideia do que são containers, então a sua primeira função é dar clareza pra equipe em relação as vantagens do uso de containers. Escreve aqui porque a sua equipe deve adotar containers e os benefícios no uso da tecnologia.
>> Porque não temos riscos com algum planejamento inesperado, como antigamente... dizendo que só na minha maquina funciona...

> Depois que você apontou os benefícios do uso de containers, a galera se animou. Mas alguns questionaram porque usar containers se eles já podem fazer tudo que você falou usando máquinas virtuais. Então agora, você deve escrever porque máquinas virtuais e containers são diferentes e quais são as vantagens da containerização. *
>> Brevemente falando, a virtualização de máquina consiste em empacotar determinada aplicação em um modelo padrão com seu próprio ambiente operacional. O container também faz empacotamento, mas, no caso, ele não virtualizará o ambiente todo da máquina.

> Show de bola !!! A galera ficou MUITO animada, mas querem ver algo mais prático. Então agora, você deve pegar o projeto de conversão de temperatura no GitHub e fazer todo o processo pra executar em containers Docker.Segue o link do projeto no GitHub: https://github.com/KubeDev/conversao-temperatura Faça um fork do repositório, monte o processo de execução no Docker e compartilha aqui o seu repositório. *
>> 

>Boa! A equipe comprou a ideia e todos estão usando o projeto de conversão de temperatura como base. Mas você percebeu que algumas imagens estão fora de padrão e não estão seguindo boas práticas. Então chegou a hora de enumerar as boas práticas que todos devem seguir pra construir as imagens. *
>>

> Agora surgiu um novo desafio... Foi definido que agora será inserido projetos em .NET Core na sua equipe. Então você precisa criar um projeto base como referencia pra uso pela equipe.Como o .NET Core é uma tecnologia que é baseada em JIT, a construção da imagem utiliza o Multistage Build. Então agora você deve usar o projeto de conversão de peso, que está no GitHub do KubeDev e executar ele em container pra sua equipe entender por onde começar.Segue o link do projeto no GitHub: https://github.com/KubeDev/conversao-peso Faça um fork do repositório, monte o processo de execução no Docker e compartilha aqui o seu repositório. Essa documentação vai te ajudar https://docs.microsoft.com/en-us/aspnet/core/host-and-deploy/docker/building-net-docker-images?view=aspnetcore-5.0 * 
>> 
