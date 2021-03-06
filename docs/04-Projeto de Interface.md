
# Projeto de Interface

<p align="justify"> Para o desenvolvimento do sistema em questão, foram projetadas telas buscando-se uma identidade visual intuitiva e padronizada entre as diferentes telas do sistema. Com a navegação entre as diferentes funcionalidades ocorrendo através dos itens do cabeçalho e do menu lateral, que se encontram presentes em todas as telas após o login do usuário. Também foi levado em consideração a responsividade do sistema para funcionamento tanto em desktop quanto em dispositivos móveis.</p>

## Diagrama de Fluxo

![Diagrama de Fluxo do Usuario ADS 2022_1_versao2](https://user-images.githubusercontent.com/74699119/161865551-187fd8c1-57fa-46f2-89b4-0887ca632947.png)
<p align="center"><b>Figura 4</b> - Diagrama de fluxo do usuário do projeto</p>
<br>

## Wireframe Interativo

<p align="justify"> Conforme o diagrama de fluxo do projeto apresentado no item anterior, as telas do sistema são apresentados em detalhes nos itens que se seguem. 
O wireframe interativo do projeto encontra-se disponível em: https://lucid.app/documents/embeddedchart/660ffadd-238f-49f7-9ed3-5b89b8208a25?invitationId=inv_d8efbf44-b38b-48bc-9c44-65305935decf#</p> 

A estrutura de interface será comum em todas as telas do sistema após a realização do login. A figura abaixo ilustra a divisão dos conteúdos nestas telas. Observamos que a estrutura está dividida em seções:
* Cabeçalho - Onde são dispostos os elementos fixos da navegação principal do site, cujo será apresentado em todas as telas para todos os usuários do sistema.
* Menu lateral - Apresenta os menus de navegação do sistema e é associado ao conteúdo da tela. A tabela de Menu será diferente e de acordo com o nível de acesso de cada usuário. 
* Conteúdo - Onde é apresentado o conteúdo das telas.
* Rodapé - Nesta tabela é apresentado as informações de contato e copyright.

![Estrutura de interface](https://user-images.githubusercontent.com/89323922/162098121-d093dcc0-0448-4161-bc2f-da9640ca54fb.png)

<p align="justify"> Para as telas de homepage, soluções e login, que são apresentadas quando não há nenhum usuário logado no sistema, uma estrutura similar, porém sem a presença do menu lateral à esquerda é utilizada.</p>

 ![Estrutura de interface (2)](https://user-images.githubusercontent.com/89323922/162333677-47a725a1-fb14-410f-aa98-f01dcf57b345.png)


 Listadas abaixo estão as telas individuais do wireframe com suas descrições:
 
 ### Tela - Homepage
 
 <p align="justify"> A tela de homepage apresenta uma breve explicação sobre o produto, com as informações básicas do que o sistema tem a oferecer. Através dessa página, é possivel que os usuários visualizem os contatos da instituição de ensino, como também possibilita o acesso das telas: Soluções e Login.</p>
 
![Homepage](https://user-images.githubusercontent.com/74699119/162334329-5fb9f5c3-4905-401a-957d-6eca9e8b04bb.png)

 ### Tela - Soluções
 
 <p align="justify"> A tela de Soluções apresenta através de imagens ilustrativas e textos explicativos, as funcionalidades do sistema. Está tela proporciona ao usuário o acesso à tela de Login e homepage, como também as informações de contato.</p>
 
![Solucoes](https://user-images.githubusercontent.com/74699119/168452622-178dd5e4-321f-4558-b5d5-a8a65bca94b2.png)

 ### Tela - Fale conosco
 
 ![faleconosco](https://user-images.githubusercontent.com/74699119/173220760-e80b03cb-38a1-4f69-8fee-b9318375bf1a.png)
 <p align="justify"> A tela de "Fale conosco" apresenta um formulário que o usuário poderá preencher para entrar fazer contato com a plataforma.</p>
 
 ### Tela - Login
 
<p align="justify">  Na tela de login, mostra os elementos padrões do cabeçalho, rodapé e temos o bloco principal de login:
 
> - **Área para login de usuários:** são solicitadas as informações de e-mail e senha para que o login seja efetuado. O usuário possui disponível também a opção de recuperação de senha.</p>

![Login](https://user-images.githubusercontent.com/74699119/168448419-e40fef96-69b0-483f-91eb-ba978def3879.png)

 ### Tela - Tela inicial (pós login do usuário)
 
<p align="justify"> Tela inicial mostrada após realização do login pelo usuário, contém links de navegação para as demais telas/funcionalidades no menu lateral e no cabeçalho:</p>

<p align="justify"> No bloco de barra lateral à esquerda, as opções mostradas serão diferentes para cada tipo de usuário:

> - **Administrador:** Apresentará os menus de acesso para as telas de todos os usuário, agenda, mensagens, cadastrar usuários, alunos, turmas e disciplinas.
> - **Professor:** Apresentará os menus de acesso para as telas de minhas turmas, linha do tempo, agenda e mensagens.
> - **Responsável do aluno:** Apresentará os menus de acesso para as telas de linha do tempo, agenda, mensagens e assinaturas de autorização.
> - **Outros:** Apresentará os menus de agenda e mensagens.</p>

<p align="justify"> Além disso, todos os usuários poderão acessar as notificações e o menu de opções da conta a partir das opções "Notificações" e "Perfil" presentes no cabeçalho</p> 

<b>Tipo de usuário - Responsável do Aluno</b><br>
![painelResp](https://user-images.githubusercontent.com/74699119/173224633-4cdf8223-d491-487f-84ad-b36781f141cf.png)

<b>Tipo de usuário - Professor</b><br>
![painelProf](https://user-images.githubusercontent.com/74699119/173224636-2c4fa161-73d4-4ddd-86e2-1a750e65a938.png)

<b>Tipo de usuário - Administrador</b><br>
![painelAdmin](https://user-images.githubusercontent.com/74699119/173224665-839d496b-4f4d-46cd-bfca-bf348bbe7fb4.png)

<b>Tipo de usuário - Outros</b><br>
![paineloutro](https://user-images.githubusercontent.com/74699119/173224630-06fc5cc7-fd8b-44b3-ba3c-abf5720dfd20.png)
 
### Tela - Mostrar notificações 

<p align="justify"> Na tela de notificações, são mostrados avisos para os usuários, sejam notificações do sistema ou notificações lançadas diretamente pelo administrador. Será mostrado aos usuários um resumo das notificações no botão "Notificação" na parte superior da tela, bem como em um painel centralizado na página. Usuários do tipo "Administrador" poderão criar novas notificações que serão enviadas para os demais usuários clicando na opção "Criar notificação". </p>

<b>Tipo de usuário: Professor, Responsável do Aluno e "Outros"</b>
![notificacaoOutros](https://user-images.githubusercontent.com/74699119/173224832-127fdab8-50fd-4f57-88aa-252b7be87ddb.png)

<b>Tipo de usuário: Administrador</b>
![notificacaoAdmin](https://user-images.githubusercontent.com/74699119/173224983-53e42a1f-6959-4306-bd87-93740482cec3.png)

### Tela - Criar notificação

 <p align="justify"> Tela acessada pelo Administrador ao clicar em "Criar notificação" no menu de notificações. Permite criar uma nova notificação e lança-la no sistema.</p>
![criarNotificacao](https://user-images.githubusercontent.com/74699119/173224991-c41c9e31-7deb-407d-97e0-f4fe515fd283.png)

### Janela - Opções da conta

<p align="justify">  Será permitido aos usuários acessarem o submenu de opções da conta, que possui as funcionalidades de "Alterar dados", que direciona o usuário para a tela de "Alterar informações da conta" e "Sair", que finaliza a sessão do usuário realiznado logoff.</p>

![menuUsuari](https://user-images.githubusercontent.com/74699119/173226592-f25ab195-b30a-4764-8e34-956570a8210b.png)
 
### Tela - Alterar informações da conta

 <p align="justify">  Será permitido aos usuários modificarem suas informações básicas, como email, telefone, senha e endereço ao preencher o formulário solicitando as novas informações e clicando em "Salvar".</p>

![alterarDados](https://user-images.githubusercontent.com/74699119/173226585-1de1485c-877c-4713-b8a6-27578ef158f1.png)

### Tela - Lista de agendas
 
<p align="justify">  Será permitido ao administrador do sistema visualizar todas as agendas cadastradas no sistema, bem como criar novas agendas.</p>

![listaAgendas](https://user-images.githubusercontent.com/74699119/173226650-fb3149d9-c77f-46b5-9b99-f876ea74f0b5.png)

### Tela - Cadastrar nova agenda
 
<p align="justify">  Será permitido ao administrador do sistema criar novas agendas, selecionando a turma e o tipo de usuário que terá acesso a ela.</p>

![cadastraAgenda](https://user-images.githubusercontent.com/74699119/173226751-d15d9d43-c58c-47c7-a856-2b42a4879bfe.png)

### Tela - Visualizar agenda escolar
 
 <p align="justify">  Será permitido aos usuários visualizar um calendário contendo os eventos da escola de acordo com a data em que estão marcados. Os usuários do tipo "Professor" e Administrador" poderão não só visualizar, como também cadastrar eventos na agenda.</p>
 
<b> Tipo de usuário: Responsável do aluno ou "Outros"</b>

![calendarioOutros](https://user-images.githubusercontent.com/74699119/173225910-fd20e5ce-2edd-45fe-97e3-319ee00db8ce.png)

<b> Tipo de usuário: Administrador ou Professor</b>

![calendarioAdmin](https://user-images.githubusercontent.com/74699119/173226299-acefe4b3-1114-40ef-a6fb-d879925db5f7.png)

### Tela - Cadastrar novo evento em agenda
 
<p align="justify">  Será permitido aos usuários do tipo "administrador" e "professor" cadastrar eventos nas agendas criadas, sendo que o administrador pode cadastrar um evento para aparecer em todas as agendas, enquanto o professor pode cadastrar eventos apenas nas agendas que possui acesso.</p>

![cadastrEvento](https://user-images.githubusercontent.com/74699119/173226431-4ae1f22e-add3-42f9-85f9-1d6c6c8c2c8e.png)

### Tela - Listar eventos cadastrados
 
<p align="justify">  Será permitido aos usuários do tipo "administrador" e "professor" visualizar os eventos cadastrados nas agendas que possuem acesso. O usuário poderá também apagar eventos que tenha cadastrado, mas não eventos cadastrados por outros usuários.</p>

![listaEventos](https://user-images.githubusercontent.com/74699119/173226435-a4acc261-2a85-47db-81e3-c8a23bd65319.png)

### Tela - Caixa de mensagens

 <p align="justify">  Será permitido aos usuários receber e enviar mensagens contendo texto, imagens e video. Esta tela mostra a caixa de entrada de mensagens.</p>
  
![mensagens](https://user-images.githubusercontent.com/74699119/173227546-396407fc-a0c5-4abb-a50e-68b240eb2269.png)

### Tela - Criar nova mensagem

 <p align="justify">  Será permitido aos usuários receber e enviar mensagens contendo texto, imagens e video. Esta tela mostra a tela de criação de nova mensagem, onde o usuário pode enviar uma mensagem para uma lista de destinatários, iniciando assim uma nova conversa.</p>

![criarconversa](https://user-images.githubusercontent.com/74699119/173228328-84439fdd-2d92-4f64-9e37-801470d89255.png)

### Tela - Visualizar mensagens da conversa

 <p align="justify">  Será permitido aos usuários receber e enviar mensagens contendo texto, imagens e video. Esta tela é acessada ao clicar na opção "Visualizar" em uma conversa presente na caixa de mensagens, nesta tela, o usuário pode visualizar todas as mensagens da conversa (isto é, a mensagem original e as respostas à mensagem original e a outras respostas da conversa). O usuário pode também criar uma resposta a uma das mensagens clicando na opção "Responder" ou "Responder a todos" no corpo da mensagem desejada.</p>
  
![visualizarmensagens](https://user-images.githubusercontent.com/74699119/173227552-6019494f-b466-4a2d-899c-6f292e46c37c.png)

### Janela - Responder mensagem da conversa

 <p align="justify">  Será permitido aos usuários receber e enviar mensagens contendo texto, imagens e video. Esta tela é acessada ao clicar na opção "Responder" ou "Responder a todos" em uma mensagem presente na conversa. Nesta tela, o usuário pode compor sua resposta de forma similar ao que é realizado na tela de "Criar nova mensagem" e envia-la clicando em "Responder" dentro da janela de responder mensagem da conversa.</p>

![responder](https://user-images.githubusercontent.com/74699119/173228333-92455434-794a-4ae8-b13c-662c5296097a.png)

### Tela - Selecionar linha do tempo
 
![selecionarLinhadotempo](https://user-images.githubusercontent.com/74699119/173228316-6ae18198-4fae-4dc1-8301-23d2a1c38c4d.png)

### Tela - Visualizar linha do tempo
 <p align="justify"> Tela aonde se encontram todas as postagens realizadas pelos professores na linha do tempo, bem como a opção de criar comentários nas postagens (disponível tanto para os professores quanto responsáveis do aluno).</p>
 
 <b>Tipo de usuário - Responsável do Aluno</b><br>
  
  > - **Responsável do aluno:** Será permitido ao usuário visualizar imagens adicionadas de seus filhos. Este usuário poderá ver todas as fotos adicionadas e interagir através de comentários.
  
![linhadotempoResp](https://user-images.githubusercontent.com/74699119/173227787-89c6984d-537e-4ecc-9826-759ae4cc2178.png)

 <b>Tipo de usuário - Professor</b><br>
  
  > - **Professor:** Este usuário poderá criar postagens adicionando texto e imagens de um determinado aluno, bem como interagir com a publicação por meio de comentários.
  
![linhadotempoProf](https://user-images.githubusercontent.com/74699119/173227791-4b4630a7-3c5a-4e13-906b-4e2d3a8028a1.png)

### Tela - Criar postagem em linha do tempo
<p align="justify"> Será permitido aos professores postar eventos dos alunos em uma "linha do tempo", que poderá ser visualizada pelos responsáveis do aluno.</p>
 
![criarPostagem](https://user-images.githubusercontent.com/74699119/173227967-9ed98c9c-9ae9-4c50-8d86-0dccaeeb54c3.png)

### Tela - Visualizar autorizações para assinar

<p align="justify">  Será permitido aos usuários do tipo "Responsável do aluno" visualizarem notificações de eventos que necessitam de sua autorização, assinalando se autorizam ou não que seu filho participe. Ao usuário será apresentada uma mensagem informando o conteúdo necessário de autorização, que pode ser um evento, excursão etc.</p>
 
![listaAuto](https://user-images.githubusercontent.com/74699119/173228109-c9bba083-b003-4c33-b723-32bb17a45909.png)

### Tela - Assinar autorização

<p align="justify"> Tela contendo a descrição do evento em questão, bem como as opções "Sim" e "Não" que o usuário poderá selecionar para autorizar ou não a participação do dependente no evento.</p>
 
![autorizar](https://user-images.githubusercontent.com/74699119/173228111-5bf48ac0-37b3-406c-a78f-7445b9a3aa93.png)

### Tela - Visualizar turmas do professor
 
<p align="justify">  Será permitido aos usuários do tipo "Professor" visualizar todas as turmas que estão sob sua responsabilidade e os alunos atrelados a elas. Ao clicar em "Visualizar" na coluna "Lista de alunos" o usuário será redirecionado a uma tela contendo a lista de alunos daquela turma, bem como seus responsáveis.</p>

![minhasturmas](https://user-images.githubusercontent.com/74699119/173228238-438c3f67-f523-43d6-b38b-8149bc1aa8be.png)

### Tela - Visualizar alunos das turmas (Professor)
 
<p align="justify"> Tela que permite ao usuário visualizar a lista de todos os alunos daquela turma específica, bem como seus responsáveis.</p>

![alunosturmas](https://user-images.githubusercontent.com/74699119/173228239-f52e3bdd-d5af-4bf1-a2c4-85d7231609f7.png)

### Tela - Visualizar todos os usuários do sistema

<p align="justify">  Será permitido aos usuários do tipo Administrador visualizar todos os usuários cadastrados no sistema, vendo suas informações básicas de nome completo, nome de usuário e tipo de usuário. Poderão também editar ou deletar contas de usuários.</p>

![usuario](https://user-images.githubusercontent.com/74699119/173230992-0745694b-4ed1-45b8-a605-9b2bf18630a2.png)

### Tela - Cadastrar usuário

<p align="justify">  Será permitido aos usuários do tipo Administrador cadastrar um novo usuário ao sistema, adicionando informações previamente apresentadas, bem como selecionar o tipo de usuário atrelado aquele novo usuário.</p>
 
![usuariocadastrar](https://user-images.githubusercontent.com/74699119/173230994-69624fd7-2973-4bf1-a01a-f6f9087d215f.png)

### Tela - Visualizar disciplinas cadastradas

<p align="justify">  Será permitido aos usuários do tipo Administrador visualizar a lista de disciplinas cadastradas no sistema, bem como apagar disciplinas cadastradas ou editar suas informações, incluindo horário das aulas e turma da qual faz parte.</p>

![disciplinas](https://user-images.githubusercontent.com/74699119/173231041-f09b8fdf-e4e9-45e2-b107-9a3469f3ae8d.png)

### Tela - Cadastrar disciplina

<p align="justify">  Será permitido aos usuários do tipo Administrador cadastrar novas disciplinas no sistema, definindo seus horários na semana e podendo escolher a turma da qual faz parte. O usuário deverá clicar nas opções desejadas e seguir o fluxo de preenchimento apresentado pelo sistema.</p>
 
![disciplinascadastrar](https://user-images.githubusercontent.com/74699119/173230999-68bf1141-ecca-43ea-9b60-f9c518642aff.png)

### Tela - Visualizar turmas cadastradas

<p align="justify">  Será permitido aos usuários do tipo Administrador visualizar a lista de turmas cadastradas no sistema, bem como apagar ou editar informações das turmas cadastradas e visualizar/editar o quadro de horários contendo as disciplinas associadas a turma.</p>

![turmas](https://user-images.githubusercontent.com/74699119/173231007-53ecf708-f2b8-417a-831a-d852ec0303cb.png)

### Tela - Cadastrar turma

<p align="justify">  Será permitido aos usuários do tipo Administrador cadastrar uma nova turma, em que lhe será apresentada uma opção de inserir o nome e código de uma nova turma e salvar no sistema. Após o cadastro da turma, o Administrador será direcionado para o quadro de disciplinas da turma, aonde poderá selecionar as disciplinas que compõe o quadro de horários semanal da turma.</p>
 
![turmascadastrar](https://user-images.githubusercontent.com/74699119/173231012-53589e04-02db-4c23-af3f-9c27819bc863.png)

### Tela - Visualizar alunos cadastrados
<p align="justify">  Será permitido aos usuários do tipo Administrador visualizar a lista de alunos cadastrados no sistema, bem como remover alunos cadastrados ou editar suas informações para situações nas quais seja necessário trocar sua turma ou adicionar mais responsáveis.</p>

![alunos](https://user-images.githubusercontent.com/74699119/173231014-d9af53a0-a69e-4285-b2ea-3c5dcc2401c2.png)

### Tela - Cadastrar aluno

<p align="justify">  Será permitido aos usuários do tipo Administrador cadastrar um novo aluno ao sistema, atrelando este ele a seus responsáveis (previamente cadastrados como usuários do tipo "Responsável de aluno") e também a uma turma.</p>

![alunoscadastrar](https://user-images.githubusercontent.com/74699119/173231017-eec4a025-7d56-4c31-bc86-0f4a4f8cd824.png)

### Tela - Ver quadro de horários/Associar disciplinas à turma
 
<p align="justify">  Será permitido aos usuários do tipo Administrador associar disciplinas cadastrada à uma turma cadastrada, vinculando essas informações. Nesta tela também é possível visualizar o quadro de horários correspondente às disciplinas atualmente associadas àquela turma.</p>

![quadro](https://user-images.githubusercontent.com/74699119/173231018-31f384b4-20aa-4ee5-8b86-da8d475d6bba.png)
