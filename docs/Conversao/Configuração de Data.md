# Configuração de data inicial e final
![[ConfiguracaoData.png]]
É necessário selecionar uma data inicial e final na aba `Geral` da sessão `Configurações`. As conversões de [[Contas]] e [[Movimentos]] convertem apenas registros em um dado período de tempo devido ao alto volume de registros que normalmente essas entidades possuem.
>[!IMPORTANT]
>Como a aplicação do `SolNet_Conversao` é uma aplicação 32bits, selecionar um intervalo de datas muito grande pode causar um erro de `out of memory`, sempre tente converter intervalos curtos, ativando os botões de conversão (`Contas`, `Contas Pagar`, `Contas Receber`, `Pedido de venda`, etc) uma vez para cada intervalo. Sendo assim é necessário persistir registros entre conversões clicando em "Não" no dialogo de deleção ou marcando as opções de [[Confirmações]] `Conversão` ou `Nenhuma`.

## Ver Também
- [[Contas]]
- [[Movimentos]]
- [[Configuração Geral]]