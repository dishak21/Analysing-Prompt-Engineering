# 🧠 Analysing Prompt Engineering

## 📌 Overview

This project delves into the intricacies of prompt engineering, aiming to understand how different prompt structures and strategies influence the performance of large language models (LLMs). By systematically analyzing various prompting techniques, the study seeks to identify best practices that enhance model outputs across diverse tasks.

---

## 🎯 Objectives

- **Evaluate Prompt Strategies**: Assess the effectiveness of different prompting methods, including zero-shot, few-shot, and chain-of-thought prompting.
- **Performance Metrics**: Measure the impact of prompt variations on model accuracy, coherence, and relevance.
- **Best Practices**: Derive insights and guidelines for crafting effective prompts tailored to specific tasks and models.

---

## 🗂️ Repository Contents

- `prompt_analysis.ipynb`: Jupyter Notebook containing experiments and analyses of various prompting techniques.
- `data/`: Directory housing datasets used for prompt evaluations.
- `results/`: Contains output files and performance metrics from the conducted experiments.
- `README.md`: Project overview and instructions.

---

## 🧪 Methodology

### 🔹 Prompting Techniques Explored

- **Zero-Shot Prompting**: Evaluating model performance without prior examples.
- **Few-Shot Prompting**: Providing the model with a few examples to guide its responses.
- **Chain-of-Thought Prompting**: Encouraging the model to reason step-by-step before arriving at an answer.

### 🔹 Evaluation Metrics

- **Accuracy**: Correctness of the model's responses.
- **Coherence**: Logical consistency in the generated outputs.
- **Relevance**: Alignment of responses with the intended task or question.

---

## 📈 Results

- **Zero-Shot vs. Few-Shot**: Few-shot prompting consistently outperformed zero-shot in tasks requiring contextual understanding.
- **Chain-of-Thought**: Incorporating reasoning steps improved performance in complex problem-solving tasks.
- **Prompt Structure**: Clear and specific prompts yielded more accurate and relevant responses.

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python libraries:
  - openai
  - pandas
  - numpy
  - matplotlib
  - seaborn

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/dishak21/Analysing-Prompt-Engineering.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd Analysing-Prompt-Engineering
   ```

3. **Install the required libraries**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Jupyter Notebook**:

   ```bash
   jupyter notebook prompt_analysis.ipynb
   ```

---

## 📚 References

- [OpenAI Cookbook](https://github.com/openai/openai-cookbook)
- [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide)
- [Awesome Prompt Engineering](https://github.com/promptslab/Awesome-Prompt-Engineering)
