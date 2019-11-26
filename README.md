# -hackathondecarreiras


###<div style="text-align: justify"> Este trabalho refere-se ao processo de seleção, segunda fase, para participação no Hackathon de Carreiras TI 2019 em atendimento ao quesito "Desafio Técnico". </div>
###Participante: Jairo Ataide (jairo@ataide.net)


#Desafio proposto
>**Desafio**
>
>Propor um processo de governança de ti
>
>**O problema**
>
>A empresa XY, importante player do mercado de transporte de mercadorias está iniciando o planejamento para um novo sistema de gestão integrada e, dadas as informações que os gestores receberam, o uso de computação em nuvem tem sido fortemente considerado.
>
>Entretanto, dada a tradição da empresa, em manter sua infra-estrutura e sistemas on-premisses, os gestores tem mostrado dúvidas e grandes receios quanto aos riscos que o uso de computação em nuvem pode trazer para a empresa. Questionam-se sobre o retorno sobre o investimento e, especialmente, mostram temores quanto ao compartilhamento indesejado de dados sensíveis com outras empresas ou pessoas.
>
>Por outro lado, apesar se acostumados e seguros com as iniciativas on-premisses, os gestores tem conhecimento de que a escalabilidade em nuvem maior.
>
>Como gestor de TI da XY, você deve propor um conjunto de processos, atividades e métricas a serem implementados, de maneira que as dificuldades apresentadas sejam minimizadas.
>
>1. Utilize os guias que considerar adequados para seu projeto.
>2. Priorize os processos, criando um caminho a ser seguido.
>3. Para cada processo, atividade ou métrica, apresente uma justificativa baseada nos guias explorados.
>4. Demonstre os efeitos que seu projeto pode gerar para a XY e seus gestores.
>5. Todos os artefatos desenvolvidos devem disponibilizadaos para análise técnica.
#Contexto
Toda e qualquer mudança em uma organização exige dos tomadores de decisão avaliar os impactos que podem ocorrer durante esse processo. Além da desconfiança, há os riscos inerentes que necessitam ser identificados e avaliados para que seja decidido qual melhor caminho seguir.

A migração de infraestruturas de TI *on-premise* para a nuvem levanta, por sua complexidade, uma série de incertezas em relação aos benefícios, riscos, desafios, segurança da informação e custos o que leva ao receio e hesitação por parte dos gestores corporativos.

Neste contexto este trabalho apresenta um modelo de fluxo de processo de avaliação de riscos tendo como guias a norma NBR ISO 31000 e o *framework* ITIL^®^  a partir da ponderação dos critérios de decisão e objetivos estratégicos, realizados a partir de análise multicritério.

Objetivos:
- Aumentar a probabilidade de acerto e acuracidade na tomada de decisão;
- Melhorar a identificação de oportunidades e ameaças;
- Melhorar a confiança das partes interessadas;
- Estabelecer uma base confiável de planejamento;
- Melhorar a eficácia e a eficiência operacional;
- Minimizar perdas.

Desta forma fornecer ao gestores da empresa XY, para que qualquer que seja a decisão entre a plataforma *on-premisses* ou *cloud*, estes tenham segurança na opção a ser adotada.


***

#Fluxo de processo de avaliação de riscos
##Processo de gestão de riscos
A norma NBR ISO/IEC 31000 define o processo de gestão de riscos como uma "aplicação sistemática de políticas, procedimentos e práticas de gestão para as atividades de comunicação, consulta, estabelecimento do contexto, e na identificação, análise, avaliação, tratamento, monitoramento e análise crítica dos riscos”. O principal objetivo é obter benefícios e valores sustentáveis para o negócio em cada uma de suas atividades. Uma estrutura de gerenciamento de risco deve fornecer uma diretriz abrangente para avaliar e gerenciar os riscos identificados.
![Imgur](https://i.imgur.com/ddqv3IG.png)
##Fluxograma de atividades do processo
A ferramenta segue o processo de avaliação de riscos da norma NBR ISO 31000, porém, é fundamental que seja realizada uma análise de contexto, conforme preconiza a norma, para que o processo aplicado na ferramenta seja o mais próximo da realidade organizacional. O fluxo abaixo apresenta o passo a passo das atividades de cada etapa a ser executada na ferramenta.
![](https://i.imgur.com/8Oxa18S.jpg)
###Critérios considerados no processo de tomada de decisão para migração em nuvem
Na definição dos indicares e métricas a serem consideradas, quando aplicáveis, aos critérios presentes na tabela abaixo devem ser abordados os processos que o *framework* ITIL® de melhores práticas de *Information Technology Service*:
<br>- ***Incident Management***: O propósito deste processo é o de restaurar o normalidade funcionamento dos serviços no mais curto espaço de tempo possível.
- ***Problem Management***: Neste processo a atenção centrasse em minimizar o impacto de incidentes que não podem ser prevenidos e prevenir a recorrência dos incidentes.
- ***Change Management***: Este processo tem a missão de gerir o ciclo de vida das alterações de uma maneira controlada, nomeadamente o registo, avaliação, autorização, priorização, planeamento, teste, implementação, documentação e revisão das mesmas.
- ***Release & Deployment Management***: Este processo tem como objetivo principal gerir todos os aspectos relacionados com a entrada em produção das várias *releases* dos serviços prestados pela organização, assim como o estabelecimento de um uso eficaz dos mesmos, cobrindo assim todas as fases de montagem e implementação do novo serviço, ou de um serviço alterado, desde o planeamento da *release* até ao suporte inicial no ambiente de produção.
<br>Outro aspécto a se abordar especificamente ao critério financeiro é adoção, **para ambas as opções**,  é análise de CAPEX e OPEX por meio do **TCO** (*Total Cost of Ownership*) ou custo total da posse, qué uma estimativa financeira projetada para avaliar os custos diretos e indiretos relacionados à compra de todo o investimento necessário além do gasto inerente de tais opções para mantê-las em funcionamento.
<br>Ainda relativo a questão financeira deve-se abordar método para cálculo de "Análise de Viabilidade Econômica Financeira" utilizando os parâmetros de VPL, TIRm, Payback descontado e ROI.

|Critério        	|Subcritério             	|
|:-----------------------:	|:-----------------------------------:	|
| **Ambiente organizacional** 	| Alinhamento às normas de SIC        	|
|                         	| Alinhamento estratégico com TIC     	|
|                         	| Envolvimento da alta direção        	|
| **Gestão de serviços**      	| Acordos de Níveis de Serviços (SLA) 	|
|                         	| Gestão contratual                   	|
|                         	| Gestão de capacidade                	|
| **Infraestrutura TIC**      	| Soluções de conectividade           	|
|                         	| Soluções de armazenamento           	|
|                         	| Soluções de processamento           	|
|                         	| Soluções de memória volátil         	|
|                         	| Elasticidade e escalabilidade       	|
| **Segurança da Informação** 	| Disponibilidade                     	|
|                         	| Integridade                         	|
|                         	| Confidencialidade                   	|
|                         	| Autenticidade                       	|
|** Financeiro/orçamentário** 	| Operacionalização                   	|
|                         	| Manutenção                          	|
|                         	| Orçamento                           	|
| **Governança**              	| Planejamento                        	|
|                         	| Política de recursos humanos        	|
|                         	| Gestão de mudanças                  	|
|                         	| Gestão de maturidade                	|****

<br/>
###Matriz de probabilidade X Impacto
A matriz de probabilidade e Impacto combina abordagens qualitativas ou semiquantitativas de consequências (impactos) e probabilidades, a fim de produzir um nível de risco
ou classificação de risco [14, 15].
Conforme é demonstrado na tabela 2.1, a matriz de probabilidade e impacto é fortemente aplicada na identificação e anális

####Definição da escala de Impacto
O impacto deve considerar os potenciais prejuízos causados, caso o incidente se concretize. Quanto maior a relevância do ativo, maior será a severidade de um incidente. A definição da escala de impacto deve ser elaborada a partir dos objetivos estratégicos alinhada a escala de impacto.
![](https://i.imgur.com/i2HnPoB.png)
####Definição da escala de Probabilidade
A probabilidade representa a possibilidade de que um determinado evento ocorrerá, ou a como a chance de uma ameaça se concretizar.

| Valor 	| Probabilidade 	| Descrição                              	|
|:-------:	|:---------------:	|:----------------------------------------:	|
| 1     	| Rara   	| Muito improvável de acontecer (1a 10%) 	|
| 2     	| Baixa         	| Improvável de ocorrer (11 a 30%)       	|
| 3     	| Média         	| Ocorre ocasionalmente (31 a 70%)       	|
| 4     	| Alta          	| Provável de ocorrer (71 a 90%)         	|
| 5     	| Quase certa    	| Ocorre frequentemente (91 a 100%)      	|

####Cálculo da matriz
Os quadrantes da matriz de riscos são resultantes do cálculo impacto x probabilidade.
<br/>Os eventos de riscos situados nos quadrantes definidos como risco alto e risco muito alto são indicativos de necessidade de controles mais rígidos, enquanto os riscos situados nos quadrantes de risco pequeno e moderado seriam um indicativo de controles mais moderados. Em alguns casos não há necessidade de implementar controles e/ou até retirar controles.
![](https://i.imgur.com/qVgQqCT.png)
####Nível de risco
O nível de risco expressa a magnitude de um determinado evento de risco, em termos da combinação de seu impacto e probabilidade de ocorrência.
<br/>- Nível de Risco Inerente (NRI): É o nível de risco antes da consideração das respostas para reduzir a probabilidade do evento ou os seus impactos nos objetivos, incluindo controles internos.
- Nível de Risco Residual (NRR): É o risco que ainda permanece depois de considerado o efeito das respostas adotadas pela gestão para reduzir a probabilidade e o impacto dos riscos, incluindo controles internos e outras ações.
<br/>Os níveis de riscos obtidos com aplicação desta matriz orientarão os gestores na adoção de ações para responder os eventos de riscos identificados.
![](https://i.imgur.com/EF1gKgn.png)
###Resposta ao risco
Após a etapa de avaliação de riscos, em que o risco é mensurado, o gestor deverá responder aos riscos. Esta fase é responsável por implementar ações orientadas pelo resultado da avaliação dos riscos.
<br/>Formas de resposta a riscos podem variar entre aceitar, reduzir, evitar ou compartilhar o risco, incluindo o estabelecimento de atividades de controle para assegurar que as respostas definidas sejam efetivamente aplicadas. É fundamental que o gestor considere o "apetite ao risco" quando propor as ações de controle em resposta aos riscos.

| Nível de Risco 	|                                              Parâmetro de análise<br>para adoção da resposta                                             	| Tipo de resposta 	|
|:--------------:	|:----------------------------------------------------------------------------------------------------------------------------------------:	|:----------------:	|
| RMA            	| A alta administração decide não realizar a atividade,<br>a fim de não envolver ou agir de forma a se retirar<br>de uma situação de risco 	| Evitar           	|
| RA             	| Implementa ações para reduzir a probabilidade, as<br>consequências negativas, ou ambas.                                                  	| Reduzir          	|
| RM             	| Compartilhar com outra entidade o ônus associado a<br>um risco                                                                           	| Transferir       	|
| RB             	| Assume as responsabilidade caso ocorra o risco<br>identificado.                                                                          	| Aceitar          	|
| RMB            	| Assume as responsabilidade caso ocorra o risco<br>identificado.                                                                          	| Aceitar          	|

#Metodologia de aplicação
Para aplicar a ferramenta proposta, indica-se o *framework* SCRUM Agile.
![Imgur](https://i.imgur.com/x6cYI99.jpg)

No caso o backlog de produto será composto pelos itens correspondentes da tebela de critérios.
<br><br><br>

***

#Referencias

ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **NBR ISO 31000: Gestão de riscos - Diretrizes**. Rio de Janeiro: ABNT, 2018. 17 p.

TI.EXAMES. Apostila do curso e-learning: **Fundamentos no gerenciamento de serviços de TI com base na ITIL®V3**. Disponível em: <http://www.tiexames.com.br/Amostra_Apostila_ITIL_V3_Foundation.pdf>

MENDONÇA, Tharcísio Queiroz. **Proposta de um instrumento de análise de riscos para auxiliar na tomada de decisão de migração de ambiente tradicional para Nuvem**. 2018.
