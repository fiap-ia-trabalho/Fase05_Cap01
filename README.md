# FIAP - Faculdade de Informática e Administração Paulista

<img width="2385" height="642" alt="image" src="https://github.com/user-attachments/assets/594c28cc-66ae-40ac-b8a6-8c39e6f14de4" />

# FarmTech na Era da Cloud Computing

## 👨‍🎓 Integrantes: 
- [CAUAN OTTO RODRIGUES SOUSA (RM567940)](https://www.linkedin.com/in/cauanotto)
- [FERNANDO A GURGEL (RM567606)](https://www.linkedin.com/in/fernando-gurgel-75aa8369)
- [IRACI MONTEIRO SOUZA (RM567544)](https://www.linkedin.com/in/iraci-souza-bab42034)
- [MARIA LUISA RODRIGUES NASCIMENTO (RM567659)](https://www.linkedin.com/in/malu-rodrigues-bb756b271)
- [RAFAELA TORRES MARTINS (RM567735)](https://www.linkedin.com/in/rafaela-torres222)


## 👩‍🏫 Professores:
- **Tutor(a):** [ANA CRISTINA DOS SANTOS](https://www.linkedin.com/company/inova-fusca)
- **Coordenador(a):** [ANDRÉ GODOI](https://www.linkedin.com/in/andregodoichiovato)


## 📜 Descrição
Este projeto foi desenvolvido para a Fase 5 da FIAP com foco em **Machine Learning** e **Cloud Computing**, dentro do contexto da startup fictícia **FarmTech Solutions**.

A proposta consiste em analisar uma base de dados agrícolas contendo informações sobre:
- Cultura
- Precipitação
- Umidade específica
- Umidade relativa
- Temperatura
- Rendimento da safra

O trabalho foi dividido em duas frentes:

### Entrega 1 — Machine Learning
- Análise exploratória da base
- Identificação de padrões e outliers
- Clusterização com algoritmos não supervisionados
- Construção de **5 modelos preditivos de regressão**
- Avaliação de desempenho com métricas apropriadas

### Entrega 2 — Cloud Computing
- Simulação de custos na AWS
- Comparação entre as regiões **São Paulo** e **Virgínia do Norte**
- Justificativa técnica e legal da escolha da infraestrutura

---

## Objetivo

Desenvolver uma solução analítica e preditiva capaz de estimar o rendimento agrícola com base em variáveis ambientais, além de avaliar a viabilidade de hospedagem da aplicação em ambiente de nuvem.

---

## Dataset utilizado

Arquivo: `crop_yield.csv`

A base contém 156 registros distribuídos entre 4 culturas agrícolas:
- Cocoa, beans
- Oil palm fruit
- Rice, paddy
- Rubber, natural

---

## Principais etapas do notebook

O notebook contempla:

1. Importação e leitura da base  
2. Estatística descritiva  
3. Histogramas, boxplots e heatmap de correlação  
4. Modelagem preditiva com:
   - Linear Regression
   - Random Forest Regressor
   - Gradient Boosting Regressor
   - SVR
   - KNeighbors Regressor
5. Clusterização com:
   - K-Means
   - DBSCAN
6. Análise de outliers  
7. Simulação de custos AWS  

---

## Principais resultados

- Os modelos supervisionados apresentaram bom desempenho preditivo para estimativa de rendimento agrícola.
- A análise não supervisionada permitiu identificar agrupamentos de condições ambientais e observações discrepantes.
- A análise de computação em nuvem mostrou que decisões de infraestrutura não devem considerar apenas custo, mas também fatores como latência, conformidade legal e contexto de negócio.

---

## Notebook do projeto

https://colab.research.google.com/drive/1_sKZ5Exa9XY4d8-A10MnmGUINMwq3WX6#scrollTo=c0996c18

> Importante: para correção, o notebook deve estar com todas as células executadas.

---

## Vídeos demonstrativos

### Entrega 1 — Machine Learning
https://youtu.be/mee4sucIaTw

### Entrega 2 — AWS
https://youtu.be/Z_3WqeunGow

---

## Como executar o projeto

### Requisitos
- Python 3.10+
- Jupyter Notebook ou Google Colab

### Bibliotecas utilizadas
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
