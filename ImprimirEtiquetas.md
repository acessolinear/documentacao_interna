## Imprimir Etiquetas

Caminho da tela no projeto (SGlinx > Forms > EtiquetaProduto.frm). Nas pasta está salvo em SGLinx\AlteracaoRestrita\Forms\Imprimir.frm
 ## Críticos
   - Para casos de etiqueta nutricional, verificar as informações extras que podem sair em até 7 ou até 13 linhas
     - Verificar o uso do X_CUSTOMIZAR(42) que permite configurar para estas linhas em 70 caracteres
   - Testar as etiquetas de gondola e produto se não foram impactados
   - Nào testar somente a opção que imprime digitando o código do produto, explorar as outras combinações que a tela permite, que listam no grid da tela.
   - Para casos em que se trata do preço do produto, alterar as opções da tela ao máximo possível variando os checkboxs.
     - Testar os preços com os rotinas que preenchem o grid da tela. Algumas delas gravam preços em colunas diferentes. o que na programação pode sofre impactos.
 ## Funcionamentos Gerais
   - Testar os checks do F6 que aparecem mais opções de filtros
