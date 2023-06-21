## Imprimir Etiquetas

Caminho da tela no projeto (SGlinx > Forms > EtiquetaProduto.frm). Nas pasta está salvo em SGLinx\AlteracaoRestrita\Forms\Imprimir.frm
 ## Críticos
   - Para casos de etiqueta nutricional, verificar as informações extras que podem sair entre 1 e 7 ou entre 1 e 13 linhas
     - Verificar o uso do X_CUSTOMIZAR(42) que permite configurar para estas linhas em 70 caracteres, testar este necário
     - Testar a informações nutricionais e extras sem o X_CUSTOMIZAR(42) que terá 50 caracteres por linha.
   - Testar as etiquetas de gondola e produto para atestar se não foram impactados.
     - Com o F6, testar o checkbox de "Importar Itens NFE". Ele usa o grid de produtos de forma diferente de outros filtros da tela, e é importante ser sempre testado.
   - Não testar somente a opção que imprime digitando o código do produto, explorar as outras combinações que a tela permite e que listam no grid da tela por exemplo.
   - Para casos em que se trata do preço do produto, alterar as opções da tela ao máximo possível variando os checkboxs.
     - Testar os preços com os rotinas que preenchem o grid da tela. Algumas delas gravam preços em colunas diferentes. o que na programação pode sofrer impactos.
 ## Funcionamentos Gerais
   - Testar os checks do F6 que aparecem mais opções de filtros
