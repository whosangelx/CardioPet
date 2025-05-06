# PLANO DE TRABALHO

| Nome do Projeto:       | CardioPet: Peitoral com tecnologia vestível para monitoramento de Sinais Cardíacos em pets |
| ---------------------- | --------------------------------- |
| Versão:                | 1.0                              |
| Status:                | Especificação             |
| Executor Principal:    | Chyntia Prestes, Gabriel Batista, João Vitor Oliveira, Luanna Benezar e Manole Braga    |
| Coordenador Principal: | Vandermi Silva                  |

---

# HISTÓRICO DE VERSÕES
| Versão | Descrição                              | Autor                          | Data       |
| ------ | -------------------------------------- | ------------------------------ | ---------- |
| 1.0    | Elaboração do Plano de Trabalho        | Chyntia Prestes, Gabriel Batista, João Vitor Oliveira, Luanna Benezar e Manole Braga | 23/04/2025 |
|     |  |  |
|     |                  |  |  |
|||||

---

# 1. INTRODUÇÃO
Atualmente, o cuidado com a saúde dos animais de estimação tem ganhado destaque, impulsionado pela maior conscientização dos tutores em relação ao bem-estar de seus pets. Apesar dos avanços na medicina veterinária, ainda se observa a dificuldade no monitoramento contínuo de sinais vitais durante atendimentos e acompanhamentos clínicos, principalmente em ambientes que exigem agilidade e precisão no diagnóstico. A ausência de métodos acessíveis e eficazes para a coleta de informações como a frequência cardíaca pode comprometer a identificação precoce de problemas de saúde e a adoção de intervenções adequadas.
Com isso, muitos profissionais e tutores enfrentam desafios na manutenção da saúde dos animais, sobretudo em situações que exigem acompanhamento em tempo real dos sinais vitais. A falta de ferramentas práticas e confiáveis no dia a dia da prática veterinária reforça a necessidade de soluções que integrem tecnologia, praticidade e segurança para otimizar o monitoramento da saúde animal.

## 1.1 Objeto
Desenvolver um peitoral com tecnologia vestível embarcada para monitoramento da frequência cardíaca de pets, visando auxiliar profissionais veterinários e tutores no acompanhamento em tempo real dos sinais vitais dos animais.

## 1.2 Motivação, Justificativa e Oportunidade
Para melhorar a segurança no atendimento veterinário na cidade de Itacoatiara, especialmente no acompanhamento de animais com doenças cardíacas (cardiopatias), torna-se necessária a introdução de tecnologias adequadas para o monitoramento da frequência cardíaca durante consultas clínicas. Atualmente, a ausência de dispositivos específicos nas clínicas compromete a avaliação precisa da saúde cardíaca dos pets, o que dificulta diagnósticos rápidos e seguros, mesmo em atendimentos rotineiros.
Diante desse cenário, o projeto propõe uma solução inovadora para o monitoramento cardíaco em pets, com foco em animais que necessitam de atenção especial devido a cardiopatias. A proposta visa reduzir riscos associados a atendimentos clínicos, além de promover maior segurança, eficiência e qualidade no acompanhamento veterinário local, contribuindo para a melhoria da saúde e do bem-estar animal.
  

## 1.3 Caracterização do Projeto
### 1.3.1 Classe
| Classe                 | Detalhamento                                                                                                                                 |
| ---------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| Sistema embarcado com aplicação mobile | O projeto será desenvolvido como um sistema embarcado utilizando a placa ESP32 integrada a um sensor de batimentos cardíacos. Os dados coletados serão transmitidos via Bluetooth para uma aplicação mobile simples, que exibirá em tempo real os batimentos cardíacos do animal. O sistema será implementado em um peitoral vestível, projetado para uso em pets, com foco em segurança, usabilidade e monitoramento eficiente. |

### 1.3.2 Enquadrabilidade

| Enquadrabilidade  | Detalhamento                                                                                                                |
| ----------------- | --------------------------------------------------------------------------------------------------------------------------- |
| Dispositivo de Monitoramento Veterinário | Está em conformidade com normas de biossegurança e regulamentações aplicáveis à área de saúde animal. Respeita os direitos de propriedade intelectual, privacidade de dados (quando aplicável) e adota medidas de segurança digital. |

### 1.3.3 Tipo
| Tipo                        | Detalhamento                                                                                                                                       |
| --------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| Documentação de hardware e software | Levantamento de requisitos, integração de sensores com a ESP32, programação do Bluetooth e criação de uma aplicação mobile para visualização dos dados em tempo real. |

# 2 INFORMAÇÕES GERAIS
O desenvolvimento de um peitoral com tecnologia vestível para monitoramento cardíaco de pets visa aprimorar o acompanhamento da saúde animal, oferecendo maior segurança durante procedimentos veterinários e no dia a dia dos tutores. O monitoramento de sinais vitais é essencial para a prevenção de complicações e para a realização de diagnósticos mais precisos. Assim, a utilização de um dispositivo estruturado com sistemas embarcados e comunicação mobile pode trazer benefícios significativos para a prática veterinária e para a qualidade de vida dos animais.

## 2.1 Objetivo
O principal objetivo é monitorar em tempo real a frequência cardíaca de pets por meio de um peitoral com tecnologia vestível, utilizando sistemas embarcados para garantir a coleta segura e contínua dos dados. Além disso, o dispositivo deve transmitir as informações via Bluetooth para uma aplicação mobile simples, permitindo que tutores e profissionais veterinários acompanhem de forma prática os sinais vitais dos animais, contribuindo para a prevenção de riscos e o suporte a diagnósticos mais precisos.

## 2.2 Escopo geral
O projeto envolve o desenvolvimento de um sistema de monitoramento vestível para pets, focado em funcionalidades essenciais para a coleta e transmissão de sinais cardíacos. Em primeiro lugar, a integração do sensor de batimentos cardíacos com a ESP32 para captação contínua dos dados e envio via Bluetooth. Em segundo lugar, o desenvolvimento de uma aplicação mobile que receba, interprete e exiba em tempo real as informações de frequência cardíaca de forma clara e acessível.
Ademais, o sistema permitirá o registro básico dos sinais captados, auxiliando no acompanhamento da saúde do animal ao longo do tempo. Além disso, será priorizada a segurança dos dados transmitidos, alinhando o projeto às boas práticas de proteção da informação e respeitando normas de saúde animal.

### 2.2.1 Escopo Específico
- Inicialmente, será realizada a integração do sensor de batimentos cardíacos com a placa ESP32, permitindo a captação precisa dos sinais vitais do animal. A ESP32 será programada para realizar a leitura contínua dos dados do sensor e estabelecer a comunicação via Bluetooth, garantindo que as informações possam ser transmitidas em tempo real para dispositivos móveis.
- Em seguida, será desenvolvido um aplicativo mobile simples, que permitirá a conexão direta com a ESP32 para a recepção dos dados de batimentos cardíacos. O aplicativo exibirá a frequência cardíaca de maneira numérica e gráfica, oferecendo uma visualização clara e rápida para tutores e profissionais veterinários. A interface será desenhada para ser intuitiva e de fácil uso, sem a necessidade de conexão com a internet.
- O projeto também contempla a construção de um peitoral vestível que acomode os componentes eletrônicos de forma confortável e segura para o animal. O design do peitoral será ajustável para atender diferentes portes de pets, garantindo que o sensor permaneça corretamente posicionado para a captação eficaz dos sinais cardíacos, sem causar desconforto.
- Para a alimentação do sistema, será utilizada uma bateria portátil, como uma bateria recarregável compacta ou um pequeno powerbank, garantindo autonomia adequada e mobilidade do equipamento. O suporte aos componentes eletrônicos será planejado de forma que permita a fácil remoção para manutenção ou recarga da bateria, aumentando a praticidade e a vida útil do dispositivo.
- Por fim, serão realizados testes de funcionamento do sistema em ambiente controlado, verificando a estabilidade da comunicação Bluetooth, a precisão na leitura dos batimentos cardíacos e a usabilidade do aplicativo. Será produzida também a documentação técnica detalhada sobre o hardware e software desenvolvidos, assegurando a reprodutibilidade e a futura manutenção do projeto.


### 2.2.2 Escopo Negativo
- O projeto não abrange o desenvolvimento de funcionalidades para análise clínica automática dos dados captados, como diagnóstico de doenças ou interpretação médica dos batimentos cardíacos, limitando-se apenas à exibição dos sinais vitais em tempo real. Também não será implementada qualquer funcionalidade de alerta inteligente ou sistema de notificação automática para situações de emergência baseadas nos dados coletados.
- O sistema não utilizará conexão Wi-Fi, nem transmitirá dados para servidores remotos ou bancos de dados na nuvem, restringindo-se à comunicação via Bluetooth entre a ESP32 e o aplicativo mobile. Não haverá integração com plataformas de monitoramento remoto, nem com sistemas veterinários já existentes. O projeto se concentrará exclusivamente na comunicação local e na visualização imediata dos dados.
- Além disso, não será desenvolvido um sistema de histórico completo para acompanhamento longitudinal dos dados cardíacos, nem uma base de dados para arquivamento prolongado das informações. As leituras serão exibidas de forma instantânea, sem armazenamento interno avançado.
- O projeto também não contemplará um sistema de recarga automática de energia, gestão inteligente da bateria ou otimização avançada de consumo energético, sendo o carregamento realizado manualmente pelos usuários, através de bateria externa ou fonte de energia via USB.
- Funcionalidades de geolocalização, rastreamento de movimentação do pet ou integração com redes sociais não serão incluídas. Também não haverá suporte para múltiplas línguas, limitações de acessibilidade específicas ou customizações individuais da interface do aplicativo mobile nesta versão inicial. Melhorias nesse sentido poderão ser consideradas para versões futuras do projeto.

## 2.3 Ambiente de Desenvolvimento
### Ferramentas e Tecnologias
| Tipo                                        | Modelo e Especificações     |
| ------------------------------------------- | --------------------------- |
| Repositório Online   | GitHub                      |
| Editor de Código Mobile                       | Visual Studio Code com extensões para Flutter/Dart ou React Native                       |
| Editor de código embarcado | Arduino IDE    |
| Linguagem de Programação Embarcada                    | C++  |
| Linguagem de Programação Mobile                       | Dart(Flutter) ou JavaScript (React Native)     |
| Modelagem de Protótipo                                | Figma      |
| Modelagem de fluxogramas                              | Draw.io           |
| Comunicação sem Fio                                   | Bluetooth Low Energy (BLE)           |
| Plataforma de desenvolvimento mobile                  | Expo Go                   |

## 2.4 Características Inovadoras do Projeto
- Utilizar tecnologia vestível adaptada a pets para monitoramento contínuo da frequência cardíaca;
- Integrar sensores de sinais vitais a um peitoral confortável e ajustável para diferentes tamanhos de animais;
- Realizar a transmissão dos dados de batimentos cardíacos em tempo real via Bluetooth;
- Permitir o acompanhamento instantâneo dos sinais cardíacos através de um aplicativo mobile simples e acessível;
- Promover o monitoramento de saúde animal de forma portátil, sem necessidade de conexão à internet;
- Possibilitar a remoção prática dos componentes eletrônicos para manutenção e higienização do peitoral. 

## 2.5 Resultados Esperados
- Permitir o monitoramento da frequência cardíaca de pets em tempo real com segurança e praticidade;
- Auxiliar tutores e profissionais veterinários na identificação precoce de alterações cardíacas;
- Reduzir riscos durante procedimentos clínicos e atividades físicas dos animais;
- Facilitar a coleta de informações vitais sem a necessidade de equipamentos hospitalares complexos;
- Contribuir para a inovação no cuidado preventivo da saúde animal;
- Estimular o desenvolvimento de soluções tecnológicas voltadas ao bem-estar de pets.

# 3 METODOLOGIA DE PROJETO
## 3.1 Estrutura do Projeto
- PO – Product Owner
- Scrum Master
- Squad: Avaliador de inspeção, modelador, analista de requisitos e designer UX/UI

## 3.2 Equipe de Projeto: Papéis e Responsabilidades dos integrantes
| Responsabilidade        | Profissional                   |
| ----------------------- | ------------------------------ |
| Scrum Master            | João Vitor O. |
| Avaliador de inspeção | Chyntia Prestes    |
| Desenvolvedor embarcado (ESP32)  | Luanna Benezar |
| Desenvolvedor mobile (App)       | Gabriel Batista    |
| Prototipação    | Chyntia Prestes  |
| Analista de requisitos       | João Vitor O.    |
| Modelador                    | Manoele Braga |

## 3.3 Fases, Atividades e Cronograma
- **Fase I: Especificação e Planejamento – Abril:**
  - Planejamento inicial.
  - Levantamento de requisitos do sistema.
  - Desenvolvimento de Personas.
  - Trabalhar histórias do usuário e seus critérios de aceitação, regras de negócios e requisitos não funcionais.

- **Fase II: Desenvolvimento Parcial – Maio/Junho:**
  - Início da implementação prática: programação da ESP32 para captação de sinais cardíacos.
  - Configuração da comunicação Bluetooth.
  - Desenvolvimento inicial do aplicativo mobile e primeiros testes de integração.

- **Fase III: Finalização do Projeto – Junho/Julho:**
  - Conclusão da integração entre o hardware (ESP32 + sensor + peitoral) e o aplicativo mobile.
  - Testes finais de funcionamento.
  - Ajustes de protótipo.
  - Refinamento da interface do app e entrega final da implementação funcional.

## 3.4 Entregas de cada Fase
| Fase                           | Mês               | Entregável                                                                            |
| ------------------------------ | ----------------- | ------------------------------------------------------------------------------------- |
| I. Especificação e Planejamento               | 29/04 | Personas, Histórias do Usuários e Requisitos do sistema.                              |
| II. Desenvolvimento Parcial                   | 10/06       | Programação da ESP32 e sensor funcionando, estrutura inicial do aplicativo mobile, testes de comunicação. |
| III. Implementação Final     | 10/07        | Sistema completo integrado (hardware + app), testes finais de funcionamento e documentação técnica final. |

## 3.5 Controle de Mudanças
O monitoramento e controle do escopo do projeto serão realizados a partir das seguintes diretrizes:

- Requisitos do projeto devem ser compreendidos por todos os membros da equipe.
- Todas as questões técnicas, de entregas e do cronograma que a equipe do projeto possui devem ser respondidas.
- Todas as entregas devem ser acordadas pela equipe do projeto e entidades parceiras.
- Todas as informações devem estar atualizadas no escopo e não-escopo.
- Nenhum trabalho fora do escopo do projeto deve ser feito.
- Solicitações de mudança no escopo do projeto devem ser efetivamente comunicadas e compreendidas.
