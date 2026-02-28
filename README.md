<h1 align="center">NietzscheLLM</h1>
<h3 align="center">Modelo de linguagem com BERT treinado em textos de Friedrich Nietzsche</h3>

<p align="center">
Projeto educacional que demonstra como construir e entender um modelo de linguagem baseado em Transformers a partir de um corpus real.
</p>

<p align="center">
<a href="https://www.youtube.com/watch?v=LphBQB1amrw">
  <img src="https://img.youtube.com/vi/LphBQB1amrw/hqdefault.jpg" width="760" alt="LLM do Zero com BERT"/>
</a>
</p>

<p align="center">
<b>LLM do Zero com BERT — Construindo um modelo de linguagem na prática</b><br/>
<sub>Clique na imagem para assistir ao walkthrough completo</sub>
</p>

---

## Visão geral

Este repositório mostra, de forma prática e didática, como funciona a arquitetura de um modelo de linguagem moderno utilizando **Transformers (BERT)**.

O modelo é explorado a partir de um corpus específico:  
**Crepúsculo dos Ídolos**, de Friedrich Nietzsche.

O objetivo do projeto é mostrar:

- Como preparar um corpus textual
- Como funciona a tokenização
- Como estruturar entradas para um Transformer
- Como executar inferência
- Como modelos de linguagem capturam contexto a partir dos dados

O foco é **entendimento estrutural**, não apenas uso de modelos prontos.

---

## Estrutura do repositório

```
NietzscheLLM/
├── IntroLLMTransformers.ipynb   # Notebook principal (pipeline completo)
├── crepusculoDosIdolos.txt      # Corpus utilizado
└── README.md
```

### O que o notebook contém

- Introdução conceitual aos Transformers
- Leitura e preparação do corpus
- Tokenização
- Construção das entradas do modelo
- Execução de inferência
- Exploração do comportamento do modelo

---

## Stack utilizada

- Python 3.x  
- Jupyter Notebook  
- PyTorch  
- Hugging Face Transformers  
- Tokenizers  

---

## Como executar

### 1. Clonar o repositório

```
git clone https://github.com/ferrarimarlon/NietzscheLLM.git
cd NietzscheLLM
```

### 2. Instalar dependências

```
pip install torch transformers notebook
```

### 3. Executar

```
jupyter notebook
```

Abra o arquivo:

```
IntroLLMTransformers.ipynb
```

Execute as células em sequência.

---

## O que este projeto demonstra

- Funcionamento prático de um Transformer
- Como um modelo de linguagem aprende a partir de um domínio específico
- Estrutura interna de um pipeline de NLP moderno
- Diferença entre usar um LLM e entender um LLM

---

## Possíveis extensões

- Fine-tuning com múltiplas obras do autor
- Geração de texto no estilo Nietzsche
- Avaliação semântica das respostas
- Deploy como API ou chatbot temático

---

## Autor

**Marlon Ferrari**  
Analytics Engineer @ Nubank  
Professor de Ensino Superior  

YouTube: https://www.youtube.com/@profmarlonferrari  
LinkedIn: https://linkedin.com/in/marlonferrari  

---

## Licença

GPL v3
