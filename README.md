# Projeto-Microsoft-Azure-Machine-Learning
# Meu primeiro projeto em Microsoft Azure Machine Learning

Olá! Me chamo Isac Freitas, e este é meu projeto trabalhando com Machine Learning na prática no Microsoft Azure ML.
Bom, para o projeto, foram dadas as instruções no curso de Microsoft Azure Ai Fundamentals pela plataforma DIO, com todos os dados para os alunos entregarem a atividade.

Foram compartilhados dois links (documentações de apoio): 
	https://aka.ms/ai900-auto-ml
	https://aka.ms/ai900-azure-ai-services

Aqui é uma espécie de "log" do que eu fiz.
--------------------------
Comecei criando uma assinatura (Azure Subscription 1) e um grupo de recursos, que chamei de "MachineLearning".
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/64cd7709-89f8-4adb-91a4-299ba313fffa" width="300px" />
</div>
Defini o nome do Workspace como "PraticaAi900", como região East US (serviços mais baratos), revisei e criei.

Então esperei a implantação finalizar.

Após concluída,

cliquei em "Ir para o recurso", e "Iniciar estúdio".

Com o Estúdio de Aprendizado de Máquina aberto,

cliquei em "ML automatizado" na seção criação.

Logo após, cliquei em "Novo trabalho de ML automatizado";

Nessa parte de Configurações Básicas, defini o nome do Trabalho como "mslearn-bike-automl", como foi indicado, e o nome do experimento e descrição conforme foi descrito.

Aprendizado de máquina automatizado para previsão de aluguel de bicicletas

Na caixa "selecionar tipo de tarefa", selecionei "Regressão" (prever valores numéricos contínuos).

Logo após, cliquei em criar, para criar um ativo de dados.

Na parte de criação de Ativo de Dados, dei o nome de "aluguel-de-bicicletas", descrição "Dados históricos de aluguéis de bicicletas", e tipo Tabular.

Avançando para a próxima etapa, escolhi a fonte "de arquivos da Web"

Aqui, informei o link que foi passado (https://aka.me/bike-rentals).

Na aba de configurações, informei o que foi passado na aula.

Nessa parte de "Esquema", não modifiquei nada.

Aqui, na última etapa, verifiquei se tinha escrito tudo corretamente e cliquei em Criar.

Selecionei o nosso ativo de dados.

Nessa parte de Configuração de Tarefas, na parte de Coluna de Destino, selecionei "rentals".

E, em "Exibir Definições de Configuração Adicionais", deixei assim:

Agora, voltando para a parte de Configurações de Tarefas, desci até a parte "Limites", e expandindo-o, preenchi da seguinte forma:

Agora, descendo mais um pouco, na caixinha de "Tipo de Validação", selecionei "Divisão de Validação de Treinamento", deixei no valor padrão (10), e na caixa de Dados de Teste, Deixei em "Nenhum".

Na parte de Computação, deixei tudo no padrão mesmo.

Ao finalizar, cliquei em "Enviar trabalho de treinamento".

Uns 15 minutos depois, terminou de fazer a validação.

Fui na aba de "Pontos de extremidade", para realizar os testes.

Então cliquei na aba "testar", e digitei o os seguintes comandos:

Logo após, cliquei em "Testar", e foi apresentado um erro:

Não sei o que houve, ou se fiz algo de errado. Então pesquisei na internet e não achei nada que servisse de solução para este problema.

Os resultados apresentados na documentação deveriam ser similares a estes:

Então é isso.

Este foi o meu primeiro projeto em Cloud e Machine Learning em meus estudos em Ciência de Dados.
