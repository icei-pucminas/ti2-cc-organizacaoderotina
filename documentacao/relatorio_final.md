# Organização de rotina


**Thais Camila Gonçalves costa, thaiscamilacc@gmail.com**

**Daniel Soares França**

**Filipe Arthur Ferreira Silva**

**Lucas Diniz de Moraes**

---

_Curso de Ciência da Computação, Unidade {Coração Eucarístico | Praça da Liberdade}_

_Instituto de Informática e Ciências Exatas – Pontifícia Universidade de Minas Gerais (PUC MINAS), Belo Horizonte – MG – Brasil_

---

Nosso objetivo é que o usuário atinja o máximo rendimento em suas tarefas com nosso site. Em uma pesquisa realizada pelo grupo no primeiro semestre de 2020 as pessoas apontam como principal problema a dificuldade de organizar a rotina, conciliar escola e tarefas de casa e colocar a matéria vista em dia, problemas agravados por questões como procrastinação, questões financeiras e psicológicas, então nosso objetivo geral e ter uma aplicação web que ajude-os a se organizar.
._

---



**1. Introdução**

**1.1 contextualização**
No livro O Poder do Hábito de Charles Duhigg é apresentada uma teoria de um loop do hábito, na qual, o funcionamento de todos nossas atividade rotineiras passariam esse loop, que começa com uma deixa, que é um ativador da rotina, a rotina sendo a atividade propriamente dita, e gerando um recompensa, porém grande parcela da sociedade apresenta dificuldades para organizar seu dia ,ou seja, construir esse loop de maneira positiva. Afinal, em uma sociedade corridas em que todos nós temos de ser multitarefas, é difícil para essas pessoas terem tempo para se organizar.
	Tendo isso em mente, fizemos uma pesquisa de campo com um questionário (em que recebemos 19 respostas de estudantes da PUC, UFMG, Coltec e estudantes de vestibular) e uma enquete em uma rede social (em que recebemos 11 respostas).
	A maioria das respostas apontam como principal problema desse grupo a dificuldade de organizar a rotina, conciliar escola e tarefas de casa e colocar a matéria vista em dia, problemas agravados por questões como procrastinação, questões financeiras e psicológicas.
No formulário também foi perguntado se as pessoas utilizam algum software que auxilie na organização. Nesse maior destaque vai ás pessoas que não utilizam esses serviços, que compõem mais de 60% das respostas

![Figura 1 - Gráfico de respostas do formulário](imagens/images/image19.jpg "Gráfico de respostas do formulário")


**1.2 Problema**
Conforme exposto, o problema que se busca resolver com este projeto é que o nosso usuário seja capaz de atingir o máximo rendimento em suas tarefas diárias , produzindo um crescimento constante pessoal para se tornar uma pessoa melhor.

**1.3 Objetivos gerais**
Criar uma aplicação web que ajude o usuário a organizar sua rotina, auxiliando na conciliação entre tarefas acadêmicas e pessoais, evidenciando também eventos e tarefas futuras importantes.
Como objetivos específicos, podemos ressaltar:
- **1.3.1** Disponibilizar uma agenda para organização da rotina. 
- **1.3.2** Salvar resumos de matéria estudada (técnica Feynman)
- **1.3.3** Cronômetro Pomodoro: Auxilia o usuário a organizar o tempo.

**1.4 Justificativas**
Após pesquisa de campo por diversas redes sociais ,foi verificado em nossos questionários que a grande maioria dos entrevistados têm dificuldade para organizar a rotina. Seja para estabelecer prioridades ,falta de motivação para comprir tarefas ,tempo diário mal utilizado, falta de persistência e entre outros.


**2. Projeto da Solução**
O escopo funcional do projeto é definido por meio dos requisitos funcionais que descrevem as possibilidades interação dos usuários, bem como os requisitos não funcionais que descrevem os aspectos que o sistema deverá apresentar de maneira geral. Estes requisitos são apresentados a seguir.

    2.1. Requisitos funcionais
	
A tabela a seguir apresenta os requisitos do projeto, identificando a prioridade em que os mesmos devem ser entregues.


| No.           | Descrição                       | Prioridade |
| ------------- |:-------------------------------:| ----------:|
| RF-01      | O site deve permitir ao usuário adicionar e remover lembretes de tarefas e eventos importantes | Alta      |
| RF-02      | O site deve permitir ao usuário adicionar e remover tarefas cotidianas.                                |  Alta    |
| RF-03      | O site deve conter um cronômetro que siga a ideia da técnica Pomodoro.                                 |  Média  | 
| RF-04      | O site deve exibir as tarefas importantes e cotidianas de forma organizada | Baixa      |
| RF-05      | O site deve permitir ao usuário adicionar resumos da matéria estudada de maneira digitada.                                 | Alta    |
| RF-06      | O site deve permitir ao usuário adicionar um resumo da matéria estudada a partir de um arquivo criado externamente                                 |  Média  | 
| RF-07      |O site deve permitir a sincronização da conta do usuário com contas de serviços externos. | Baixa      |
| RF-08      | O site deve exibir ao usuário mensagens a fim de motivar o usuário a concluir suas tarefas.                                | Baixa     |
| RF-09      |  O site deve permitir a criação de contas a partir de contas externas.                                 | Baixa  |
| RF-10      | O site deve notificar o usuário em relação aos horários em que ele deverá realizar alguma tarefa.                               | Baixa  | 

    2.2. Tecnologias

Descreva qual(is) tecnologias você vai usar para resolver o seu problema, ou seja implementar a sua solução. 
Liste todas as tecnologias envolvidas, linguagens a serem utilizadas, serviços web, frameworks, bibliotecas, 
IDEs de desenvolvimento, e ferramentas.  Apresente também uma figura explicando como as tecnologias estão 
relacionadas ou como uma interação do usuário com o sistema vai ser conduzida, por onde ela passa até 
retornar uma resposta ao usuário. 

    2.3. Serviços inteligentes

Descreva o mecanismo de inteligência que será utilizado no seu sistema. Utilize a modelagem baseada em agente
para definir as entradas e saídas do seu módulo de serviço inteligente. Apresente quem irá fornecer o serviço
e em que módulo será utilizado.

	
**3. Modelagem de dados**

Apresente o modelo de dados. Defina o dicionário de dados com os respectivos formatos e significados.

    3.1. Diagrama de Entidade-Relacionamento

Apresente a estrutura das tabelas de banco de dados no modelo Diagrama de Entidade-Relacionamento. 
A Seguir, segue um exemplo de imagem adicionada ao documento.

![Diagrama de Entidade Relacionamento de Exemplo](imagens/er_diagram.png "Diagrama de Entidade Relacionamento de Exemplo")

**4. Sistema desenvolvido**

Faça aqui uma breve descrição do software e coloque as principais telas com uma explicação de como usar cada uma.

**5. Avaliação**

Faça aqui sobre a avaliação do software. Indique se ele atendeu as expectativas e ele é viável. 
Para não ficar subjetivo, o ideal é fazer um questionário e pedir ao usuário do processo que faça a avaliação.

**6. Conclusão**

Apresente aqui a conclusão do seu trabalho. Discussão dos resultados obtidos no trabalho, onde se verifica as 
observações pessoais de cada aluno. Poderá também apresentar sugestões de novas linhas de estudo.  


**REFERÊNCIAS**


**[1.1]** - _Bakshy, E.; Messing, S.; Adamic, L. A. Exposure to ideologically diverse news and opinion on Facebook. Science. 2015.._

**[1.2]** - _Littlefield, A. Guia da metodologia ágil e scrum para iniciantes. 2016. Disponível em: https://blog.trello.com/br/scrum-metodologia-agil. Acessado em 26/05/2020.._

**[1.3]** - _Newman, N.; Fletcher, R.; Kalogeropoulos, A.; Nielsen; R. K. Reuters Institute Digital News Report 2019.  Reuters Institute for the Study of Journalism. 2019. Disponível em: https://reutersinstitute.politics.ox.ac.uk/sites/default/files/2019-06/DNR_2019_FINAL_0.pdf. Acessado em 26/05/2020._

**[1.4]** - _Vietro, I. L. Fluxo de desenvolvimento com GitFlow. 2015. Disponível em: https://imasters.com.br/agile/fluxo-de-desenvolvimento-com-gitflow. Acessado em 26/05/2020._
