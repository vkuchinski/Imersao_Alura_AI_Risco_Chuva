
## Projeto/Desafio - Imersão Inteligência Artificial Alura 2a Edição: Análise de Risco de Chuva

### Resumo:

Este projeto utiliza o Google Earth Engine (GEE) e o Google Generative AI para realizar análises de risco de chuva com base no volume precipitado em uma área específica. O código interage com um modelo de linguagem para obter instruções e fornecer resultados de forma estruturada.
<br><br>
### Funcionalidades:
- Análise de Precipitação: Obtenha informações sobre a precipitação média em uma região para um período específico.
- Riscos envolvidos: Avalie o risco de inundação em uma área com base no volume precipitado.
- Orientações para a População: Receba orientações sobre como se proteger em caso de exposição ao perigo.
<br><br>

### Exemplo de Aplicação:

Um órgão público pode utilizar o projeto para monitorar áreas de risco de inundação e emitir alertas à população. 
Isso pode ajudar a prevenir perdas de vidas e danos materiais.
<br><br>

### Benefícios:

Dados Precisos e Atualizados: Utilize dados de precipitação em tempo real com alta resolução temporal e espacial.
Interpretação Facilitada: Obtenha resultados claros e concisos com a ajuda de um modelo de linguagem.
Fácil de Usar: Siga instruções simples para realizar análises e obter resultados.
<br><br>

### Importante:

Resultados para Fins Didáticos: Utilize os resultados apenas para fins didáticos e em hipótese alguma deve ser utilizado fora do contexto de aprendizagem desses sistemas.
Consulte Especialistas: Consulte órgãos oficiais e especialistas para obter informações precisas sobre riscos, como CEMADEN e INMET.
<br><br>

### Observação:

O código incluído no github não está renderizando o caderno com os blocos de codigo de maneira visual. Sugere-se que seja testado diretamente no Google Colab para visualização completa da análise. Acesse o código completo do projeto: https://colab.research.google.com/drive/1ICrT6S-Nda9lOfiC1HyQA5Oeyb0myR3u
<br><br>

### Exemplo:

#### Inputs solicitados pelo código:
- Cidade: Santa Maria
- Estado: RS
- Data: 30/04/2024

#### Outputs do código:
- Mapa da bacia hidrográfica do local informado
![Mapa da bacia hidrográfica](https://github.com/vkuchinski/Imersao_Alura_AI_Risco_Chuva/blob/main/bacia_hidrografica.png?raw=true)

- Mapa da precipitação na data informada
![Mapa de precipitação](https://github.com/vkuchinski/Imersao_Alura_AI_Risco_Chuva/blob/main/precipitacao.png?raw=true)

- Análise de risco
  
**Análise de risco devido a precipitação**

**Análise do Risco de Precipitação**

Local: Santa Maria, Rio Grande do Sul Data: 30/04/2024 Valor da Precipitação: 263,77 mm

**Análise Inicial**:

A precipitação registrada em Santa Maria em 30/04/2024 foi de 263,77 mm.
A média mensal de precipitação para abril em Santa Maria é de 150 mm.

**Análise do Risco**:

Nível de risco: Vermelho (Grande Perigo)
Ações que devem ser tomadas pela população:
Mantenha-se informado sobre as condições meteorológicas previstas e os possíveis riscos. Siga as instruções e conselhos das autoridades em todas as circunstâncias e prepare-se para medidas de emergência.

**Pessoas Afetadas:**

População de Santa Maria: 282.811 habitantes
Número estimado de pessoas possivelmente afetadas: 282.811 (toda a população da cidade)

**Observações:**

O nível de risco e as ações recomendadas podem variar dependendo das condições locais, como topografia, cobertura do solo e infraestrutura.
É importante seguir as orientações das autoridades locais e estar preparado para tomar medidas de emergência, como evacuar sua casa ou procurar abrigo, se necessário.
Importante!!
A presente análise não deve ser levado em conta por ninguém.

Esse código foi criado como parte de um desafio da Imersão de Inteligência Artificial da Alura.

Portanto, os resultados aqui apresentados não foram validados, servem apenas para fins didáticos.
