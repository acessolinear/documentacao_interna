# Gestão de Pedido de Venda

Caminho da tela no projeto (Sglinx > Forms > GestaoPedidoVenda.frm)
## Críticos
  - Para casos em que a gestão pedido gera separação no WMS. Com o parâmetro WMS_GESTAO_PEDIDOS_GERAR_SEPARACAO maior que zero configurado:
      - Verificar se a separação foi criada corretamente com os itens do pedido
      - Testar com pedido com item cancelado
      - Testar cenários em que o estoque não atende ao pedido e o ocorre o corte das quantidades, e se isso reflete corretamente na separação
  - Testar processando mais de um pedido juntos:
      - Nesses pedidos ter mais de 2 produtos
      - Cada produto variar as quantidades (não usar somente 1 como quantidade)
      - Forçar para ocorreo o corte das quantidades (quando pedimos mais do que o disponível no estoque)
  - Verificar a geração do Romaneio (quando ele ser aplicar)
  - Verificar a geração do pedido residual (quando ele se aplicar)
      - 
## Funcionamentos Gerais
  - 
