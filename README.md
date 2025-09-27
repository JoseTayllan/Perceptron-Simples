
# 🧠 Perceptron Simples

<a href="https://colab.research.google.com/github/JoseTayllan/Perceptron-Simples/blob/main/Perceptron_Simples.ipynb" target="_parent">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## 📚 Informações
- **Curso:** GTI  
- **Disciplina:** Inteligência Artificial Aplicada  
- **Professor:** Jonas Augusto Kunzler  
- **Aluno:** José Tayllan Pinto Almeida  
- **Data:** 10/03/2025  

---

## 📖 Descrição
Este projeto implementa um **Perceptron Simples** em Python utilizando **NumPy** para classificar pontos no plano cartesiano.  
O algoritmo aprende a separar os pontos com base em uma **reta predefinida**, ajustando seus pesos conforme a **regra de atualização do Perceptron**.

---

## ⚙️ Estrutura do Notebook
- Importação de bibliotecas: `numpy`, `matplotlib`
- Função `target_function(x)` → gera a reta de separação  
- Função `step_function(x)` → função de ativação degrau  
- Função `train_perceptron(...)` → treino do perceptron com taxa de aprendizado e épocas  
- Função `predict(...)` → previsões após o treinamento  
- Visualização gráfica dos pontos classificados no plano cartesiano  

---

## 📊 Exemplos de Resultados
O notebook gera gráficos mostrando:
- A reta de separação aprendida  
- Pontos classificados como **acima** ou **abaixo** da reta  
- Evolução do treinamento do perceptron  

---

## ▶️ Como Executar
1. Clone este repositório  
2. Abra o notebook no Jupyter ou Google Colab  
3. Execute as células em ordem  

```bash
pip install numpy matplotlib
```

---

## 🌱 Melhorias Futuras
- Implementar perceptron multicamadas (MLP)  
- Adicionar função de custo e monitoramento do erro  
- Avaliar diferentes funções de ativação  
- Criar interface interativa para testes  

---

📍 **Responsável:** José Tayllan Pinto Almeida
