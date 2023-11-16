# Trabalahdno com Branches - Comandos úteis no Dia a Dia
Nessa aula, aprendemos alguns comandos essenciais do Git para gerenciar nosso repositório. Primeiro, usamos o comando `git fetch origin main` para baixar as alterações do branch remoto "main" para o nosso repositório local. Isso nos permite atualizar nosso código sem mesclá-lo automaticamente.

Em seguida, exploramos o comando `git diff main origin/main`, que nos ajuda a visualizar as diferenças entre o branch local "main" e o branch remoto "main" (origin/main). Essa é uma ferramenta valiosa para entender as alterações feitas por outros colaboradores.

Introduzimos também o `git stash`, uma maneira de armazenar temporariamente alterações locais. Isso é útil quando precisamos mudar de branch ou fazer outras alterações sem commitar as mudanças atuais.

Além disso, discutimos como recuperar as alterações armazenadas temporariamente. Tanto `git stash pop` quanto `git stash apply` são comandos que nos ajudam a aplicar essas alterações de volta ao código. A diferença principal é que o `pop` também remove a alteração da lista de stashes, enquanto o `apply` mantém a alteração lá, permitindo seu uso em diferentes partes do projeto.

Esses comandos são ferramentas poderosas para melhorar nosso fluxo de trabalho e colaboração no desenvolvimento de software usando o Git.

Simplificando:

-  **git fetch origin main:** Este comando baixa as alterações do branch remoto chamado "main" para o seu repositório local, mas não as mescla automaticamente com o seu branch atual.

- **git diff main origin/main:** O comando git diff compara as diferenças entre o branch local "main" e o branch remoto "main" (origin/main), mostrando as alterações feitas.

- **git stash:** Este comando é usado para armazenar temporariamente as alterações locais que você fez no seu código, permitindo que você mude de branch ou faça outras alterações sem commitar as mudanças atuais.

- **git stash pop:** Este comando aplica a última alteração armazenada temporariamente (stash) e a remove da lista de stashes. Ele é útil quando você deseja retomar as alterações que foram temporariamente armazenadas.

- **git stash apply:** Similar ao git stash pop, o git stash apply também aplica a última alteração armazenada, mas não a remove da lista de stashes. Isso permite que você aplique a mesma alteração em vários lugares, se necessário.
