# TesteGuruBank99
 Prática de casos de teste de um sistema bancário chamado GuruBank99, com duração de 13 dias (iniciado 27/03/2024) onde é recebido um e-mail a cada 24h com orientações para a elaboração de casos de teste do sistema citado.


 Projeto de teste manual desenvolvido pela Guru99 com duração de 13 dias, onde a cada 24h é recebido um e-mail com orientações sobre o desenvolvimento de um sistema bancário. Nesse projeto irei práticar a criação e execução de casos de testes funcionais.

O objetivo é por em prática os conhecimentos básicos que venho adquirindo no estudo de testes de software. 

Acredito que por essa prática possa ser possível não somente práticar, mas a desenvolver visão e pensamento de solucionadora de problemas e desenvolvimento de habilidade ágeis.

Este repositório será atualizado no decorrer da prática.

Dia 1 - A chegada do primeiro e-mail! Nele contém o SRS (Especificação de Requisitos de Software), onde foi o momento de conhecer o projeto, logo realizei a leitura, análise e busquei entender sobre as funcionalidades que estarão presentes no software. Após a leitura, o passo seguinte foi o inicio do planejamento de como os casos de testes e os testes serão efetuados, assim como caracteristicas e prioridades. 

Dia 2 - No segundo e-mail, continha suposições de uma situação real onde, mesmo com o documento SRS haveria algumas lacunas no entendimento aprofundado do projeto, que seriam discutidos em equipe. Desta forma, segundo essa situação hipotética ainda não seria possível elaborar os casos de testes. Após o exposto, foi encaminhado nesse e-mail documentos importantes que vão permitir o começo da criação dos CT's, sendo o primeiro documento um Mockup com algumas telas do projeto (o que já ajudou a entender muito mais sobre o projeto e funcionalidades a serem testadas) e uma FAQ com perguntas importantissímas que me fazem perceber a importancia de questionar sobre os detalhes, funcionalidades e etc de um sistema. A partir desse e-mail, é que a criação dos casos de teste começa a ser pensada, pois agora há base visual e requisitos técnicos que permitem e ajudam na criação dos casos de testes.
Nesse momento, busquei revisar as técnicas de caixa preta e selecionei em príncipio algumas para utilizar no projeto:
- Teste de valor limite
- Teste de particionamento de equivalência
- Teste de transição de estado
- Casos de uso

Dia 3 - O e-mail 3 é partido do pressuposto em que houve um reunião com a equipe de desenvolvimento, e nela é informado pela equipe que na primeira versão do site bancário, serão implementados os seguintes módulos:
Novo cliente
- Editar cliente
- Nova conta
- Editar conta
- Deletar conta
- Excluir cliente
- Minideclaração
- Declaração personalizada

Desta forma, agora é necessário a criação dos casos de teste para esses módulos.

Dia 4 - Após os casos de testes feitos, recebi o e-mail da equipe com o gabarito dos casos de testes dessas primeiras funcionalidades desenvolvidas. Esse momento foi indicado para analisar todos os casos de testes que havia feito e comparar com o gabarito da equipe, deixar tudo alinhado para no próximo dia iniciar a execução. No e-mail também foi recomendado leituras e busca de entendimento mais a fundo sobre teste de integração.

Dia 5 - Iniciada as excecuções dos testes! Recebi as instruções e link de acesso a primeira versão do sistema, desta forma pude iniciar as execuções dos testes e detalhar sobre resultados esperados, resultados obtidos e documentando sobre os bugs encontrados.

Dia 6 - No e-mail do dia 6, constava mais um 'gabarito' da execução dos testes feitos pelos especialistas. Muitos bugs foram encontrados, assim como foi percebido muitas falhas nos testes de integração, pois os módulos não foram integrados de maneira correta, o que fez com que o sistema perdesse muito de suas funcionalidades, desta forma assim que os bugs fossem corrigidos ao próximo dia um teste de sanidade será realizado para que verificar se os bugs foram corrigidos e se nenhum outro problema foi introduzido devido as alterações realizadas.
Outro ponto do dia 6 foi que o documento de especifições do software foi atualizado e com base nisso, a tarefa do dia foi criar casos de teste para uma nova funcionalidade criada: Consulta de saldo.

Dia 7 - Após a criação dos casos de teste para a nova funcionalidade, o e-mail do dia 7 continha o link da versão 2.0 do sistema, onde também foi relatado que os bugs haviam sido corrigidos e que agora seria necessário refazer a execução dos testes que haviam sido sinalizados com bugs. Após executar novamente os casos de teste, foi notado que os bugs mais criticos foram resolvidos. 

Dia 8 - Dia de conhecer as atualizações da versão 3.0 do sistema, logo, o novo documento de SRS versão 3 foi enviado para leitura, e também foi informado que novas funcionalidades para função gerente serão desenvolvidas assim como iniciará o desenvolvimento das funções de cliente. Desta forma foi dia que criar criar casos de teste para cada nova funcionalidade listada abaixo e realizar teste de integração entre os módulos já existentes, o que não foi de muito sucesso, pois alguns módulos ainda constavam com problemas de integração.

Função de gerente:
- Alterar a senha
- Depósito
- Cancelamento
- Transferência de fundos

Função do cliente:
- Consulta de saldo
- Transferência de fundos
- Minideclaração
- Declaração personalizada
- Alterar a senha

Dia 9 - No e-mail deste dia continha apenas aviso de que ao próximo dia a versão 3 do sistema estaria liberada. Logo, segui com a criação e adaptação dos casos de teste do dia 8.

Dia 10 - Chegada a Versão 3.0 para a realização dos testes, houveram novas alterações do documento SRS do projeto, entre as alterações foram inseridas instruções e documentação para realização de testes de API mais adiante, para testar se os parâmetros obrigatórios estão sendo respeitados. 
Além disso, como as funcionalidades para cliente estão sendo desenvolvidas, agora chegou o momento de criar as credenciais de cliente e seguir com as execuções dos testes.

Dia 11 -  Após a execução dos testes, houve o momento de reporte de bugs encontrados.
Nesse momento também já foi disponibilizado o novo SRS da versão 4.0 do sistema, com novas alterações.

Dia 12 - Versão 4.0 do sistema foi liberada! Dia de testar API (utilizarei o Postman) e executar novamente os casos de testes em que haviam reporte de bugs. 

Dia 13 - Após concluir a execução dos casos de testes com bugs, percebi que nem todos foram corrigidos, assim como os testes da API nem todos apresentaram o comportamento esperado. No entanto, concluo com êxito a execução desse projeto - mesmo que por certos momentos não pensei ser capaz de concluir esse desafio - e deixo registrado o quanto ele me agregou, me ensinou sobre uso de técnicas, me ajudou na prática me fazendo perceber e analisar como está minha base, como compreendo e aplico os conhecimentos fundamentais e básico de teste de software. 
Com certeza, foi um ganho incrível de conhecimento realizar esse desafio!





