Gerenciador de Tarefas

Este projeto é um simples gerenciador de tarefas em JavaScript, que permite adicionar, visualizar, e remover tarefas de uma lista. As funcionalidades incluem a adição de novas tarefas com prioridade, exibição da tarefa mais antiga, exibição da primeira tarefa na lista, e remoção de tarefas com uma mensagem de conclusão detalhada.

Funcionalidades
1. Adicionar Tarefa (adicionarTarefa())
Permite ao usuário adicionar uma nova tarefa com uma descrição e prioridade.
A tarefa é registrada com a data e hora atuais.
A tarefa é inserida na lista de tarefas, e a interface é atualizada.
2. Remover Tarefa (resolverTarefa())
Remove a primeira tarefa da lista.
Exibe uma mensagem detalhada informando quanto tempo se passou desde que a tarefa foi adicionada até sua remoção.
Se a lista estiver vazia, uma mensagem de "Nenhuma tarefa para concluir" é exibida.
3. Mostrar Tarefa do Início (mostrarTarefaInicio())
Exibe a primeira tarefa da lista, mostrando sua descrição, prioridade, data e hora.
Se a lista estiver vazia, uma mensagem de "Lista Vazia" é exibida.
4. Mostrar Tarefa Mais Antiga (mostrarTarefaMaisAntiga())
Percorre a lista para encontrar e exibir a tarefa mais antiga com base na data e hora de criação.
Se a lista estiver vazia, uma mensagem de "Lista Vazia" é exibida.
5. Exibir Mensagem de Remoção (mostrarMensagemRemocao(tarefaRealizada))
Exibe uma mensagem detalhada sobre a tarefa que foi removida, incluindo o tempo decorrido desde sua criação.
A mensagem informa o tempo em dias e horas entre a adição da tarefa e sua conclusão.

Como Usar:

Adicionar Tarefa: Insira a descrição e a prioridade da tarefa nos campos de entrada e clique no botão "Adicionar".

Resolver Tarefa: Clique no botão "Resolver Tarefa" para remover a tarefa do início da lista.

Mostrar Tarefas: Use os botões "Mostrar Tarefa do Início" e "Mostrar Tarefa Mais Antiga" para visualizar informações específicas sobre as tarefas na lista.
