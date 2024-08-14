Card de KPI Moderno para Power BI
Este repositório contém um exemplo de um card de KPI moderno, desenvolvido com HTML, CSS e JavaScript puro, para uso em Power BI. Este projeto permite exibir valores de KPI animados com uma barra de progresso dinâmica, verificando se a meta foi atingida e alterando a cor do card de acordo com o desempenho.

Autor
Nome: Reed Iury
LinkedIn: (https://www.linkedin.com/in/reediury/)

Instruções de Uso
1. Introdução
Este código HTML pode ser utilizado diretamente em um visual personalizado no Power BI. Ele foi projetado para ser um exemplo didático e impressionante de um card de KPI que pode ser facilmente integrado em seus relatórios.

2. Como Usar
Copie o código completo que está neste repositório.
No Power BI, ao inserir o código HTML no campo de texto do visual, substitua todas as aspas duplas (") por duas aspas duplas (""). Isso é necessário porque o Power BI utiliza aspas duplas para delimitar strings, e ao inserir código HTML com aspas duplas simples, o Power BI pode interpretar de forma incorreta o código, resultando em erros de renderização.

3. Explicação do Código
Variáveis Principais
valorFinal: Define o valor final do KPI que será exibido. Este é o valor que será animado até atingir o valor máximo desejado.

meta: Representa o valor da meta que deve ser alcançada. Se o valor final for maior ou igual a este valor, o card e a barra de progresso ficarão verdes; caso contrário, ficarão vermelhos.

incremento: Define o valor pelo qual o KPI será incrementado em cada passo da animação. Ele é calculado automaticamente com base na meta para criar uma animação suave.

intervalo: Determina o tempo em milissegundos entre cada incremento. Um valor menor resulta em uma animação mais rápida.

Funções Principais
atualizarKPI(): Esta função inicia a animação do KPI, aumentando o valor exibido progressivamente até atingir o valorFinal. Ela também ajusta a largura da barra de progresso em proporção ao valor atual.

formatarMoeda(valor): Formata um número para o formato de moeda brasileiro (R$), garantindo que o KPI seja exibido corretamente como um valor monetário.

verificarMeta(): Verifica se o valorFinal é maior ou igual à meta. Se for, aplica o estilo de sucesso (verde); caso contrário, aplica o estilo de alerta (vermelho).

4. Requisitos para Power BI
Quando você for inserir este código HTML no Power BI, lembre-se de substituir todas as aspas duplas (") por duas aspas duplas (""). Isso evita problemas de interpretação do código no contexto do Power BI.

5. Exemplo de Uso
Aqui está uma captura de tela de como o card de KPI aparecerá no Power BI após a implementação:
