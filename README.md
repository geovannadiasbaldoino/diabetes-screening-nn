# diabetes-screening-nn

# Triagem Automática de Pacientes com Diabetes

Este projeto aplica conceitos de **Aprendizado Supervisionado** para construir um modelo de triagem automatizada, capaz de identificar a probabilidade de um paciente desenvolver diabetes com base em métricas biomédicas.

### O que eu fiz e por quê?
A ideia foi migrar de cenários acadêmicos clássicos (como o dataset Iris) para um desafio de saúde do mundo real. Utilizando o dataset **Pima Indians Diabetes Database** (via Kaggle), tratei e explorei os dados estruturados de centenas de pacientes. 

Construí e treinei uma **Rede Neural Artificial (Deep Learning)** utilizando o **TensorFlow/Keras** para realizar uma classificação binária (saudável vs. diabético), analisando variáveis como glicose, IMC, pressão arterial e idade.

###  Resultados Obtidos
* **Análise Exploratória:** Identificação visual de que variáveis como *Glicose* e *IMC* possuem forte correlação e separação clara na distribuição dos pacientes diagnosticados.
* **Desempenho do Modelo:** O modelo conseguiu convergir bem durante as épocas de treino. A acurácia, precisão e recall foram avaliadas em dados de teste inéditos para garantir que a rede não estava apenas memorizando os dados (overfitting), tornando o modelo viável para auxiliar em uma triagem médica preliminar.
* **Métricas Visuais:** O repositório inclui a plotagem do comportamento da *Loss* e da *Acurácia* ao longo do treinamento, validando a estabilidade do aprendizado da rede.

---
*Tecnologias utilizadas: Python, Pandas, Seaborn, Matplotlib, Scikit-Learn e TensorFlow/Keras.*
