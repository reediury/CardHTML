📊 Card de KPI Moderno para Power BI

Este repositório contém um exemplo de um card de KPI moderno, desenvolvido com HTML, CSS e JavaScript puro, para uso em Power BI. Este projeto permite exibir valores de KPI animados com uma barra de progresso dinâmica, verificando se a meta foi atingida e alterando a cor do card de acordo com o desempenho.

👤 Autor

Reed Iury 

LinkedIn: (https://www.linkedin.com/in/reediury/)

📦 Arquivos no Repositório

index.html: O código-fonte completo do card de KPI.

CARD_HTML.pbix: Arquivo Power BI de exemplo com o card aplicado.

🚀 Instruções de Uso

1. Introdução

Para utilizar este card de KPI em seu relatório do Power BI, será necessário o uso de um visual personalizado que suporte HTML. Neste exemplo, estamos utilizando o visual HTML Content.

2. Como Usar

Baixe e instale o visual HTML Content:

Você pode baixar pelo site (www.html-content.com) e siga as instruções para adicionar o visual personalizado ao Power BI, ou adicione o visual a partir da opção (Obter mais visuais) do Power BI.

O arquivo (CARD_HTML.pbix) contém um exemplo de relatório Power BI com o card de KPI já aplicado.

Utilize o código HTML:

Copie o código completo do arquivo index.html.

Ao inserir o código HTML no visual, substitua todas as aspas duplas (") por duas aspas duplas (""). Isso é necessário porque o Power BI utiliza aspas duplas para delimitar strings, e ao inserir código HTML com aspas duplas simples, o Power BI pode interpretar de forma incorreta o código, resultando em erros de renderização.

3. Explicação do Código

🛠 Variáveis Principais

valorFinal: Define o valor final do KPI que será exibido. Este é o valor que será animado até atingir o valor máximo desejado.

meta: Representa o valor da meta que deve ser alcançada. Se o valor final for maior ou igual a este valor, o card e a barra de progresso ficarão verdes; caso contrário, ficarão vermelhos.

incremento: Define o valor pelo qual o KPI será incrementado em cada passo da animação. Ele é calculado automaticamente com base na meta para criar uma animação suave.

intervalo: Determina o tempo em milissegundos entre cada incremento. Um valor menor resulta em uma animação mais rápida.

📜 Funções Principais

atualizarKPI(): Esta função inicia a animação do KPI, aumentando o valor exibido progressivamente até atingir o valorFinal. Ela também ajusta a largura da barra de progresso em proporção ao valor atual.

formatarMoeda(valor): Formata um número para o formato de moeda brasileiro (R$), garantindo que o KPI seja exibido corretamente como um valor monetário.

verificarMeta(): Verifica se o valorFinal é maior ou igual à meta. Se for, aplica o estilo de sucesso (verde); caso contrário, aplica o estilo de alerta (vermelho).
