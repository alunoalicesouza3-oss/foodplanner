# FoodPlanner — protótipo v3

Protótipo web responsivo para planejamento de refeições, controle de estoque e validade, receitas sugeridas e lista de compras.

## Como testar
1. Abra `index.html` em um navegador moderno.
2. Cadastre alimentos com quantidades e datas de validade.
3. Acesse Receitas e confira a compatibilidade com o estoque.
4. As receitas com maior compatibilidade aparecem primeiro; entre receitas com compatibilidade igual, são priorizadas aquelas que aproveitam alimentos próximos do vencimento.
5. Alimentos vencidos não são considerados disponíveis para receitas.

## Limitações desta versão
Os dados ficam no armazenamento local do navegador. Ainda não há autenticação real, banco de dados remoto ou sincronização entre dispositivos. As sugestões usam um catálogo demonstrativo de receitas e comparação aproximada por nome dos ingredientes.
