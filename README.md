<img alt="Linear Sistemas" src="https://linearsistemas.com.br/wp-content/uploads/2020/09/marca-Linear-768x301.png" />

<h3 align="center">
  Cheklist de Teste para os Desenvolvedores e Qualidade
</h3>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/rocketseat/bootcamp-gostack-desafios?color=%2304D361">

  <a href="https://www.linearsistemas.com.br">
    <img alt="Made by Linear Sistemas" src="https://img.shields.io/badge/made%20by-Linear%20Sistemas-red">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361">
</p>

<p align="center">
  <a href="#rocket-sobre-o-checklist">Sobre o Checklist</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-torre-4-produtos">Torre 4 Produtos</a>
</p>

## :rocket: Sobre o Checklist

O Checklists são documentos criados para auxiliar desenvolvedor e testers na etapa final do nosso processo de desenvolvimento, que consistem em validar e atestar a qualidade das aplicações e das entregas realizadas.
A qualidade de nossas ferramentas se inicia no teste final da realizados pelo desenvolvedor em usa tarega, na validação e homologação realizadas na Qualidade, assim como nas checagens finais das telas e rotinas na versão 
final. Em todos estes casos citados acima o checklist pode ser aplicado.
Como base seu objetivo é ter listado um conjunto de regras/cenários que serão usados no final do tabalho de cada um dos atores do nosso processo (desenvolvedor, tester, validador, homologador) visando verificar quais etapas
das listadas ainda não foram testadas.
O usuário destes documentos deve serguir o seu processo de teste normalmente como faz hoje. Ao final deve consultar estes checklist para ver o que esqueceu de fazer, ou mesmo já identifica o que foi realizado.
Não devemos de forma algum começar o nosso teste pelo checklist, seu objetivo e ser a prova final de nosso trabalho.

## :memo: Torre 4 Produtos

Checklist produzidos para a Torre dd Produtos. Abaixo listaremos as telas que já possuem a documentação implementada.

[Liberação Entrada Pendente](#liberação-entrada-pendente)</p>
[Relatório Curva ABC](#relatório-curva-abc)

## Liberação Entrada Pendente

Caminho da tela no projeto (SGlinx > Forms > LiberacaoEntradaPendente)
  ## Críticos
   - Liberar mais de uma nota ao mesmo tempo, sendo que cada nota possua vários produtos
   - Verificar a movimentação de estoque dos produtos testados
   - Testar nota com produto que tem desmembramento
   - Nota fiscal aparecer liberada no sistema
  ## Funcionamentos Gerais
   - Verificar a liberação de contas a pagar
   - Verificar se as notas e seus itens aparecem corretamento no Recebimento de Mercadoria e também do Via Cega
   - Verificar a geração do Acordo Comercial

## Relatório Curva ABC

Caminho da tela no projeto (LinearLibRelatorios > Forms > RelABCVenda)
  ## Testes para alteração no Form ou outros objetos do VB usandos na tela
   - Validar se os dados ou totalizadores do relatório testado batem com outro da mesma tela, usando os mesmo parâmetros
   - Quando o filtro de data é usado tentar mudar o período e selecionar maior do que o informado
   - Se os filtros apontandos no caso são de milti seleção, aumentar a quantidade de itens selecionados para ver se influencia no resultado
   - Comprar os resultados e totalizadores com os relatórios de Venda ECF
   - Variar pesquisando em mais de um filial
  ## Testes para Alteação no Report
   - 
