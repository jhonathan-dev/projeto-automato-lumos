# Autômato Modernizado "Lumos": Solução de Iluminação Pública Inteligente para Smart Cities

## Alunos Envolvidos
| Nome | RGM |
| :--- | :--- |
| Alejandro Lopes Reategui | 34125701 |
| Artur Almeida Alves de Melo | 33363650 |
| Gabriel Henrique Luiz Mendes | 33890897 |
| Jhonathan de Moura Santos | 32813589 |
| Melissa Aragão Leite | 33999554 |

---

## 📌 Observações Importantes

1.  **Pesquisa:** O arquivo de pesquisa completo, **`Pesquisa_Automathon_Lumos.pdf`**, está localizado na pasta **`Docs`**.
2.  **Vídeo do Projeto:** O vídeo de demonstração do projeto está hospedado externamente, pois o tamanho do arquivo excedeu o limite de **25 MB** permitido pelo GitHub. O arquivo de vídeo está na pasta **`Video`** e contém um link ou arquivo de texto com a URL de acesso no Google Drive.
3.  
---

## 📄 Pesquisa e Desenvolvimento: Autômato Modernizado "Lumos"

Este repositório contém a documentação completa do projeto **Autômato Modernizado "Lumos"**, uma proposta de solução de **Iluminação Pública Inteligente** baseada em Sistemas Ciber-Físicos (CPS) e Internet das Coisas (IoT) para o contexto de Smart Cities.

O documento principal, **`Pesquisa_Automathon_Lumos.pdf`** (localizado na pasta `Docs`), detalha o diagnóstico, a arquitetura tecnológica e o plano de implementação da solução.

### Descrição Detalhada do Conteúdo do PDF

O trabalho está estruturado em três fases principais, que transformam o poste de luz tradicional (autômato clássico) em um nó inteligente e ativo na infraestrutura urbana:

#### Fase I: Diagnóstico (O "Porquê")
Esta seção identifica as limitações do sistema de iluminação pública convencional.
*   **Objeto de Estudo:** O poste de luz tradicional é analisado como um "autômato clássico" com operação binária (ligado/desligado), resultando em alto consumo energético e ineficiência.
*   **Deficiência Computacional:** O sistema atual é considerado "hardware mudo", incapaz de processar dados, se integrar a redes (IoT) ou fornecer informações para Gêmeos Digitais.
*   **Impacto Sociológico e Urbanístico:** É abordada a falha do modelo de **manutenção reativa**, que depende do cidadão como "sensor falho", gerando "zonas de escuridão" prolongadas, impactando a segurança pública (Teoria das Janelas Quebradas) e aumentando os custos operacionais da gestão pública.

#### Fase II: Solução - Arquitetura Tecnológica do Autômato Modernizado LUMOS
A solução proposta é um **Sistema Ciber-Físico (CPS)** que opera com base em dados e Inteligência Artificial (IA).
*   **Arquitetura em Camadas:** O fluxo de dados é dividido em cinco camadas:
    1.  **Sensoriamento (Input):** Coleta de dados ambientais via sensores LDR (luminosidade) e PIR (presença/movimento).
    2.  **Comunicação (Rede):** Uso de protocolos como LoRaWAN e MQTT para envio de dados.
    3.  **Plataforma/Nuvem:** Armazenamento e processamento de dados (e.g., InfluxDB, Edge Computing).
    4.  **Inteligência Artificial (IA):** Decisão automatizada, ajuste dinâmico de intensidade luminosa e manutenção preditiva.
    5.  **Atuação (Output):** Controle da iluminação LED (aumento/diminuição de intensidade) e envio de alertas de falha.
*   **Funcionalidades Inteligentes:** O sistema implementa **Iluminação em Repouso** (baixa intensidade na ausência de movimento) e **Iluminação por Demanda** (alta intensidade ao detectar presença), garantindo economia e segurança.
*   **Integração com Infraestrutura Crítica e Gêmeos Digitais (Digital Twins):** O Lumos se integra à gestão da cidade, permitindo simulação de cenários, otimização centralizada e previsão de falhas de componentes.

#### Fase III: Implementação e Resultado
Esta fase detalha o roteiro prático para a ativação da arquitetura e a comprovação de sua eficácia.
*   **Roteiro de Ação:** Guia de implementação que inclui Adequação Física (Hardware), Conectividade (Rede) e Integração com IA/Digital Twin (Software).
*   **Definição de KPIs:** São estabelecidas métricas quantitativas alinhadas à norma ABNT NBR ISO 37122 para medir o sucesso do projeto:
    *   **Redução do Consumo Energético** (Meta: >30%).
    *   **Tempo Médio de Reparo (MTTR)**.
    *   **Índice de Manutenção Preditiva vs. Corretiva**.
    *   **Taxa de Disponibilidade da Rede IoT**.

