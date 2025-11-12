1. Dependendo do caso ela ficara do mesmo tamanho ou pode ficar uma unidade maior.A arvore continuará balanceada, pois uma AVL é feita para ter um mecanismo de autobalanceamento,
então se caso uma inserção ou remoção tire-a do estado balanceado, a arvore se balanceará sozinha.

2. Rotação a esquerda
    - Antes da rotação: 70(raiz), 80, 90 (todos filhos a direita)
    - Depois: 80(raiz), 70(filho esquerda), 90(filho direita).

   4.A busca em uma arvore AVL é sempre O(log n), enquanto uma arvore binaria de busca pode nos dar O(n) no pior caso.
O impacto do balanceamento no momento da incerção e remoção em uma AVL é que, assim como na busca, nos garante uma complexidade temporal de O(log n) no pior caso, o que a arvore binaria
comum não pode garantir.

   6.a) O fator de balanceamento é uma metrica usada para verificar se a arvore está equilibrada.

   b)  As quatro situações classicas de rotação são: rotação simples para a esquerda - essa situação acontece quando um nó pe inserido na subárvore direita da subárvore direita.
     Rotação simples para a direita - acontece quando um novo nó é incerido na subárvore esquerda da subárvore esquerda de um nó desbalanceado.
     Rotação dupla esquerda-direita - ocorre ao inserir um nó na subárvore direira da subárvore esquerda desbalanceando um nó acima dele.
     Rotação dupla direita-esquerda - acontece ao colocar um nó na subárvore esquerda da subárvore direita de um nó desbalanceado.
     
    c) Uma arvore AVL não pode ter um valor maior que 1 ou menor que -1, pois quando isso ocorre indica que ela esta desbalanceada e o sinal negativo ou positivo indica para qual lado.

   8.Será aplicada um arotação simples para direita.
     - Antes: PAI - A6(FB=+2), filho - A4(FB=+1), Novo nó esquerda de A4 - A2(FB=0)
     - Depois: Pai A4 - Filho esquerda A2 - Filho direita A6. 
