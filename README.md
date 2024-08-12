# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 12/08/2024
Empresa: Abstergo Industries 
Responsável: Kayllane Pina

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Kayllane Pina. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- **Nome da ferramenta**: Amazon EC2 Spot Instances
- **Foco da ferramenta**: Redução de custos em computação na nuvem
- **Descrição de caso de uso**: A utilização de Spot Instances permite à Abstergo Industries acessar capacidade de computação não utilizada na AWS a uma fração do custo das instâncias sob demanda. Essa solução é ideal para cargas de trabalho flexíveis, como análises de dados e processamento em batch, onde a interrupção das instâncias não comprometerá a operação.

Etapa 2: 
- **Nome da ferramenta**: Amazon S3 Intelligent-Tiering
- **Foco da ferramenta**: Otimização de custos de armazenamento
- **Descrição de caso de uso**: O S3 Intelligent-Tiering oferece uma maneira automática de otimizar os custos de armazenamento, movendo dados entre camadas de armazenamento de acesso frequente e infrequente com base em padrões de uso. Essa abordagem é adequada para dados cujo padrão de acesso é imprevisível, garantindo economia automática sem impacto no desempenho.

Etapa 3: 
- **Nome da ferramenta**: AWS Lambda
- **Foco da ferramenta**: Redução de custos operacionais através da computação serverless
- **Descrição de caso de uso**:  A adoção de AWS Lambda para execução de código em resposta a eventos permite que a Abstergo Industries pague apenas pelo tempo de computação consumido, sem a necessidade de gerenciar servidores. Esta solução é eficaz para automatização de tarefas, como processamento de imagens ou integração de sistemas, onde o dimensionamento automático e a cobrança baseada em uso resultam em economias significativas.



## Conclusão
A implementação de ferramentas na empresa *[nome da empresa] tem como esperado [benefícios das ferramentas]*, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

1. **Manual de Uso**: Amazon EC2 Spot Instances

   - **Descrição:** Este manual detalha o processo de configuração e uso das Spot Instances no Amazon EC2. Inclui instruções passo a passo para selecionar, lançar e gerenciar instâncias, além de dicas para maximizar a economia de custos.

     **Formato:** PDF

     **Arquivo:** `Manual_EC2_Spot_Instances.pdf`

2. **Documento de Políticas de Retenção de Dados: Amazon S3 Intelligent-Tiering**

   - **Descrição:** Este documento descreve as políticas de retenção e movimentação de dados no Amazon S3 utilizando o Intelligent-Tiering. Contém exemplos de políticas aplicáveis para diferentes tipos de dados e como configurar a mudança automática entre as classes de armazenamento.
   - **Formato:** DOCX
   - **Arquivo:** `Politicas_Retencao_S3.docx`

3. **Planilha de Cálculo de Custo: AWS Lambda**

   - **Descrição:** Planilha que estima os custos potenciais ao utilizar AWS Lambda para diferentes cargas de trabalho. A planilha inclui variáveis como número de execuções, duração média das funções e memória alocada para fornecer uma visão geral dos custos previstos.
   - **Formato:** XLSX
   - **Arquivo:** `Custo_Lambda.xlsx`

Assinatura do Responsável pelo Projeto:

 Kayllane Pina