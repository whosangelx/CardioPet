# Relatório da Inspeção dos Requisitos
- A inspeção foi conduzida por dois inspetores, identificados como Inspetor A e Inspetor G. Cada um deles elaborou, de forma independente, uma tabela categorizando os defeitos encontrados nos requisitos. Após concluírem suas análises individuais, os inspetores reuniram-se para comparar e discutir suas tabelas. Com base nessa discussão, realizaram uma consolidação das informações, elaborando uma única tabela unificada. Nessa tabela final, foram registrados os defeitos considerados reais, ou seja, aqueles que ambos concordaram que deveriam ser corrigidos.

  ### Tabela de consolidação


  | ID     | User Story |  Localização                    |  ID-Defeito |  Descrição| Sugestão |  
  |----------|------------|---------------------------------------------------------------|------------|------------|------------|
  | 1 | H1| Título | 2 | Ao final a história define tal funcionalidade como "rapida" e "eficiente"|  Reavaliar.|
  | 2 | H1|  C2 | 2  | Ao final do critério "... em gráfico de fácil leitura." pode ser interpretado de diferentes formas|  Especificar o tipo de grafico que o sistema utilizará|
  | 3 | H2|  Título| 1 e 2|  O uso de adjetivos como "estável" e "contínua" intenciona um bom estabelecimento de conexão, entretanto precisa ser especificado|Reavaliar e Especificar o uso de conexão Bluetooth|
  | 4 | H2|  C3 | 1    | É importante identificar o que são tais interrupções e por quantos segundos o sistema estará recebendo ela. Importante entender mensuração dessas interrupções | Reavaliar e Especificar cenário do problema|
  | 5 | H3|  Título | 2    | Uso de adjetivos em "... com informações claras, ícones intuitivos e números bem visíveis" é ambiguo.|  Reavaliar|
  | 6 | H3|  C1 | 2   |  Uso de adjetivo em "... com fonte grande..." é ambiguo.|Especificar o tamanho da fonte|
  | 7 | H3|  RN2 | 3   | Tal regra soa como um critério de aceitação|Reavaliar|
  | 8 | H3|   RN1 | 3| Regra de negocio inconsistente com a historia apresentada| Mover para a H2 pois diz respeito ao comportamento da conexão do sistema|
  | 9 | H4  |  Título    | 1 | Em "... dispositivo tenha autonomia de bateria suficiente para funcionar... evitando a necessidade de recargas frequentes" é interessante avaliar que dispositivo é esse.     | Informar o tipo de bateria que será utilizada no sistema      |
  | 10 | H5  |  Título         | 1 |  Em "... que o peitoral seja confortável e seguro, ..." é interessante avaliar em qual material será feito esse peitorial.     | Informar o material necessario priorizando o conforto do pet      |
  | 11  | H5  |   C1         | 2  | O critério é ambiguo     |Reavaliar a descrição de período de consulta destacando a boa  usabilidade do peitoral      |
  | 12  | H6  |  Toda a história   | 3 e 5 |  Há semelhanças com a H1, especificações redundantes     |Reavaliar requisistos de uso para o usuario Tutor      |
  | 13  | H6  |  Título         | 2 | A parte "momentos específicos em casa" é vaga. Pode gerar interpretações diversas sobre o que seria considerado "específico" ou em que contexto os batimentos cardíacos devem ser monitorados.    |      |
  | 14  | H6  |   C1         | 2 |  No critério de aceitação "gráfico simples", é vago e pode ser interpretado de diversas maneiras.     |      |
  | 15  | H7  |   Título        | 1 |  Em "... dispositivo seja fácil de colocar e retirar do meu animal, ..." é interessante especificar o material |Reavaliar e descrever o material que será utilizado |
  | 16  | H7  |   C1        | 2 e 5 |  No critério de aceitação "2 minutos sem necessidade de ferramentas", é vaga essa parte de "ferramentas".    |      |
  | 17  | H8  |   Título        | 2 | Em "... para que eu consiga usar o monitoramento em qualquer lugar... " é ambiguo. Há semelhanças com a H2 por serem sobre a conexão.    |Reavaliar e organizar as histórias citadas, para não perder informações importantes sobre conexão e uso para ambos usuarios      |
  | 18  | H9  |    C1        | 3  | Em "... deve suportar no mínimo 6 horas..." é conflitante com o C1 da H4 que diz "... garantir autonomia de no mínimo 2 horas..."    |Reavaliar      |
  | 19  | H9  |   Título        | 2  | A expressão "bastante tempo" é vaga e pode ser interpretada de diferentes maneiras.     |      |
