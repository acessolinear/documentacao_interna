## Promoção Pague Menos

Caminho da tela no projeto (LinearComercial > Forms > CadPromocao2.frm)
## Críticos
  - Validar se o produto inserido na promoção já existe em outra nos mesmo período. Basta que um dia do intervalo coincida com o de outra promoção para que a validação sinalize que o produto existe na condição.
  - As validações de datas acima devem considerar também as promoções da tela Cadastro de Promoção de Produtos Geral, não só a da Pague Menos. Ambas devem funcionar com o mesmo critério
  - O produto não deve aparece duas vezes na mesma promoção como condição.
  - Se promoção cadastrada em 1 dia para ser iniciada no dia posterior, já realizar o cadastro da promoção como Ativo. Ex: Promoção cadastrada no dia 13/06 para iniciar dia 14/06, sistema já cadastrar a promoção como Ativa.
  - Complementar a tela existe a rotina de ativação de promoção na inicialização do sistema:
      - Nela deve ser considerar Data - 1, para que seja realizado a ativação da promoção. Ex: Promoção cadastrada no dia 13/06 para iniciar dia 14/06, sistema mudar essa promoção para ativa na inicializaçõa do dia 13/06.
  ## Funcionamentos Gerais
  - 
