# LangChain-Arxiv-GPT
Em resumo, o LangChain nos permite conectar um modelo de linguagem grande como GPT-4 para nossas próprias fontes de dados.
 
Além disso, neste experimento há a tecnilogia LLM, que é baseada em algoritmos de aprendizado de máquina. Isso significa que ela utiliza técnicas estatísticas para analisar e aprender com grandes quantidades de dados de texto.

Os modelos de linguagem LLM funcionam por meio de um processo de geração de texto que envolve a escolha das palavras e frases mais prováveis com base no contexto e na informação disponível.

Aqui, a ideia é que a API referente ao acervo de arxiv seja consumida pelo modelo utilizado e retorne artigos científicos relevantes, assim como o título, resumo e data de publicação, com base na criatividade do agente autônomo.

Primeiro, é necessário definir as ferramentas que o modelo de liguagem LLM usará para fazer as procuras por artigos relevantes.


Inicializa-se o agente autônomo com base nas ferramentas definidas, o modelo LLM e o tipo de agente. 

Por fim, o usuário insere um input de texto ao agente, e o mesmo retorna artigos relevantes que torneiam os objetivos que foram propostos no input.
