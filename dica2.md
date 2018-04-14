Dica 2

Git não pensa ou armazena sua informação dessa forma. Ao invés disso, o Git considera que os dados são um conjunto de snapshots (captura de algo em um determinado instante, como se fosse uma foto) de um mini-sistema de arquivos. Cada vez que você salva ou consolida (commit) o estado de seu projeto no Git, é como se ele tirasse uma foto de todos os seus arquivos naquele momento e armazenasse uma referência para esta captura. Para ser eficiente, se nenhum arquivo foi alterado, a informação não é armazenada novamente - apenas um link para o arquivo identico anterior que já foi armazenado. A figura 1-5 mostra melhor como o Git lida com seus dados.

Dica mais valiosa 
