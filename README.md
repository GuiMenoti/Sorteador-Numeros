<h1>Treinamento de lógica de programação</h1>

<em>Funções utilizadas:</em>
<td>
<li>**Sortear:**<span>Esta função é chamada quando o usuário clica no botão para sortear números. Ela primeiro obtém os valores de entrada (quantidade, mínimo e máximo) do HTML. Em seguida, usa um loop para gerar números aleatórios dentro do intervalo especificado (de de a ate) e armazená-los em um array chamado sorteados. Antes de adicionar um número ao array, verifica se ele já foi sorteado anteriormente para evitar duplicatas. Finalmente, atualiza o elemento HTML com os números sorteados e chama a função alterarStatusBotao() para alterar o status do botão.</span></li>

<li>**Reiniciar**:<span>Esta função é chamada quando o usuário clica no botão para reiniciar. Ela simplesmente redefine os campos de entrada e o conteúdo do elemento HTML onde são mostrados os números sorteados. Em seguida, chama alterarStatusBotao() para ajustar o status do botão.</span></li>

<li>**alterarStatusBotao:**<span>Esta função é responsável por alterar a aparência do botão de reiniciar, habilitando ou desabilitando-o com base em sua classe. Se o botão estiver desabilitado (possui a classe container__botao-desabilitado), ele o habilita (removendo a classe desabilitada e adicionando a classe de estilo). Se estiver habilitado, ele faz o oposto. Isso ajuda a controlar quando o botão pode ser clicado pelo usuário.</span></li>

<li>**obterNumeroAleatorio:**<span>Esta função retorna um número aleatório inteiro dentro do intervalo especificado, incluindo os valores mínimos e máximos fornecidos como argumentos. Isso é feito usando Math.random() para gerar um número entre 0 e 1, que é então multiplicado pelo intervalo desejado e arredondado para o inteiro mais próximo usando Math.floor(). O resultado é um número aleatório dentro do intervalo fornecido.</span></li>

</td>