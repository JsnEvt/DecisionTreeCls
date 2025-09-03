# Projeto: Análise do Dataset Kyphosis com Árvores Aleatórias 🌳

Este projeto foi desenvolvido durante o curso **Python para Data Science e Machine Learning** (Udemy) e tem como objetivo aplicar técnicas de **tratamento de dados** e utilizar o algoritmo de **Árvores Aleatórias (Random Forest)** para prever a ocorrência de **cifose (Kyphosis)** após cirurgia na coluna vertebral.

---

## 📌 Sobre o Dataset Kyphosis
O dataset **Kyphosis** é amplamente utilizado em exemplos de aprendizado de máquina.  
Ele contém informações de 81 pacientes submetidos à cirurgia de correção da coluna, com os seguintes atributos:

- **Kyphosis** → Variável alvo (presença ou ausência da deformidade pós-cirurgia).  
- **Age** → Idade do paciente no momento da cirurgia.  
- **Number** → Número de vértebras envolvidas.  
- **Start** → Primeira vértebra onde a cirurgia foi realizada.

O objetivo é prever se a condição **Kyphosis** estará presente ou ausente após a cirurgia.

---

## 🌳 Árvores Aleatórias (Random Forest)
O algoritmo **Random Forest** é um método de **ensemble learning**, combinando diversas **árvores de decisão** para aumentar a robustez e a precisão do modelo.

### 🔑 Características principais:
- Reduz o **overfitting**, comum em árvores de decisão únicas.
- Trabalha bem em datasets pequenos e médios.
- Mede a **importância das variáveis** na previsão.
- Pode ser aplicado em **classificação** e **regressão**.

---

## 🛠️ Tecnologias utilizadas
- **Python**
- **Pandas** → manipulação dos dados  
- **NumPy** → cálculos numéricos  
- **Matplotlib / Seaborn** → visualização dos dados  
- **Scikit-learn** → implementação do Random Forest, divisão de dados e métricas  

---

## 📊 Etapas do projeto
1. Importação e análise exploratória do dataset Kyphosis.  
2. Tratamento e preparação dos dados.  
3. Criação e treinamento do modelo com **Random Forest Classifier**.  
4. Avaliação do modelo utilizando:
   - Acurácia  
   - Matriz de confusão  
   - Relatório de classificação (precisão, recall e F1-score)  
5. Análise da **importância das variáveis**.  

---

## 🚀 Como executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/JsnEvt/DecisionTreeCls.git

📖 Licença
Este projeto está sob a licença MIT – sinta-se à vontade para usar e modificar.
