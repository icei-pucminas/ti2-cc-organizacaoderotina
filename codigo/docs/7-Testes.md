# Avaliação da Aplicação

## Plano de Testes

Item testado - Teste - Resuldado esperado - Resultado obtido

> Item testado:
> Homepage

> Teste:

1 - Conexão com Internet

Passos

1 - Entrar no site

2 - Alterar as seções da página inicia

> Resuldado esperado:
> Homepage alterável, podendo mostrar apenas o que o usuário poderá ver
> Resultado obtido:
> Informações somem, mas não aparecem.

> Item testado:
> Cadastro
> Teste:
> Pré-condições

1 - Conexão com Internet

Passos

1 - Criar no mínimo uma conta no sistema

2 - Verificar se a conta foi salva corretamente no localStorage

> Resuldado esperado:

Conta criada com sucesso

> Resultado obtido:

Conta hipotética “Capsm” criada e salva no localStorage com sucesso

> Item testado:

Resumos de matéria

> Teste:
> 1 - Conexão com Internet

Passos

1 - Criar um resumo de matéria no sistema

2 - Criar um resumo adicionando um arquivo externo

3 - Acessar os dois resumos criados

> Resuldado esperado:
> Os dois resumos salvos e acessíveis no sistema.

> Resultado obtido:

Resumos criados, salvos no localStorage e visíveis na página do usuário, mas ainda não acessíveis.

> Item testado:
> Quadro de horários

> Teste:
> Pré-condições

1 - Conexão com Internet

Passos

1 - Criar uma tarefa no formulário que ocorra em um dia.

2 - Verificar se a tarefa se encontra na parte correta do quadro.

3 - Criar uma segunda tarefa que ocorra em mais de um dia.

4 - Verificar se a tarefa aparece em todos os dias em que deveria aparecer.

5 - Remover tarefas criadas da tabela e verificar se foram de fato removidas do localStorage.

> Resuldado esperado:
> Todas as tarefas criadas, exibidas e removidas do quadro corretamente.
> Resultado obtido:
> Tarefas são criadas, exibidas e removidas corretamente, mas o valor correspondente ao número de tarefas não é atualizado com a remoção de tarefas

> Item testado:
> Cronômetro Pomodoro

> Teste:
> Pré-condições

1 - Conexão com internet

2 - Item “Resumos de matéria” funcionando.
Passos

1 - Ativar o timer “Fazer atividade” e conferir se o tempo está sendo contabilizado corretamente. Após um tempo determinado, clicar no botão “Parar”.

2 - Ativar o timer “Curta pausa” e conferir se o tempo está sendo contabilizado corretamente. Após um tempo determinado, clicar no botão “Parar”.

3 - Ativar o timer “Longa pausa” e conferir se o tempo está sendo contabilizado corretamente. Após um tempo determinado, clicar no botão “Parar”.

4 - Acessar os resumos de matéria salvos (e/ou salvar um resumo) na tela do cronômetro

> Resuldado esperado:
> Os três timers funcionando corretamente

Botão “Parar” funcionando com os três timers
Item “Resumos de matéria” acessível a partir da tela do cronômetro

> Resultado obtido:

Timers funcionando corretamente e pop up dos resumos de matéria aparecendo após o término do timer “Fazer atividade”

> Item testado:
> Agenda de lembretes
> Teste:
> Pré-condições

1 - Conexão com internet

Passos

1 - Criar um lembrete.

2 - Verificar se o
lembrete está visível dentro e fora da tela de adição de lembretes.

3 - Remover o lembrete na tela de adição.

4 - Verificar se o lembrete foi removido do localStorage e se não está mais visível fora da tela de adição.

> Resuldado esperado:

Lembrete adicionado, visível e removido corretamente.

> Resultado obtido:

Lembrete adicionado e removido corretamente, mas não exibido em todas as páginas do sistema.

> Item testado:
> Login
> Teste:
> Pré-condições

1 - Conexão com Internet

2 - Item “Cadastro” funcionando

Passos

1 - Tentar acessar o sistema com uma conta não criada.

2 - Tentar acessar o sistema com uma conta criada anteriormente.

> Resuldado esperado:
> Mensagem de erro quando usuário e/ou senha incorretos forem digitados

Sistema acessado por uma conta criada

> Resultado obtido:
> Login realizado com sucesso usando a conta hipotética “Capsm”

## Avaliação

1 - Homepage
Inicialmente, a homepage do sistema exibia, após uma mensagem inicial, duas informações principais: uma descrição de algumas das principais funcionalidades do projeto e informações sobre os membros do grupo. Agora, foi adicionada uma funcionalidade que permite ao usuário escolher se essas informações são exibidas ou não, mas uma vez ocultada, as informações não aparecem novamente.

2 - Resumos de matéria

Aparecendo o pop up para adicionar um resumo, foi criado o resumo de Cálculo sobre a Regra da Cadeia
Como consta nos wireframes, os resumos serão exibidos na página do usuário, algo já ocorrente na versão atual do projeto.

3 - Cronômetro Pomodoro

Começamos o teste ligando o timer “Fazer atividade”, de 25 minutos.
O botão “Parar” foi pressionado, interrompendo o timer, e em seguida foi ligado o timer “Curta pausa”, de 5 minutos.
O botão “Parar” foi pressionado, interrompendo o timer, e em seguida foi ligado o timer “Longa pausa”, de 15 minutos.
Evidenciando também que, após o término do timer “Fazer atividade”, aparece o pop up para adicionar um resumo de matéria (funcionalidade anterior).

4 - Quadro de horários

Primeiro foi criada a tarefa “Aula de LIP”, que ocorre em todas as segundas, entre 13:30 e 15:10.
Verificando a página onde o quadro de horários se encontra, podemos ver que ele aparece apenas no card da segunda-feira.
Agora, foi adicionada a tarefa “Aula de AED”, que ocorre em três dias da semana: segunda, terça e quarta, no horário entre 15:20 a 17:00.
Conferindo a tabela, vemos que a tarefa aparece nos três dias selecionados.
As tarefas são colocadas no quadro na ordem em que foram criadas. Para exemplificar, criamos uma terceira tarefa, “Aula de Cálculo 1”, que ocorre terça e quinta, entre 13:30 e 15:10 (na terça, logo, antes da “Aula de AED”).

Removendo agora as três tarefas do quadro
Vale ressaltar, porém, que o valor “numTasks”, usado para contabilizar as tarefas criadas, não é atualizado com a remoção de tarefas.

5 - Agenda de lembretes

Inicialmente, criaremos o lembrete “TI - Entrega parcial 3”, para o dia 01/07/2020, às 23:59:
A tarefa foi criada e é exibida corretamente ao lado do formulário, mas os campos do formulário não são limpos após a adição da tarefa.
Vale ressaltar também que, como consta nos wireframes, os lembretes criados serão exibidos também na tela onde se encontra o quadro de horários. No entanto, ainda não aparece nenhum lembrete na página.
Removendo a tarefa criada clicando nela

6 - Cadastro e login

Para testar o cadastro, foi criada uma conta hipotética “Capsm” :
Agora, para testar o login no sistema, vamos usar a conta criada :
