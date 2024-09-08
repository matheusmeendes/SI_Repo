# Modelo de runbook do cutover - AWS

## Enunciado

Pesquise na Internet um exemplo de Plano de Cutover.
(1) Descreva a que projeto se refere e inclua seu link.
(2) Explique quais são seus principais elementos.
(3) Identifique e liste 3 pontos positivos e 3 pontos negativos deste plano.

## Respostas

1) Esse modelo de plano de cutover é fornecido pela AWS como um suporte de orientação para migrações para a nuvem AWS. O objetivo é auxiliar as equipes na criação de um runbook detalhado e planejado para a fase de cutover, que é o momento em que os sistemas são transferidos do ambiente antigo para o novo ambiente na AWS.

Link: https://docs.aws.amazon.com/pt_br/prescriptive-guidance/latest/cutover-runbook/cutover-runbook-template.html

2) Os principais elementos do plano incluem:

- Atividades: Lista de todas as tarefas a serem executadas durante o cutover, incluindo configuração de rede, migração de dados, testes, validação e ativação dos novos sistemas.
- Responsáveis: Identificação de quem é responsável por cada atividade, garantindo que todos saibam suas funções e responsabilidades.
- Cronograma: Definição de quando cada atividade deve começar e terminar, permitindo um controle do tempo e evitando atrasos.
- Comunicação: Plano de comunicação para manter todas as partes informadas sobre o progresso do cutover.
- Rollback: Procedimentos para reverter o cutover em caso de falhas ou problemas imprevistos, garantindo a continuidade dos negócios.

3) Aqui estão alguns pontos positivos e negativos que observei a respeito desse plano:

Pontos positivos incluem:
- Estrutura fácil: O modelo oferece uma estrutura bem organizada e fácil de seguir, facilitando a criação de um plano de cutover completo e eficaz.
- Abrangência: Cobre todas as etapas importantes do cutover, desde a preparação até a ativação e o rollback, garantindo que nada seja esquecido.
- Flexibilidade: Pode ser adaptado para diferentes tipos de migrações e projetos, permitindo que as equipes personalizem o plano de acordo com suas necessidades específicas.

Pontos negativos incluem:
- Complexidade: Para projetos grandes e complexos, o plano pode se tornar extenso e difícil de gerenciar, exigindo ferramentas e recursos adicionais para controle e acompanhamento.
- Especificidade da AWS: Embora seja flexível, o modelo é voltado para migrações para a AWS, podendo exigir adaptações para outros ambientes de nuvem ou migrações locais.
- Foco na execução: O modelo se concentra principalmente na fase de execução do cutover, podendo ser necessário complementar com outras ferramentas para planejamento e gerenciamento de riscos.

Dessa forma, o modelo de runbook do cutover fornecido pela AWS oferece uma estrutura bem legal para equipes que planejam migrar para a nuvem AWS. Sua estrutura clara, abrangência e flexibilidade facilitam a criação de um plano de cutover eficaz. No entanto, é importante estar atento à sua complexidade em projetos maiores, sua especificidade para a AWS e seu foco principal na execução, o que pode exigir ferramentas complementares para planejamento e gestão de riscos. No geral, o modelo serve como um bom ponto de partida, mas a adaptação e o planejamento ainda continuam sendo importantes para o sucesso do cutover.
