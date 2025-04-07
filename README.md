## Entidades:

- Produto (Atributos: Id, Nome, Quantidade Mínima, Data de cadastro, Data de atualização)
- Estoque (Id, ProdutoId, Tamanho, Valor de Custo, Cor, Tipo de Movimentação (Entrada/ Saída), Quantidade, Data do Cadastro, Data de Atualização)
- Venda (Id, ProdutoId, EstoqueId, Valor, Data da Venda, Data de Cadastro, Data de Atualização)
- Fornecedor (Id, Nome, Data de Cadastro, Data de Atualização)
- Ordem de compra (Id, ProdutoId, FornecedorId, IdExterno, Data da Compra, Data de Cadastro, Data de Atualização) 

## Casos de uso: 
- Definir Identificador unico para todos os registros
- Cadastrar/Editar Produto
- Definir quantidade mínima em estoque
- Receber alertas no sistema e pro e-mail para quantidade mínima em estoque
- Visualizar histórico de vendas
- Visualizar histórico de estoque
- Atribuir variações de cor para produto em estoque
- Relatório de vendas em determinado período agrupado por produto
- Em cada produto no relatório, mostrar margem de lucro
- Exibir indicador de dados de desempenho
- Mostrar tendências de vendas para compras de estoque
- Criar ordem de compra com base na quantidade de estoque e tendência de vendas
- Integrar ao sistema de fornecedores para rastreio de ordem de compras
