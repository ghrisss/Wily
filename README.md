# 🏡 Wily - Previsão de Preços de Diárias de Imóveis

**Wily** é uma ferramenta de ciência de dados com foco em **previsão e consulta de preços de diárias de imóveis residenciais** disponibilizados por **pessoas físicas** em plataformas como o Airbnb. O objetivo é auxiliar esses anfitriões a precificarem de forma mais justa e estratégica seus anúncios de aluguel por temporada, além de permitir que possíveis locatários verifiquem se o preço de um imóvel está dentro do esperado para a região e período desejados.

## 💡 Motivação

Qualquer pessoa que possua um imóvel pode se tornar um "host" em plataformas de aluguel por temporada como o Airbnb. Ao criar um anúncio, o proprietário insere uma série de informações detalhadas sobre o imóvel, incluindo:

- Número de quartos, banheiros, camas e comodidades  
- Políticas de cancelamento  
- Regras da casa  
- Cobranças extras (como taxa de limpeza ou número adicional de hóspedes)  
- Período mínimo e máximo de estadia  
- Localização  

Essa grande variedade de características, junto com fatores sazonais e localização, torna a precificação uma tarefa complexa. **Wily** surge como uma consulta para trazer mais clareza nesse processo de definição de preço.

## 🎯 Objetivo

O projeto tem como principal objetivo construir um **modelo preditivo de preços de diárias**, utilizando dados reais de hospedagens, de forma a responder perguntas como:

- Quanto cobrar por uma diária, dado meu imóvel e suas características?
- O imóvel que estou interessado em alugar está com preço justo ou fora da média?

Apesar do foco principal estar voltado aos **anfitriões**, a ferramenta também poderá ser útil para **locatários** que queiram comparar preços.

## 📦 Base de Dados

Os dados utilizados no projeto foram extraídos do **Kaggle**, por meio do seguinte conjunto de dados:

📂 [Airbnb Rio de Janeiro - Kaggle Dataset](https://www.kaggle.com/datasets/allanbruno/airbnb-rio-de-janeiro/)

O conjunto contém arquivos mensais com os preços dos imóveis anunciados entre **agosto de 2018 e maio de 2020**, todos em reais.

### 📁 Estrutura dos Dados


## 🧠 Premissas Iniciais

Com base no conhecimento de domínio, algumas hipóteses levantadas para modelagem são:

- **Sazonalidade**: feriados, férias escolares e eventos locais impactam os preços  
- **Localização**: imóveis próximos a pontos turísticos, transporte público e áreas seguras tendem a ser mais valorizados  
- **Comodidades**: imóveis com comodidades como elevador, ar-condicionado, piscina ou garagem têm maior valor agregado  
- **Políticas e Regras**: restrições de estadia mínima/máxima ou regras rígidas podem influenciar negativamente o preço  

## 🔧 Tecnologias e Ferramentas


## 👤 Autor

**[Henrique B. Fragoso]** – Desenvolvedor de Software e entusiasta de ciência de dados.
