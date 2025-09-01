# Projeto: Construção de um Pipeline de Dados ETL com Orientação a Objetos

#### Descrição do Projeto
Este projeto tem como objetivo principal a construção de um pipeline de Extração, Transformação e Carregamento (ETL) de dados, utilizando as melhores práticas de engenharia de dados e o paradigma de programação orientada a objetos (POO). Partindo de um ambiente de exploração inicial, o projeto evolui para uma solução robusta e automatizada, capaz de processar, limpar, transformar e salvar dados de diferentes formatos, como CSV e JSON.

O foco central é a transição de um código procedural, baseado em funções sequenciais, para uma estrutura organizada em classes e métodos, demonstrando a importância da POO para a manutenibilidade, escalabilidade e reutilização de código em projetos de dados. Ao final, o projeto entrega não apenas os dados transformados, mas também um relatório de execução que valida o processo, garantindo a integridade e o controle do pipeline.

#### Principais Aprendizados e Competências Desenvolvidas
Este projeto foi desenhado para fornecer uma experiência prática e abrangente, cobrindo as seguintes áreas:

1. Paradigma de Orientação a Objetos em Engenharia de Dados:
    - **Identificação da Necessidade:** Compreensão dos cenários em que a orientação a objetos se torna essencial para a organização e escalabilidade de um pipeline de dados.
    - **Refatoração para Classes:** Transformação de um conjunto de funções de processamento de dados em uma classe Dados coesa, encapsulando a lógica e o estado.
    - **Criação de Atributos e Métodos:** Definição clara dos atributos (para armazenar os dados brutos e transformados) e métodos (para executar as etapas de extração, transformação e carregamento).
    - **Adaptação e Manutenção:** Refatoração do código existente para acomodar novas necessidades e requisitos do cliente, demonstrando a flexibilidade da POO.

2. Fundamentos de Engenharia de Dados e Ambiente Operacional:
    - **Estruturação de Projeto:** Organização de um projeto de engenharia de dados em uma estrutura de diretórios lógica e funcional.
    - **Ambiente Linux:** Utilização de comandos essenciais do Linux (mkdir, wget) para criar a estrutura de pastas e realizar o download de fontes de dados da web.
    - **Leitura de Dados:** Manipulação de arquivos utilizando o comando open do Python como base para a leitura de dados brutos.

3. Extração e Manipulação de Dados (CSV e JSON):
    - **Leitura Eficiente:** Uso das bibliotecas csv e json para uma leitura de dados performática e segura, aproveitando funções como DictReader e readlines.
    - **Estruturação de Dados:** Análise e escolha da estrutura de dados mais adequada (listas, dicionários) para armazenar e manipular os dados extraídos.

4. Transformação Avançada de Dados:
    - **Manipulação de Dicionários:** Aplicação proficiente de métodos como keys(), get() e items() para inspecionar e manipular os dados.
    - **Renomeação e Consolidação:** Uso de laços de repetição (for) combinados com métodos de dicionário para renomear colunas e alinhar os dados aos requisitos do negócio.
    - **Unificação de Dados:** Utilização do método extend() para agregar múltiplos conjuntos de dados em uma única estrutura coesa.
    - **Estruturação Flexível:** Adaptação do comportamento do método get() para lidar com a ausência de chaves e construção de novas estruturas de dados (lista de listas) para diferentes formatos de saída.

5. Carregamento (Load) e Pipeline Final:
    - **Salvamento Estruturado:** Persistência dos dados transformados em formato CSV utilizando DictWriter (para manter a estrutura de dicionário) e writer (para a estrutura de lista de listas).
    - **Criação do Pipeline ETL:** Consolidação do código exploratório em um script final, com funções bem definidas para as etapas de Extração (E), Transformação (T) e Carregamento (L).
    - **Monitoramento e Relatório:** Geração de um relatório ao final da execução do pipeline, informando a quantidade de registros lidos e gravados, garantindo a rastreabilidade e a validação do processo.