# Projeto CodeMaster DEV 2IF-DS

# Estado Inicial do projeto 💻

Recebi o HTML e CSS prontos. O layout renderiza perfeitamente, mas
o menu mobile não abre e o formulário recarrega a página.

_Lista de tarefas_

    [✅] 1. Menu Mobile

O código controla o menu do site. Quando o usuário clica no ícone do menu, ele abre ou fecha o menu adicionando e removendo classes. Quando o menu está aberto, o scroll da página é bloqueado. Se o usuário clicar em algum link do menu ou rolar a página, o menu fecha automaticamente e o scroll volta ao normal.

    [✅] 2. Navegação Ativa
O código seleciona todos os links do menu (.navlist a) e cria uma função que controla qual link fica ativo. Quando o usuário clica em um link, a classe active é removida de todos os links e adicionada apenas ao link clicado, deixando ele destacado no menu.

    [✅] 3. Alternar modo claro/escuro
O código cria um sistema para alternar entre modo claro e modo escuro no site. Quando a função toggleMode() é chamada, ela adiciona ou remove a classe light no HTML, mudando o tema. O tema escolhido é salvo no localStorage, para que quando o usuário abrir o site novamente, o modo selecionado continue ativo.

    [✅] 4. Animação do Título
O código cria uma animação no título "CODEMASTER", onde o texto aparece letra por letra e depois começa a apagar, repetindo esse efeito continuamente. Durante a animação, a cor do título alterna entre a cor padrão do tema (preto no modo claro ou branco no modo escuro) e laranja. Além disso, a função updateTextColor() ajusta a cor do texto de acordo com o tema claro ou escuro, e a animação começa quando a página termina de carregar.

    [✅] 5. Animação da Seção Home
O código aplica animações nas seções do site, deixando elas invisíveis no início e definindo uma transição suave. Dependendo da posição da seção, ela recebe um efeito diferente, como descer, diminuir de tamanho ou girar, criando uma animação quando aparecer na página.

    [✅] 6. Animação das Seções
O código cria animações nas seções do site quando o usuário rola a página. No início, todas as seções ficam invisíveis (opacity 0) e com transformações diferentes. Quando a seção aparece na tela, o IntersectionObserver detecta isso e faz a seção aparecer suavemente, voltando ao tamanho e posição normal.

    [✅] 7. Botão de voltar ao topo
O código cria um carrossel de slides no site. Ele controla qual slide está sendo exibido, permitindo avançar ou voltar usando botões. Também existe uma troca automática de slides, que reinicia quando o usuário interage. Além disso, quando o mouse passa sobre o carrossel, a troca automática pausa e volta a funcionar quando o mouse sai.