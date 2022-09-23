# Desafio-Sprint-1-Flutter-set.22
Repositório para arquivar as respostas do Desafio da Sprint 1 da trilha de @Flutter Set.22

Perguntas:
1. Para que serve o método Scrum?

    O Scrum é um modelo de metodologia Agile e tem como sua principal função oferecer padrões e rotinas para a organização do trabalho desenvolvido pelas equipes das mais diversas áreas. Como por exemplo, na nossa realidade, o framework é aplicado à entrega de projetos. Assim, acelerando não só a entrega final destes, mas também criando um fluxo de entregas constantes ao cliente.

2. Como funciona o método Scrum?

    O Scrum se baseia na padronização das rotinas e fluxos de trabalho para que haja o aumento da performance do time. Assim, ele utiliza do seu diferencial, as timestamps, para determinar a duração de cada uma dessas rotinas, sejam as básicas de iteração, sejam as cerimônias que fazem o review de cada Sprint. Por conseguinte, essa metodologia, tem em seu cerne um fluxo repetitivo - o qual dura até que seja encerrado o projeto no qual este está sendo utilizado - que consiste de uma cerimônia inicial de planejamento da sprint (Planning) onde é analisado o Product Backlog e definido o Sprint Backlog com suas estórias e tarefas. posteriormente então é iniciada a Sprint - essa tem uma duração limitada podendo durar até 1 mês - a qual consiste no tempo em que a equipe deve agregar valor para o usuário do produto. Durante a Sprint, ocorre a Daily que, como o nome já diz, acontece diariamente e tem uma duração de 15 min, nela cada membro fala o que fez no dia anterior, o que pretende fazer no dia e se houve algum problema ou impedimento para ele. Por fim, após o processo da Sprint acontecem duas últimas cerimônias, a Review Meeting, quando a equipe apresenta para o usuário/cliente o que foi desenvolvido e então recebe o feedback e a última seria a Retrospective, uma cerimônia realizada por todo o time na qual são levantados os pontos positivos e negativos da sprint, criando ações para solucionar esses que foram atribuídos como negativos, essa consiste na reunião de melhoria contínua do Framework. Assim, com uma descrição breve de cada rotina, podemos perceber como funciona o Scrum, mas é importante lembrar que todos esses momentos são regidos pela timestamp definida no início de tudo e como o método já diz, essas rotinas acontecem sem parar até que o projeto seja entregue, seguindo sempre o mesmo padrão, o que aumenta a eficiência na entrega de valor para o usuário/cliente.

3. O que é GIT?

    O GIT é um sistema de controle de versões distribuído, o qual além de permitir o fácil compartilhamento de arquivos, códigos, etc., facilita e possibilita que múltiplas pessoas trabalhem, ao mesmo tempo, em um único arquivo e permite o acompanhamento do histórico desses arquivos os quais podem ser recuperados caso seja necessário. 

4. O que é um Scrum Product Owner?

    O Product Owner ou PO, dentro da metodologia do Scrum, representa aquele que vai fazer o contato com o cliente do projeto para entender quais são suas prioridades e necessidades dentro daquilo que está sendo desenvolvido. Assim, o PO tem uma função essencial para o funcionamento das rotinas, a função de alimentar e atualizar o Product Backlog conforme as necessidades do cliente, priorizando as estórias que devem ser desenvolvidas e refinando estas para que sejam levadas à reunião de Planning e possam ser facilmente quebradas em tarefas com as quais a equipe de desenvolvimento vai estimar o esforço necessário para desenvolver e então irá adicionar à Sprint Backlog. Ademais, cabe ao PO esclarecer toda e qualquer dúvida que surja por parte dos desenvolvedores sobre os requisitos desenhados pelo cliente. Portanto, de forma breve, cabe ao Product Owner realizar todo o tipo de troca de informação com o cliente, tornando claro e fácil pra equipe de desenvolvedores entender os pontos que irão agregar mais valor à entrega e fornecendo a eles toda a informação necessária.

5. Qual o comando para criação de um novo repositório no GIT?
    
    O comando para criar um novo repositório no GIT é o: git init.

6. Com o Git Você pode propor mudanças (adicioná-las ao Index)  usando um comando. Qual é esse comando?  

    O comando para propor mudanças, adicionar ao index, é o git add que conta com a especificação do arquivo que será adicionado ou com o caractere * para adicionar todas as alterações ao Index.

7. O que é o Branch master e para que serve?

    O branch master é a primeira ramificação criada quando iniciamos o repositório e nela ficarão guardados todos os nossos commits, nodo por nodo, caso não optemos por mudar de branch. Assim, facilita com que possamos ver todas as alterações realizadas dentro desta "linha" desde sua criação até seu estado atual, podendo até mesmo comparar as diferenças entre as versões. 

8. Quais são os comandos usados para atualizar um repositório local e fazer merge de um outro branch ao seu branch ativo ?

    Para atualizar um repositório local com o que está no servidor, utilizamos o git pull e para realizar o merge de um branch com o nosso branch ativo, usamos o git merge especificando o branch com o qual iremos fazer o merge.

9. Qual a diferença entre Git e Github?

    A grande diferença entre ambos, é que o Git consiste no sistema de versionamento de arquivos propriamente dito, enquanto o Github é uma plataforma que utiliza o Git por baixo, para permitir que as pessoas armazenem seus projetos e trabalhem de forma colaborativa nos seus repositórios criados com o Git.

10. Quais os dois verbos http que podemos utilizar para realizar um update? Explique a diferença entre eles.

    Os dois verbos http que utilizamos para atualizar uma informação são: o Put e o Patch, todavia apesar de realizarem a mesma ação eles possuem uma clara diferença. Enquanto que, para atualizar uma informação via método PUT é necessário, além do ID que será modificada, que sejam passados todos os parâmetros do objeto, mesmo que estes não tenham sido alterados, utilizando o método PATCH, é necessário apenas enviar a requisição com a ID e com os atributos que foram devidamente modificados, não sendo necessário repassar aqueles os quais não sofrerem nenhum tipo de alteração.

11. Qual o status code que pode ser usado na criação de um novo usuário?

    O status code que pode ser utilizado na criação de um novo usuário são os da família 200 que contemplam os status de resposta para o sucesso na requisição, todavia, mais especificamente, o status code que pode ser utilizado é o 201 que corrobora que a requisição foi processada pelo servidor e em função disso um recurso foi criado.

12. Quais são os três status code que podem ser utilizados para realizar o delete?

    Os três status code que podem ser utilizado com o método Delete são:
    - 200 (OK) para quando a requisição foi realizada e ainda retorna uma mensagem descrevendo o status da ação;
    - 202 (Accepted) para quando a requisição foi aceita mas ainda não foi realizada;
    - 204 (No Content) para quando a requisição foi realizada e nenhuma informação adicional deve ser fornecida.

13. Exemplifique para que serve os status code http 1xx, 2xx, 3xx, 4xx e 5xx. De uma forma macro (geral)!

    De forma geral, os status code de cada família tem a seguinte função:
    1xx - São os códigos de informação, retornam uma resposta temporária indicando o status da conexão ou progresso da requisição para processar e enviar uma resposta;
    2xx - Esses códigos indicam que a operação foi bem sucedida;
    3xx - É a família do redirecionamento e indica que ações devem ser realizadas pelo cliente para preencher a/as requisições enviadas;
    4xx - Os códigos começados em 4 indicam a existência de algum erro na requisição feita pelo cliente;
    5xx - Os iniciados em 5 indicam que houve um erro por parte do servidor ao processar ou responder a requisição.

14. O que é a linguagem de programação Dart?

    Dart, além de ser uma linguagem criada e mantida pela Google, é a base para a utilização do framework de desenvolvimento Flutter. Como outras grandes linguagens presentes no mercado, seu paradigma de programação de baseia na Orientação a objetos.

15. O que é o Flutter?

    Flutter é um framework de desenvolvimento com base na linguagem de programação Dart. Por conseguinte, em função de ser um framework, o Flutter nos oferece diversos recursos já construídos que facilitam e aceleram o processo de desenvolvimento principalmente naquilo que diz respeito às plataformas mobile. Nesse sentido, podemos ressaltar que apesar do Flutter trabalhar com Dart, ao exportar os projetos criados tanto para IOS quanto Android, o próprio framework realiza a “tradução” do código para a linguagem nativa de cada plataforma, otimizando a performance dessa aplicação em ambos sistemas operacionais. Ademais, devemos salientar que, apesar de ser voltado principalmente para o desenvolvimento mobile, o Flutter já pode ser usado para desenvolvimento de projetos Web e Windows.

16. Como inicio um novo projeto no Flutter?

    Para iniciar um projeto em Flutter é bem simples, todavia inicialmente precisamos garantir que temos instalado o SDK do Flutter o qual já vem com o SDK do Dart. Posteriormente, basta entrar na sua IDE e selecionar novo projeto -> criar projeto flutter, ou caso ache mais fácil, podemos ir no terminal e digitar flutter create <nome do projeto> assim o próprio framework irá se encarregar de criar um projeto no local (pasta/diretório) em que foi chamado.

17. Quais ferramentas podemos utilizar para a criação de novos apps usando Flutter?

    Para a criação de novos apps utilizando o Flutter, podemos fazer uso de qualquer IDE (Integrated Development Environment) desde que essa tenha suporte à linguagem de programação Dart. Alguns exemplos de ferramentas que podem ser utilizadas são as seguintes: VsCode, Intelij e Android Studio. Ademais, cabe ressaltar que podemos e é recomendado utilizarmos o Android Emulator, o qual é baixado junto com o Android Studio, para que possamos ver como está sendo o desenvolvimento do nosso aplicativo.

18. Qual a diferença entre uma variável final e uma variável var?

    Em Dart, uma variável final só pode ter seu valor alterado uma única vez, ou seja, ela pode aparecer em duas ou uma chamada, uma sendo declarada e então uma sendo atribuída ou caso já seja iniciada com um valor, independente da forma que ela aparece, após ser atribuído um valor, ela não poderá mais ser alterada durante o código. Paralelamente a isso, temos a variável com o prefixo var que explicita que ela pode ser alterada livremente durante o código. Portanto, a grande diferença entre elas está na capacidade de ser alterada enquanto uma só pode receber o valor uma vez, a outra pode sofrer alterações conforme necessidade. Ademais, caso não seja adicionado um prefixo final ou const à variável, o próprio framework irá trata-la como var.

19. Qual a diferença entre um Statefull e Stateless widget?

    A grande diferença entre esses dois widgets está na forma como o Flutter irá lidar com eles, no caso do Statefull o framework fica “olhando” para aquele widget visto que ele permite que alterações ocorram dentro dele, sejam de variáveis, sejam de estados que terão que ser rebuildados. Já no Stateless widget, o Flutter otimiza o seu processamento visto que ele entende que dentro daquele widget não haverá alterações não sendo mais necessário ficar “olhando” para ele após ele ser buildado. Portanto, de forma simples, enquanto o Statefull é capaz de alterar o estado da aplicação, o Stateless não consegue fazer essa ação.

20. Para que serve o conceito de gerenciamento de estado e como ele pode ser aplicado na prática?

    O conceito de gerenciamento de estados presente no Flutter tem como seu principal objetivo avisar o framework para ele saber quando deve ou não rebuildar a tela ou o widget em questão. Assim, o Flutter consegue realizar a ação de forma otimizada e performática sob demanda do app. Para isso, utilizamos o notificador nativo do framework presente nos widgets Statefull, o setState, com ele conseguimos notificar o flutter para rebuildar a tela ou o widget em questão para então mostrar as alterações que uma ação do usuário pode ter realizado. Por conseguinte, a título de exemplificação usamos o gerenciamento de estados no exemplo mais simples do flutter quando temos um contador que ao pressionar um botão atualiza ou reseta ele, para isso é utilizada uma variável e cada clique no botão é envolvido por um setState responsável por avisar o framework que ele precisa reconstruir aquela tela.

21. Qual a finalidade dos métodos InitState e dispose?

    Apesar de ambos os métodos realizarem ações definidas pelo código, cada um tem uma finalidade diferente para a qual é utilizada. Enquanto o InitState é chamado para executar linhas de ações antes do Flutter buildar uma tela, o dispose é chamado para também executar ações só que antes do Flutter descartar uma tela, ou seja, antes de fecha-la. Por conseguinte, a título de exemplo, o InitState é utilizado para carregar informações antes de abrir uma tela, seja dados de uma API ou conexões com sistemas externos tais como o Firebase, já o dispose utiliza da sua capacidade para deixar de executar ações que estão utilizando o poder computacional do hardware para então otimizar o processo do App.

22. Conta pra gente como foi sua experiência na Sprint#01 do programa de bolsa @Flutter-set.22 e quais suas expectativas a partir de agora:

    Acredito que nessa Sprint#01 já consegui agregar bastante conhecimento sobre a nossa trilha de Flutter, contudo sei que para eu fixar esse conteúdo, tenho que colocar em prática aquilo que estou aprendendo. Dessa forma, essa questão já baseia a minha expectativa para as próximas sprints, aprofundar mais meu conhecimento nas diversas áreas de desenvolvimento como, por exemplo, os testes de qualidade e receber desafios os quais vão me desenvolver cada vez mais para que seja possível entregar um resultado exemplar em cada Sprint.