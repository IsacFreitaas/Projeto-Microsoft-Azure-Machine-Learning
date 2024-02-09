## Meu primeiro projeto em Microsoft Azure Machine Learning

Olá! Me chamo Isac Freitas, e este é meu projeto trabalhando com Machine Learning na prática no Microsoft Azure ML.

O projeto será usar ferramentas da Inteligência da Azure para prever aluguéis de bicicletas, para uma empresa.

Bom, para o projeto, foram dadas as instruções no curso de Microsoft Azure Ai Fundamentals pela plataforma DIO, com todos os dados para os alunos entregarem a atividade.

Foram compartilhados dois links (documentações de apoio):

1- https://aka.ms/ai900-auto-ml
2- https://aka.ms/ai900-azure-ai-services

Aqui é uma espécie de "log" do que eu fiz.
--------------------------
Comecei criando uma assinatura (Azure Subscription 1) e um grupo de recursos, que chamei de "MachineLearning".
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/64cd7709-89f8-4adb-91a4-299ba313fffa" width="900px" />
</div>

Defini o nome do Workspace como "PraticaAi900", como região East US (serviços mais baratos),
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/bb32efa5-246f-4b5f-8640-e3be49e29b6e" width="900px" />
</div>

revisei e criei.
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/78a83b6e-e4ef-4d2b-b4d6-ea3871be5f3a" width="900px" />
</div>

Então esperei a implantação finalizar.
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/ca868ad9-fc19-4fae-8c8a-b34905e4e51b" width="900px" />
</div>

--------------------------

Após concluída,
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/3586b35f-b8dc-4e07-aa1f-897b4d9599c8" width="900px" />
</div>

cliquei em "Ir para o recurso", e "Iniciar estúdio".
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/2d2739b4-6081-428d-889e-ab24f312afbd" width="900px" />
</div>

Com o Estúdio de Aprendizado de Máquina aberto,
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/921827a0-009a-42e4-8354-63c33b737233" width="900px" />
</div>
cliquei em "ML automatizado" na seção Criação.
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/f5b1df04-e2a3-402c-967d-4270ef898b34" width="900px" />
</div>
Logo após, cliquei em "Novo trabalho de ML automatizado";
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/d2d96933-c282-41b8-aba1-0ee352a22e16" width="900px" />
</div>

Nessa parte de Configurações Básicas, defini o nome do Trabalho como "mslearn-bike-automl", como foi indicado, e o nome do experimento e descrição conforme foi descrito.
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/0270e40c-b44c-43cf-b2f3-0bcebc68788c" width="900px" />
</div>

Na caixa "selecionar tipo de tarefa", selecionei "Regressão" (prever valores numéricos contínuos).
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/0c12a459-1ed1-4353-bddf-f058c4433d82" width="900px" />
</div>

Logo após, cliquei em criar, para criar um ativo de dados.
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/ecf99303-a644-4246-9922-83af7a905ef9" width="900px" />
</div>

Na parte de criação de Ativo de Dados, dei o nome de "aluguel-de-bicicletas", descrição "Dados históricos de aluguéis de bicicletas", e tipo Tabular.
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/98cd765f-bc60-4c67-8c49-0150c612d294" width="900px" />
</div>

Avançando para a próxima etapa, escolhi a fonte "de arquivos da Web"
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/64cb1f9a-a47a-4166-9a55-0c9aef47c736" width="900px" />
</div>

Aqui, informei o link que foi passado (https://aka.me/bike-rentals).
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/2c027f78-6962-46be-9005-c2f34cc730fb" width="900px" />
</div>

Na aba de configurações, informei o que foi passado na aula.
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/91dcbfb7-eb67-4527-a2f7-53ee028e744b" width="900px" />
</div>

Nessa parte de "Esquema", não modifiquei nada.
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/99bced3d-1072-48da-af4e-a8a2d29e622c" width="900px" />
</div>

Aqui, na última etapa, verifiquei se tinha escrito tudo corretamente e cliquei em Criar.
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/c39f80b1-fbd2-4749-b9ff-38bffeb1add4" width="900px" />
</div>

--------------------------

Então selecionei o nosso ativo de dados.
Nessa parte de Configuração de Tarefas, na parte de Coluna de Destino, selecionei "rentals".
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/f2c8de53-ebaf-4025-b2e6-c78ff42513a3" width="900px" />
</div>

E em "Exibir Definições de Configuração Adicionais", deixei assim:
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/c1c8bb5d-8d06-4ad6-a3a0-3727ced7dac4" width="900px" />
</div>

Agora, voltando para a parte de Configurações de Tarefas, desci até a parte "Limites", e expandindo-o, preenchi da seguinte forma:
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/b69d0f57-f03a-4e4a-90ff-b8b9edd267ed" width="900px" />
</div>

Agora, descendo mais um pouco, na caixinha de "Tipo de Validação", selecionei "Divisão de Validação de Treinamento", deixei no valor padrão (10), e na caixa de Dados de Teste, Deixei em "Nenhum".
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/2282a39f-1766-4871-9d9e-d4b5ce1441e3" width="900px" />
</div>

Na parte de Computação, deixei tudo no padrão mesmo.
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/54434326-59f7-44a7-a12c-65bf5577f173" width="900px" />
</div>

Ao finalizar, cliquei em "Enviar trabalho de treinamento".
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/c55d1728-acb5-4cde-ae76-c7983d661787" width="900px" />
</div>

--------------------------

Uns 15 minutos depois, terminou de fazer a validação.
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/b69752d7-0206-4edb-977e-d665e46d6b2a" width="900px" />
</div>

Fui na aba de "Pontos de extremidade", para realizar os testes.
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/99c35904-aedb-410c-b569-344b41e5a1e5" width="900px" />
</div>

Então cliquei na aba "testar", e digitei o os seguintes comandos:
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/c402054a-e96d-4563-abc9-5bf7599fc145" width="900px" />
</div>

Logo após, cliquei em "Testar", e foi apresentado um erro:
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/32149a35-aacd-4307-bd41-34bff34f4039" width="950px" />
</div>

Não sei o que houve, ou se fiz algo de errado.
Então pesquisei na internet e não achei nada que servisse de solução para este problema.
Os resultados apresentados na documentação deveriam ser similares a estes:
<div align="center">
<img src="https://github.com/IsacFreitaas/Projeto-Microsoft-Azure-Machine-Learning/assets/65254733/82005783-677e-4041-af9f-fcb0dee17a47" width="750px" />
</div>

--------------------------

Então é isso.

# Este foi o meu primeiro projeto em Cloud e Machine Learning em meus estudos em Ciência de Dados.

Obrigado pela atenção!

--------------------------

Sobre mim:
# Isac Freitas
Atualmente estudante de Ciência de Dados e Inteligência Artificial.

### Me encontre:

Insta: @isac.sfreitas
Twitter: @isaczeitgeist
