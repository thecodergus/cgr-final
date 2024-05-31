# Trabalho final de CGR
Uma simulação de tecido baseada em integração verlet.

Esta série de vídeos ajudou muito:
<https://youtu.be/3HjO_RGIjCU>

## Controles:

Segure o botão esquerdo do mouse para fazer uma das quatro coisas:

* Cortar bastões
* Mover pontos
* Colocar pontos
* Atrair pontos

Você pode escolher o que o botão esquerdo do mouse deve fazer alternando o modo correto:

* Pressione [C] para escolher o modo de corte
* Pressione [H] para escolher o modo de mão (mover pontos)
* Pressione [P] para escolher o modo de colocação
* Pressione [F] para escolher o modo de força

Um símbolo no canto superior esquerdo da tela mostrará em qual modo você está.
O ponto mais próximo do mouse será realçado.
Quando você usar o modo de mão, esse ponto começará a seguir o cursor (juntamente com todos os que estão conectados a ele).

Você pode usar o botão direito do mouse para conectar pontos
pressionando-o em um ponto e soltando-o no outro.

Teclas adicionais:

* [Q] para informações de depuração (se você se sentir inclinado)
* [A] para excluir todos os bastões
* [W] para excluir todos os pontos E bastões
* [S] para tornar um ponto estático
* [D] para reverter [S]
* E mais importante, **[G]** para gerar uma grade de pontos conectados que forma um tecido
* Também existe [T]. **Não pressione**. Ok, se você estiver se sentindo arriscado, recomendo experimentá-lo quando houverem cerca de 5 pontos na tela.

### Compilando

* Clone o repositório
* `cargo build --release`
* Opcionalmente, descomente as opções em Cargo.toml/profile.release para reduzir o tamanho do binário

*LMB = Botão esquerdo do mouse
*RMB = Botão direito do mouse
