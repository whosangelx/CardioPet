# PLANO DE TRABALHO

| Nome do Projeto:       | CardioPet: Peitoral com tecnologia vestível para monitoramento de Sinais Cardíacos em pets |
| ---------------------- | --------------------------------- |
| Versão:                | 1.1                              |
| Status:                | Implementação             |
| Executor Principal:    | Chyntia Prestes, Gabriel Batista, João Vitor Oliveira, Luanna Benezar e Manole Braga    |
| Coordenador Principal: | Vandermi Silva                  |

---

# HISTÓRICO DE VERSÕES
| Versão | Descrição                              | Autor                          | Data       |
| ------ | -------------------------------------- | ------------------------------ | ---------- |
| 0.1    |Elaboração da proposta inicial do sistema embarcado CardioPet: definição do problema, objetivos do projeto e identificação preliminar de necessidades      | Chyntia F Prestes, Gabriel Batista, João Vitor Oliveira, Luanna Benezar, Manoele Braga. | 23/03/2025 |
| 0.2   |Elaboração do Plano de Trabalho: definição de cronograma, divisão de tarefas e metodologia de desenvolvimento.| Chyntia F Prestes, Gabriel Batista, João Vitor Oliveira, Luanna Benezar, Manoele Braga. | 23/03/2025 |
| 0.3    |Criação de duas personas para definição do perfil dos usuários finais (ex.: veterinários e tutores de pets), visando guiar as decisões de requisitos e funcionalidades.| Chyntia F Prestes, Gabriel Batista, João Vitor Oliveira, Luanna Benezar, Manoele Braga. | 24/04/2025 |
| 0.4    |Definição dos Requisitos Funcionais: funcionalidades principais como monitoramento cardíaco, geração de alertas e armazenamento de dados.|  Chyntia Prestes, João Vitor Oliveira.| 26/04/2025 |
| 0.5    |Definição dos Requisitos Não Funcionais: desempenho, autonomia de bateria, conectividade e  robustez.|  Chyntia Prestes, João Vitor Oliveira.| 26/04/2025 |
| 0.6    |Definição das Regras de Negócio: parâmetros clínicos, limites de alerta, periodicidade de coleta dos sinais, políticas de armazenamento e envio de dados.|  Chyntia Prestes, João Vitor Oliveira.| 27/04/2025|
| 0.7   |Definição dos sensores e componentes: escolha de sensores de frequência cardíaca, microcontroladores (ESP32), módulos Bluetooth, fonte de alimentação, etc.|  Chyntia Prestes, João Vitor Oliveira.| 27/04/2025|
| 0.8    |Definição da Arquitetura do Sistema: elaboração de diagramas de blocos, fluxogramas de dados, comunicação entre módulos e integração dos sensores com o microcontrolador.|Manoele Braga, Gabriel Batista.| 05/05/2025|
| 0.9    |Alteração de Escopo: Decisão de não desenvolver o aplicativo mobile. O projeto passa a focar exclusivamente no sistema embarcado com funcionalidades locais.|Chyntia Prestes, João Vitor Oliveira.| 28/05/2025|
| 1.0    |Elaboração Física do Projeto: montagem do protótipo, integração dos sensores com o microcontrolador, desenvolvimento de software embarcado e realização de testes iniciais.|Chyntia Prestes, João Vitor Oliveira.| 12/06/2025|





---

# 1. INTRODUÇÃO
Atualmente, o cuidado com a saúde dos animais de estimação tem ganhado destaque, impulsionado pela maior conscientização dos tutores em relação ao bem-estar de seus pets. Apesar dos avanços na medicina veterinária, ainda se observa a dificuldade no monitoramento contínuo de sinais vitais durante atendimentos e acompanhamentos clínicos, principalmente em ambientes que exigem agilidade e precisão no diagnóstico. A ausência de métodos acessíveis e eficazes para a coleta de informações como a frequência cardíaca pode comprometer a identificação precoce de problemas de saúde e a adoção de intervenções adequadas.
Com isso, muitos profissionais e tutores enfrentam desafios na manutenção da saúde dos animais, sobretudo em situações que exigem acompanhamento em tempo real dos sinais vitais. A falta de ferramentas práticas e confiáveis no dia a dia da prática veterinária reforça a necessidade de soluções que integrem tecnologia, praticidade e segurança para otimizar o monitoramento da saúde animal.

## 1.2. Descrição do Problema
Para melhorar a segurança no atendimento veterinário na cidade de Itacoatiara, especialmente no acompanhamento de animais com doenças cardíacas (cardiopatias), torna-se necessária a introdução de tecnologias adequadas para o monitoramento da frequência cardíaca durante consultas clínicas. Atualmente, a ausência de dispositivos específicos nas clínicas compromete a avaliação precisa da saúde cardíaca dos pets, o que dificulta diagnósticos rápidos e seguros, mesmo em atendimentos rotineiros.
Diante desse cenário, o projeto propõe uma solução inovadora para o monitoramento cardíaco em pets, com foco em animais que necessitam de atenção especial devido a cardiopatias. A proposta visa reduzir riscos associados a atendimentos clínicos, além de promover maior segurança, eficiência e qualidade no acompanhamento veterinário local, contribuindo para a melhoria da saúde e do bem-estar animal.

## 1.3. Descrição do Projeto
O projeto CardioPet propõe o desenvolvimento de uma roupa tecnológica com sistema embarcado para monitoramento de sinais cardíacos em pets. A ideia surgiu da necessidade de oferecer uma solução prática e acessível para acompanhar a saúde de animais, especialmente em casos de acompanhamento veterinário e prevenção de problemas cardíacos.
Durante o desenvolvimento do projeto, houve alterações importantes no escopo inicial. O que antes seria um peitoral com transmissão de dados para um aplicativo móvel, agora será um sistema totalmente embarcado, com processamento e exibição local das informações, sem a necessidade de conexão com smartphones.
A proposta é utilizar sensores integrados à roupa, aliados a um microcontrolador, para capturar os sinais cardíacos em tempo real. As informações serão exibidas diretamente no terminal, facilitando o acompanhamento por tutores e profissionais da área veterinária durante os testes e validações.
O CardioPet busca, acima de tudo, contribuir para o cuidado com a saúde animal, oferecendo uma tecnologia portátil, de fácil uso e capaz de monitorar os batimentos cardíacos de forma contínua e confiável, sem a necessidade de estruturas clínicas complexas ou recursos de internet.

# 2. OBJETIVO PRINCIPAL
Desenvolver uma Roupa Tecnológica com Sistema Embarcado para monitoramento da frequência cardíaca de pets, com exibição dos dados em tempo real através de uma página web hospedada localmente no ESP32 via Wi-Fi.

## 2.1. Objetivos Específicos
- Captar os sinais cardíacos dos pets utilizando sensores.
- Processar os sinais com o microcontrolador ESP32, convertendo-os em BPM.
- Exibir os dados em tempo real na interface web acessível via IP local.
- Garantir o conforto da roupa e a possibilidade de lavagem, com sensores removíveis.
- Oferecer uma solução prática, de baixo custo e de fácil utilização, sem necessidade de aplicativo.

# 3. IDENTIFICAÇÃO DE STAKEHOLDERS
A tabela a seguir apresenta uma visão geral dos tipos de usuários da aplicação, descrevendo suas características e papéis.
| Stakeholders                                        | Descrição     |
| ------------------------------------------- | --------------------------- |
| Veterinários   | Utilizam o sistema durante consultas para monitoramento cardíaco de pets.                      |
| Tutores de Pets | Acompanham a saúde dos seus pets no ambiente doméstico.                       |
| Estudantes e Pesquisadores | Profissionais ou acadêmicos interessados no desenvolvimento de tecnologias embarcadas voltadas à saúde animal.    |
| Equipe de Desenvolvimento  | Responsáveis pelo desenvolvimento, implementação, manutenção e evolução do sistema embarcado e da roupa tecnológica.  |

## 3.1 Equipe de desenvolvimento
A tabela a seguir lista os membros da equipe de desenvolvimento responsáveis pela criação e manutenção do sistema.
| Desenvolvedor    |  Responsabilidade             |
| ----------------------- | ------------------------------ |
| Chyntia Freitas Prestes | Integração dos sensores, Programação embarcada e Prototipação física. |
| Gabriel Batista dos Santos | Testes e Documentação.|
| João Vitor Oliveira Simões | Análise de requisitos, Documentação e GitHub. |
| Luanna Vitória Benezar Viana| Design da Roupa.|
| Manoele Braga Colares da Costa  | Arquitetura do sistema. |


# 4. TÉCNICAS UTILIZADAS
## 4.1. Arquitetura do Sistema
O sistema utilizará uma arquitetura embarcada composta por sensores de batimentos cardíacos integrados a um microcontrolador (ESP32), que processa os dados em tempo real e exibe os resultados diretamente no terminal do dispositivo conectado via rede Wi-Fi. Diferente da proposta inicial, o projeto não contará com um aplicativo mobile, sendo toda a comunicação e exibição realizada de forma local por meio do Serial Plotter da IDE Arduino, acessível via computador.

## 4.2. Tecnologias de Gerenciamento de Projeto
Durante o desenvolvimento do projeto CardioPet, a equipe utilizou o GitHub para o controle de versão e armazenamento do código-fonte, garantindo o registro de todas as alterações feitas no sistema embarcado.
Além disso, a comunicação entre os membros da equipe foi feita principalmente através de um grupo no WhatsApp, o que possibilitou trocas rápidas de informações, organização de reuniões e alinhamento das atividades ao longo do projeto.

| Tecnologia    |  Propósito             |
| ----------------------- | ------------------------------ |
| Git/GitHub | Versionamento/Repositório |
| WhatsApp | Gerenciamento de Tarefas da Equipe|

## 4.3. Tecnologias de Desenvolvimento
- O desenvolvimento do sistema será realizado utilizando a plataforma Arduino IDE, com a linguagem de programação C/C++, adequada para microcontroladores embarcados como o ESP32, que será o coração do sistema.
- A comunicação dos dados será feita através de Wi-Fi, eliminando a necessidade de aplicativos móveis. Com isso, os dados serão enviados diretamente para o terminal do computador, utilizando a ferramenta Serial Plotter da própria IDE Arduino, permitindo a visualização em tempo real das informações coletadas.
Para a captação dos sinais cardíacos, será utilizado o Módulo ECG AD8232, um sensor específico para detecção de sinais de batimentos cardíacos e eletrocardiograma (ECG), totalmente compatível com microcontroladores. Esse sensor garante uma leitura confiável dos sinais elétricos do coração do animal.
- A roupa tecnológica foi projetada para acomodar os sensores de forma segura, confortável e eficiente, proporcionando estabilidade nas medições, mesmo durante os movimentos naturais do pet.
- O sistema embarcado será responsável por todo o processamento dos dados recebidos dos sensores, realizando a interpretação dos sinais e exibindo os batimentos cardíacos diretamente no terminal. Essa solução elimina a necessidade de interfaces gráficas complexas, aplicativos externos ou armazenamento em nuvem, focando em uma comunicação local, leve e eficiente.
