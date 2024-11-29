# Análise de Sentimentos em Feedbacks de Áudio
Este projeto utiliza tecnologias de Processamento de Linguagem Natural (PLN) para transcrever áudios e realizar análises de sentimentos. Foi desenvolvido como uma experiência prática para a aula de PLN, e ajuda a entender como ferramentas de transcrição e análise de sentimentos funcionam e podem ser aplicadas em feedbacks em audio.

## Descrição do Projeto
- **Objetivo**: Transcrever feedbacks em áudio e analisar os sentimentos expressos (positivos, negativos ou neutros).
- **Diferencial**: Os áudios utilizados foram uma combinação de gravações reais feitas com vozes familiares e áudios gerados por inteligência artificial, criando um cenário diversificado.

- **Desafios e Soluções**:
Inicialmente, o TextBlob apresentou dificuldade em classificar os sentimentos devido à falta de otimização para o português. Como solução, os textos foram traduzidos para o inglês, o que melhorou a precisão das predições.

## Tecnologias Utilizadas
- **Transcrição:** OpenAI Whisper. Responsável por transformar áudios em textos, funcionando bem para áudios com sotaques diversos e ruídos moderados.
- **Análise de Sentimentos:** TextBlob. Ferramenta simples e eficiente para análise de polaridade, utilizada em combinação com tradução para o inglês.
- **Tradução**: Googletrans. Usada para traduzir os textos transcritos do português para o inglês, otimizando a análise de sentimentos.


## Etapas do Projeto:
**1°** **Criação dos Áudios:**
10 feedbacks fictícios foram criados: 5 áudios gerados por inteligência artificial e 5 gravados manualmente.
Distribuição de sentimentos: 4 positivos, 4 negativos e 2 neutros.

**2°** **Transcrição dos Áudios:**
Usamos o OpenAI Whisper para transformar os áudios em texto, mesmo com variações de qualidade e ruídos.

**3°** **Análise de Sentimentos:**
Inicialmente com textos em português, os resultados foram insatisfatórios.
Após a tradução para inglês, o TextBlob conseguiu classificar corretamente os sentimentos.

**4°** **Visualização dos Resultados:**
Gráficos foram criados para mostrar a distribuição de sentimentos e polaridades dos feedbacks.
