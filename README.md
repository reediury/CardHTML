📊 Card de KPI para Power BI
=

Este repositório contém um exemplo de um card de KPI desenvolvido com HTML, CSS e JavaScript puro. O card exibe valores de KPI com uma animação e barra de progresso, mudando a cor conforme a meta é atingida.

👤 Autor
=

Nome: Reed Iury

LinkedIn: (https://www.linkedin.com/in/reediury/)

📦 Arquivos
=

index.html: Código-fonte completo do card de KPI.

CARD_HTML.pbix: Exemplo de relatório Power BI com o card aplicado.

🚀 Instruções de Uso
=
Visual Personalizado:

Para usar este card no Power BI, é necessário um visual que suporte HTML. Recomendo o HTML Content, que pode ser baixado e instalado através do site (https://www.html-content.com/) ou pela opção "Obter mais visuais" no Power BI.

Inserção do Código:

Copie o código do index.html.
Ao inserir o código no visual HTML, substitua todas as aspas duplas (") por duas aspas duplas (""). Isso é necessário para evitar erros de interpretação no Power BI.

Arquivo de Exemplo:

O arquivo CARD_HTML.pbix contém um exemplo de como o card de KPI é exibido em um relatório Power BI.


🛠 Variáveis Principais
=

valorFinal: Valor final do KPI, exibido e animado.

meta: Meta a ser alcançada; o card e a barra de progresso mudam de cor com base na meta atingida.

incremento: Valor adicionado a cada passo da animação.

intervalo: Tempo (em milissegundos) entre os incrementos da animação.


📜 Funções Principais
=
atualizarKPI(): Anima o valor do KPI e ajusta a barra de progresso.

formatarMoeda(valor): Formata o valor como moeda brasileira (R$).

verificarMeta(): Ajusta a cor do card e da barra de progresso com base na meta.

Card
=

https://github.com/user-attachments/assets/7259e6f5-cced-4306-8760-4c5167268312

Se tiver dúvidas ou sugestões, entre em contato comigo pelo LinkedIn.
