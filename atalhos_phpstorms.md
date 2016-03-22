#Teclas de atalhos do PHPStorm com funções semelhantes ao Sublime Text, e outras interessantes.

Sublime Text   |PHPStorm |Função
---------------|---------|-------------
Ctrl+P         |Ctrl+Shift+O |Busca por arquivos no projeto
Ctrl+R         |Ctrl+F12 (1) |Lista os métodos da classe e outros símbolos
Ctrl+F         |Ctrl+F    |Busca no arquivo
Ctrl+Option+F  |Ctrl+R    |Busca e troca os valores no arquivo
Ctrl+Shift+F   |Ctrl+Shift+F|Busca, busca e troca e outros em um determinado caminho com várias regras.
Ctrl+D (2)     |Option+Up (2) | Seleciona palavra
Ctrl+D (3)     |Ctrl+G |Busca ocorrências da seleção no resto do arquivo
(4)            |Ctrl+Click ou Ctrl+B|Vai para a definição do símbolo
Ctrl+/         |Ctrl+/ (5) |Comenta linha
(4)            |Ctrl+Option+/ (6)|Comenta trecho de código
Ctrl+Ctrl+Up|Ctrl+Shift+Up (7)|Move linha pra cima
Ctrl+Ctrl+Down |Ctrl+Shift+Down (7)|Move linha para baixo
(4)            |Ctrl+Shift+__+__|Expande o conteúdo de todos os blocos do código
(4)            |Ctrl+Shift+__-__|Esconde o conteúdo de todos os blocos do código
(4)            |Ctrl+__+__|Expande o conteúdo do bloco onde o cursor está
(4)            |Ctrl+__-__|Esconde o conteúdo do bloco onde o cursor está
(4)            |Ctrl+O |Busca de classes PHP
(4)            |Ctrl+Shift+O |Busca de arquivos no projeto
Ctrl+Ctrl+Up e Ctrl+Ctrl+Down           |Option+Shift+Up e Option+Shift+Down |Move a linha livremente para cima ou para baixo (Diferente do Ctrl+Ctrl+Up/Down que move a linha formatando e também move blocos inteiros)
(4)            |Ctrl+Shift+Left/Right |Navega pelas abas para a esquerda e para a direita, mas sempre circular
Fn+Up/Down     |Fn+Up/Down           |Navega pelo arquivo mas ao invés de ir de linha em linha, move de 28 em 28 linhas
Ctrl+Up/Down   |Fn+Ctrl+Left/Right    |Navega para o início ou fim do arquivo
Shift+Ctrl+Up/Down   |Shift+Fn+Ctrl+Left/Right    |Navega para o início ou fim do arquivo, selecionando o conteúdo



*__Up__ = seta para cima / __Down__ = seta para baixo*

####Observações
*__(1)__: lembre-se que as teclas F1 à F12 no teclado da Apple, não são as funções primárias dos botões, então para usá-las, precisa da tecla __fn__. Exemplo: __fn+tecla de aumentar volume__ = __F12__*

*__(2)__: Aperte uma única vez, para selecionar a palavra onde encontra-se o cursor.*

*__(3)__: Com uma seleção, aperte repetidas vezes, e ele buscará a próxima ocorrência da seleção, selecionando e criando um cursor para cada seleção. Assim você pode editar em vários locais de uma vez só.*

*__(4)__: Não suporta ou suporta de maneira diferente.*

*__(5)__: Sem seleciona o texto/linha, ele adiciona e move o cursor para a próxima linha. Se fizer em uma linha que já tenha o comentário, ele remove e move o cursor para a próxima linha. Se fizer com algo selecionado, nem que seja um espaço em branco, ele comenta/descomenta sem mover o cursor para a próxima linha.*

*__(6)__: Faz comentário multilinha (/**/). Se um texto estiver selecionado, o comentário envolve o texto.*

*__(7)__: Se o cursor estiver na assinatura do método/função, moverá o bloco todo. Se estiver em outro local, moverá somente a linha onde está o cursor.*