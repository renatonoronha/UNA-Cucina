# UNA-Cucina


![image](https://github.com/renatonoronha/UNA-Cucina/assets/132279548/433dacba-0ca8-49a7-9c87-6b84b468eb14)


***

Wireframe:

![image](https://github.com/renatonoronha/UNA-Cucina/assets/132279548/95c6b9d4-0925-4011-b9f9-ba3426bb3957)

***

PT: 

Proprietários do projeto:
-Guilherme Barbosa
-Luana Aguilar
-Luiz Davi
-Paola Nobre
-Renato Noronha
-Stefany Xavier

Nosso projeto pretende fazer um software de culinária contendo receitas diversas e muito interessantes. Escolhemos este tema porque é algo que as pessoas usam todos os dias, fácil para um primeiro projeto e que todo mundo gosta de comer. Além disso, sabe quando você tem vontade de comer algo diferente? UNA CUCINA tem como objetivo ajudá-lo a descobrir o que você gostaria e aproveitar para lhe mostrar receitas maravilhosas que talvez você não conheça.

O projeto contará com sistema de filtragem de receitas, que serão: receitas frios; receitas quentes; receitas vegano; doce; salgado; poucos ingredientes; lanches; saudável; drinks; pessoas experientes na cozinha e novatos na cozinha. O site terá sistema de cadastro e quem quiser postar uma receita terá que adquirir um selo de verificação para utilizar este recurso, mesmo assim as receitas enviadas passarão por uma análise de até 5 (cinco) dias úteis para garantir a seriedade do site. Os usuários poderão favoritar receitas, comentar pública ou privadamente. O site obterá receitas financeiras por meio de anúncios que serão exibidos misturados no site. O tempo de resposta do site será de até 3 segundos. A primeira página do site mostrará as receitas mais visualizadas e destacadas. Por fim, o site terá uma opção que será possível alterar o idioma do português para o inglês.

***

**Requisitos funcionais**

● Salvar receitas: O usuário pode salvar as receitas para achar com mais facilidade as próximas vezes que acessarem o site. 

● Barra de pesquisa: para ter mais facilidade quando for procurar uma recita especifica 

● Filtros: especificando os estilos de comida, algumas exemplos são: quente, fria, veganas, doces, salgadas, com poucos ingredientes. 

● Baixar a receita em pdf  

● Sistema de cadastro: onde o usuário poderá optar por compartilhar novas receitas ou só usar para ver receitas 

● A primeira página irá exibir receitas em destaques/ mais vistas/ populares  

● A página também vai ter troca de linguagem para que seja acessível para usuário que não falam português

***

**Requisito não funcionais**

● Sistema de revisão de receitas: as receitas que os usuários compartilharem serão passadas por revisão para serem ou não aprovadas para serem expostas no site. Que será em até 5 dias uteis. 

● Tempo de resposta do site: em até 3 segundos  


***


EN: 

Owners of the project:
-Guilherme Barbosa
-Luana Aguilar
-Luiz Davi
-Paola Nobre
-Renato Noronha
-Stefany Xavier

Our project plan to make a cooking software containing diverse and very interesting recipes. We chose this subject because it is something people use every day, easy for a first project and everyone likes to eat. Also, do you know when you feel like eating something different? UNA CUCINA aims to help you discover what you would like and take the opportunity to show you wonderful recipes that you may not know.

The project will have a recipe filtering system, which will be: cold recipes; hot recipes; vegan recipes; candy; salted; few ingredients; snacks; healthy; drinks; experienced in the kitchen and novices in the kitchen.
The site will have a registration system and people who want to post a recipe will have to acquire a verification stamp to use this resource, even with that the submitted recipes will undergo a review of up to 5 (five) working days to guarantee the seriousness of the site. Users will be able to favorite recipes, comment publicly or privately. The site will acquire financial income through advertisements that will be displayed mixed on the site. Website response time will be up to 3 seconds. The first page of the site will show the most viewed and highlighted recipes. Finally, the site will have an option that will be possible to change the language from Portuguese to English.

***

**Functional requirements**

● Save recipes: The user can save recipes to find them more easily the next time they access the website.

● Search bar: to make it easier when searching for a specific recipe

● Filters: specifying food styles, some examples are: hot, cold, vegan, sweet, savory, with few ingredients.

● Download the recipe in PDF

● Registration system: where the user can choose to share new recipes or just use it to view recipes

● The first page will display featured/most viewed/popular recipes

● The page will also have a language change so that it is accessible to users who do not speak Portuguese

***

**Non-functional requirements**

● Recipe review system: recipes that users share will be reviewed to be approved or not to be displayed on the website. Which will be within 5 business days.

● Website response time: within 3 seconds

 ---
 
Casos de Usos/Use Cases:
![image](https://github.com/renatonoronha/UNA-Cucina/assets/132279548/d27d002d-b5d5-4017-84a9-b94f741e89cb)

---

*Fluxos Principais e Alternativos*

Fluxo Principal: Registrar Usuários

1) O usuário preenche os campos de informações corretamente
2) O usuário clica em registrar
3) O banco de dados armazena as informações
4) O usuário é logado automaticamente no site


Fluxo Alternativo: Senha Inválida
1a) Se o usuário não cumprir os requisitos de senha informados, o campo será resetado e poderá ser inserida uma nova senha

Fluxo Alternativo: Campo de informações em branco
2a) O sistema deverá informar visualmente em vermelho os campos que não foram preenchidos para o usuário e mostrar uma mensagem informando a obrigatoriedade do preenchimento

Fluxo alternativo: Email já registrado/utilizado
3a) O sistema deverá pedir um novo email e exibir uma mensagem de email já registrado

Fluxo alternativo: Email inválido
4a) Se o email digitado for inválido (não seguir o padrão de formatação), o sistema deverá requirir um novo email e exibir uma mensagem de email inválido

Fluxo alternativo: Username já registrado
5a) Se o nome de usuário já estiver registrado, o sistema deverá mostrar uma mensagem informando e pedir um novo username


Fluxo Principal: Fazer login
1) O usuário preenche os campos de informações corretamente
2) O usuário decide se quer manter a conta logada e  em seguida clica em logar
3) O sistema busca as informações do usuário no banco de dados
4) O usuário é logado no site
Fluxo Alternativo: Senha Incorreta
1a) Se o usuário digitou a senha diferente da registrada no banco de dados, o sistema deverá mostrar uma mensagem de erro e deverá pedir para que digite novamente e mostrar uma opção de recuperar a senha.
Fluxo Alternativo: Email/username não registrado
2a) O usuário digitou um email/username que não está registrado no banco de dados, o sistema deverá mostrar uma mensagem de erro e deverá pedir a entrada de um email/username válido ou disponibilizar a opção para cadastrar o username, levando para a página de cadastro

Fluxo Alternativo: Campos de informações em branco
3a) Caso o usuário tenha preenchido as informações o sistema deverá exibir uma mensagem de erro indicando o não preenchimento dos campos e exigir credenciais corretas para fazer o login

Fluxo alternativo: Email inválido
4a) Se o email digitado for inválido (não seguir o padrão de formatação), o sistema deverá requirir um novo email e exibir uma mensagem de email inválido


Fluxo Principal: Pesquisar Receitas
1) O usuário realiza a pesquisa de uma receita pelo nome na barra de pesquisas ou pelos tópicos
2) O sistema mostra as receitas que se encaixam na pesquisa na ordem decrescente de popularidade 

Fluxo Alternativo: Nenhuma receita correspondente com a pesquisa
1a) Caso nenhuma receita se enquadre na pesquisa realizada pelo usuário, informar uma mensagem de erro informando a situação

Fluxo Alternativo: O usuário acredita que uma receita não se enquadra em uma categoria
2a) Dentro da página da receita haverá um botão escrito “Acredita que há um erro de categoria?” em que o usuário será redirecionado para um formulário para explicar o porquê disso e que será revisado por um moderador para decidir se realmente há um erro e posteriormente retirar ou mudar de categoria
Fluxo Principal: Favoritar Receitas
1) O usuário faz login no site
2) O usuário entra na página da receita que deseja favoritar
3) O usuário clica na estrela para favoritar e a estrela preenche a cor por completo indicando que favoritou
4) O sistema salva a página da receita no perfil do usuário em uma aba "favoritos"

Fluxo Alternativo: O usuário tentar favoritar uma receita sem estar logado
1a) Deverá aparecer uma mensagem de erro informando que é preciso estar logado no site para realizar a ação e disponibilizar uma opção para fazer o login

Fluxo Principal: Baixar Receitas
1) O usuário faz login no site
2) O usuário entra na página da receita que deseja baixar
3) O usuário clica no botão de download em baixo de favoritar e a receita é salva no seu computador em forma de pdf
4) Uma mensagem de confirmação do download aparece

Fluxo alternativo: o usuário tenta baixar uma receita sem estar logado 
1a)  Se o usuário tentar baixar uma receita sem estar logado deverá aparecer uma mensagem de erro informando que é preciso estar logado no site para realizar a ação e disponibilizar uma opção para fazer o login
Fluxo alternativo: o usuário tenta baixar uma receita e não tem armazenamento suficiente 
2a) Se o usuário tentar baixar uma receita e não tiver espaço para armazenamento deverá aparecer uma mensagem de erro informando que o mesmo não possui armazenamento suficiente



Fluxo Principal: Trocar Idioma
1) O usuário clica no botão de trocar idioma e seleciona o idioma que deseja colocar no site
2) O sistema troca o idioma pro idioma de destino

Fluxo alternativo: o usuário não encontra o idioma desejado 
1a) O usuário só conseguirá trocar o idioma do site para três idiomas, se o idioma não for o que ele precisa aparecerá uma mensagem de idioma não encontrado

Fluxo Principal: Verificar Conta
1) O revisador faz login no site
2) Na aba de conta, ele clica na opção "Sou Revisador (ou Administrador)" e será redirecionado para uma página em que ele colocará o código de administração dele
3) Aparecerá o painel de administração pra ele 
4) Na aba de "contas", aparecerá usuários candidatos para terem as contas verificadas e desbloquearam mais funcionalidades
5) O revisador decidirá quais usuários são aptos para ganharem o selo de verificação de acordo com suas atividades no site
6) Se aprovado, chegará uma mensagem no email do usuário, e um aviso dentro do site, informando a situação e o selo será concedido. Se negado chegará uma mensagem no email e um aviso dentro do site lamentando e desejando mais sorte em tentativas futuras. Deverá ter um intervalo de 1 mês para poder solicitar o selo novamente.

Fluxo Alternativo: Senha Incorreta
1a) Se o revisador digitou a senha diferente da registrada no banco de dados, o sistema deverá mostrar uma mensagem de erro e deverá pedir para que digite novamente e mostrar uma opção de recuperar a senha.


Fluxo Principal: Subir Receitas
1) O usuário deverá estar logado no site
2) O usuário deve ter um selo de verificação 
3) Na aba de conta, terá a opção de "Subir receitas" em que ele preencherá todas as informações sobre a receita e terá a opção de colocar uma imagem junto e enviará
4) Aparecerá uma mensagem informando que o enivo foi realizado e terá um tempo para a análise da receita por um revisador
5) Se aprovado, chegará uma mensagem no email do usuário, e um aviso dentro do site, informando a situação e a receita será postada no site com o username. Se negado chegará uma mensagem no email e um aviso dentro do site informando os motivos pelo qual foi negado.
6) Na aba de conta, terá um botão de "posts", que levará para todas as postagens realizadas pelo usuário

Fluxo Alternativo: Senha Incorreta
1a) Se o usuário digitou a senha diferente da registrada no banco de dados, o sistema deverá mostrar uma mensagem de erro e deverá pedir para que digite novamente e mostrar uma opção de recuperar a senha.

Fluxo alternativo: O usuário não possui selo de verificação 
2a) Se o usuário quiser subir uma receita ele precisa fazer uma solicitação do selo de verificação se o selo for negado pelo revisador ele não conseguirá subir receitas
Fluxo alternativo: A receita não foi aceita 
3a) Após enviar a receita ela passa por uma revisão se o arquivo enviado não for uma receita o arquivo será negado e o sistema deverá mandar um email para o usuário informando que o arquivo não foi aceito  

Fluxo Principal: Revisar Receitas
1) O revisador faz login no site
2) Na aba de conta, ele clica na opção "Sou Revisador (ou Administrador)" e será redirecionado para uma página em que ele colocará o código de administração dele
3) Aparecerá o painel de administração pra ele 
4) Na aba de "receitas", aparecerá as receitas enviadas por usuários para serem postadas no site 
5) O revisador decidirá quais receitas são aptos para serem postadas no site de acordo com o conteúdo
6) Se aprovado, chegará uma mensagem no email do usuário, e um aviso dentro do site. Se negado chegará uma mensagem no email e um aviso dentro do site informando os motivos pelo qual foi negado.

Fluxo Alternativo: Senha Incorreta
1a) Se o revisador digitou a senha diferente da registrada no banco de dados, o sistema deverá mostrar uma mensagem de erro e deverá pedir para que digite novamente e mostrar uma opção de recuperar a senha.

Fluxo alternativo: Um arquivo não é receita
2a) Se o revisador receber um arquivo que não é uma receita ele deverá reprovar o arquivo e mandar um email para o usuário com o motivo do arquivo ter sido reprovado 


Missão do Produto:

O site UNA Cucina visa oferecer opções de receitas simples e rápidas de serem feitas para usuários que buscam por simplicidade na hora de cozinhar

---

**Lista de funções**

![image](https://github.com/renatonoronha/UNA-Cucina/assets/132279548/b582858c-cbc9-4ddd-af0e-f4b35abf4aad)


---

**Requisitos de qualidade**


1- Desempenho:
O tempo de resposta do site deve ser de até 3 segundos para proporcionar uma experiência agradável ao usuário.

2- Segurança:
O sistema de cadastro e a revisão de receitas devem ser seguros para proteger as informações do usuário e garantir a integridade das receitas.

3- Disponibilidade:
O sistema do site deve ser estável e confiável, priorizando a minimização do tempo de indisponibilidade devido a manutenções programadas e não programadas. De forma que o site esteja sempre à disposição do cliente pelo maior tempo possível.

4- Internacionalização:
A opção de alterar o idioma de forma que atenda o cliente, independentemente de seu idioma, deve ser implementada de maneira eficaz, permitindo que usuários de diferentes países acessem o site.

5- Eficiência:
O sistema deve ser eficiente em termos de recursos, garantindo que os anúncios sejam exibidos de forma não intrusiva e que o desempenho geral do sistema não seja prejudicado.

6- Escalabilidade:
O sistema deve ser escalável para lidar com um aumento no número de receitas, usuários e tráfego, se necessário.

7- Usabilidade:
A interface do usuário deve ser intuitiva e fácil de usar, garantindo uma boa experiência do usuário ao navegar e interagir com as receitas.

8- Salvamento e Download:
Os usuários podem publicar e também baixar as receitas em formato PDF, aumentando a conveniência e usabilidade do site.

9- Filtros:
Filtros de pesquisa para categorizar receitas com base em estilos de comida, como quente, fria, veganas, doces, salgadas e ingredientes, facilitando a descoberta de receitas específicas.

---

*Diagrama de classes*

![image](https://github.com/renatonoronha/UNA-Cucina/assets/132279548/6e20e466-5c12-4978-835f-395d015ac41d)

---

*Banco de Dados*

![image](https://github.com/renatonoronha/UNA-Cucina/assets/132279548/83b0e313-fa9d-40ac-ab54-7df56949f6a2)

