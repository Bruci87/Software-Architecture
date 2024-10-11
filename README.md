1. Desvantagens de concentrar tudo em um único arquivo:
Dificuldade de Manutenção: Misturar lógica, interface e dados torna o código confuso e difícil de corrigir.
Pouca Reutilização: É difícil reaproveitar partes do código em outros projetos.
Escalabilidade Ruim: O arquivo fica muito grande e complicado à medida que o sistema cresce.
Testes Difíceis: Testar partes isoladas do código fica complicado.
Colaboração Ineficiente: Equipes grandes terão conflitos ao trabalhar no mesmo arquivo.
Dificuldade em Migrar Tecnologias: Separar a lógica de interface e dados se torna complicado se for necessário mudar alguma tecnologia.
2. Benefícios da separação em camadas:
Responsabilidade Separada: Facilita corrigir ou adicionar funcionalidades sem afetar outras partes.
Manutenção Mais Fácil: Código organizado por funções específicas facilita encontrar e corrigir problemas.
Reutilização: Componentes de uma camada podem ser usados em outros projetos.
Escalabilidade: Cada parte do sistema pode ser melhorada ou ampliada de forma independente.
Flexibilidade: Mudanças em uma camada não afetam as outras.
Facilidade para Testes: Testar partes específicas fica mais simples.
3. Benefícios da arquitetura Pipe e Filtros:
Modularidade: Cada etapa é independente, fácil de modificar ou adicionar novas.
Reutilização: Filtros podem ser usados em diferentes fluxos de dados.
Expansão Fácil: Novos filtros podem ser adicionados sem alterar o sistema todo.
Paralelismo: Filtros podem rodar de forma independente, melhorando a performance.
Flexibilidade: Filtros podem ser ajustados ou substituídos conforme necessário.
Manutenção Simples: Cada filtro faz uma tarefa específica, tornando a manutenção mais fácil.
