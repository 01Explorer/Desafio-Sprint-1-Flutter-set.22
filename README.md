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