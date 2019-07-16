## CEV Mobile

Bem vindo, este guia vai te ajudar a entender e trabalhar com o aplicativo [Cev Mobile](https://play.google.com/store/apps/details?id=itmil.mil_mobile)

O Cev Mobile � um aplicativo criado para que o CRM de DMS da TOTVS possa ser utilizado com maior facilidade e menos dificuldade pelos colaboradores diretamente associados com o atendimento ao cliente. Como ele funciona offline tamb�m � poss�vel sua utiliza��o fora de ambiente com conex�o o que resolve o problema em caso de fazendas ou �reas afastadas onde n�o existe rede celular.

Para sua utiliza��o basta que o usu�rio tenha em m�os o endere�o do webservice de integra��o com protheus e o entendimento geral de sua utiliza��o

### In�cio

Ao abrir o aplicativo voc� vai se deparar com a tela principal, nela abra o menu para fazer a configura��o inicial, no menu procure `Configura��es` nela voc� dever� colocar o endere�o do webservice, porta e seu CPF e clique em salvar, caso n�o saiba o endere�o ou porta do webservice entre em contato com o respons�vel de TI.

Agora v� para o menu novamente, clique em `Sincronizar`, nela clique no bot�o `Sincronizar` e voc� dever� ver que uma nova linha ser� adicionada acima dos bot�es e um percentual ser� apresentado. Caso este comportamento n�o aconte�a poss�velmente sua configura��o est� errada.

Caso algum erro aconte�a voc� pode verificar clicando na linha do percentual, alguns erros de timeout podem acontecer e s�o at� normais dependendo da sua conex�o com a internet, caso ocorram voc� pode sempre tentar novamente fazer a sincroniza��o.

### Agendas

A `Agenda` � a entidade que representa um contato com o cliente, nela voc� deve registrar todos os contatos, as conversas e os detalhes referentes a negocia��es, quanto mais detalhes melhor para o neg�cio.

Para registrar uma agenda entra no `Menu` depois `Agendas`, nele voc� ver� o dashboard.

<img src="images/dashboard_agendas.png" alt="dashboard agendas" width="250"/>

Nesta tela voc� pode separar as agendas em agendas da `Semana`, Do `Dia` ou `Todas`, acima pode ser feito um filtro ver as agendas por semana ou no `+` onde podemos criar uma nova agenda.

Ao clicar no `+` voc� ver� a seguinte janela:

<img src="images/agenda.png" alt="formul�rio de cadastro de agendas" width="250"/>


### Oportunidades

As `Oportunidades` s�o o registro principal de vendas de m�quinas ou ve�culos, esta entidade vai te ajudar a organizar e controlar as negocia��es com o cliente at� a venda efetiva do produto.

Para registrar uma oportunidade v� ao `Menu` depois `Oportunidades`, na tela apresentada voc� ter� uma lista de clietes e prospects com um filtro e um menu superior.

<img src="images/dashboard_oportunidades.png" alt="dashboard de oportunidades" width="250">

No menu superior ver� um checkbox que filtra os clientes entre os que possuem oportunidades e os que n�o possuem. No �cone de `+` voc� poder� criar um prospect com os dados digitados nos campos `Nome, Documento e Telefone` e adicionar uma oportunidade ao mesmo.

Escolhendo um cliente ou criando um prospect o formul�rio de oportunidades ser� apresentado, nele voc� vai poder cadastrar sua oportunidade de neg�cio.

<img src="images/interesse_2.png" alt="formul�rio de interesse 2" width="250">

<img src="images/interesse.png" alt="formul�rio de interesse 1" width="250">

Lembrando que uma oportunidade pode conter mais de 1 interesse.

### Raic

Os `Raics` s�o os registros de satisfa��o ou insatisfa��o com o cliente, entrando em `Menu` depois `RAIC` ser� poss�vel registrar uma satisfa��o ou insatisfa��o para um cliente.

Prospects n�o podem ter `RAICS`

### Mapeamento GPS de Clientes

Em algumas telas voc� ver� bot�es e �cones representando se o cliente possui um mapeamento GPS em seu cadastrou ou n�o.

Caso o �cone <img src="images/sem_gps.png"> seja apresentado, significa que o cliente est� sem mapeamento de GPS para a loja.

Para mapear uma loja ou fazenda de um cliente v� em `Menu` depois `Clientes` procure o cliente e nos detalhes voc� ver� um bot�o de `check in` ao clicar no mesmo ele vai coletar as corrdenadas e gravar no cliente, sendo assim na pr�xima sincroniza��o o cliente agora ser� um cliente mapeado.

Tamb�m � poss�vel mapear o cliente pela tela de oportunidades bot�o checkin no menu superior.

### Sincroniza��o

No `Menu` `Sincronizar` repare que existem 2 bot�es, `SINCRONIZAR` e `R�PIDA` a diferen�a das duas consiste na quantidade de dados que ser� recebido e enviado entre celular e webservice de integra��o.

A sincroniza��o completa busca todos os dados para trabalho com celular e pode ser bem demorada pois trafega todos os clientes, modelos, oportunidades do celular.

A sincroniza��o r�pida somente envia os dados que foram alterados no celular para o webservice de integra��o, � bem mais r�pido e recomendado caso esteja em uma rede lenta 3G.

Embora seja poss�vel sempre usar a sincroniza��o r�pida alguns dados precisam de sincroniza��o completa de tempos em tempos, como por exemplo os modelos vendidos que podem ser inclu�dos novos, mapeamentos GPS de clientes, etc.
