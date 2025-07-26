# 💻 Lab Project 03 - Análise de Sentimentos com Language Studio no Azure AI

A funcionalidade de **análise de sentimentos e mineração de opiniões** faz parte da plataforma **Language Studio do Azure**, permitindo **identificar sentimentos positivos, negativos ou neutros** em sentenças. Este repositório apresenta exemplos práticos de testes realizados na plataforma, como parte do **Bootcamp Microsoft Azure AI Fundamentals promovido pela DIO**.

---

## 📑 Índice

1. [🛠️ Procedimento](#️procedimento)
2. [📊 Resultados](#resultados)
3. [💡 Conclusão e Insights](#conclusão-e-insights)

---

## 🛠️ Procedimento

Os testes seguiram instruções do Microsoft Learn. Para mais detalhes, consulte:

🔗 [Analyze text with Language Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)

### 1. Criando o recurso **Azure Language Service**

1. Acesse o portal: https://portal.azure.com  
2. Clique em **"Create a resource"** e selecione **Language Service**.

<div align="center">
    <img src="readmeFiles/01.png" alt="Create a resource" width="600"/>
</div>

<div align="center">
    <img src="readmeFiles/03.png" alt="Create a resource" width="600"/>
</div>

3. Aguarde o término do *deploy*.

---

### 2. Conectando ao **Language Studio**

1. Acesse o [🌐 Language Studio](https://language.cognitive.azure.com/home).  
2. Na página inicial, clique em **"Select a resource"**.

<div align="center">
    <img src="readmeFiles/04.png" alt="View all resources" width="800"/>
</div>

3. Preencha os dados e selecione o recurso criado.

<div align="center">
    <img src="readmeFiles/05.png" alt="Set default resource" width="800"/>
</div>

---

### 3. Usando o serviço de análise de sentimentos

Na aba **"Classify text"**, selecione o serviço **"Analyze sentiment and mine opinions"**:

<div align="center">
    <img src="readmeFiles/06.png" alt="Language Studio Services" width="800"/>
</div>

---

## 📊 Resultados

Com o recurso ativo, é possível:

- Carregar um texto para análise
- Definir o idioma
- Ativar a opção de *opinion mining*

Para este experimento, foi utilizado um trecho do livro de Mateus (Bíblia).

<div align="center">
    <img src="readmeFiles/07.png" alt="Input Text" width="800"/>
</div>

O sistema indicou que **65% do conteúdo apresenta sentimento negativo**, com apenas **25% de confiança geral**.

<div align="center">
    <img src="readmeFiles/08.png" alt="Sentiment Chart" width="400"/>
</div>

<br>

<div align="center">
    <img src="readmeFiles/09.png" alt="Detailed Results" width="600"/>
</div>

<br>

<div align="center">
    <img src="readmeFiles/11.png" alt="Confidence Scores" width="600"/>
</div>

Também foi possível visualizar o funcionamento da **mineração de opiniões** (*opinion mining*):

<div align="center">
    <img src="readmeFiles/10.png" alt="Opinion Mining" width="600"/>
</div>

---

## 💡 Conclusão e Insights

Ferramentas de **análise de sentimentos** são extremamente úteis na **automação de análises textuais**, como avaliações e *feedbacks*.

⚠️ Porém, os resultados indicam que o sistema pode ter limitações em textos **menos diretos** ou com **contexto complexo**, possivelmente por realizar a análise **sentença por sentença**, sem entender o **contexto global**.

🔍 Uma abordagem baseada em **compreensão contextual ampla** e **relação entre sentenças** poderia oferecer resultados mais coerentes em textos narrativos ou informativos.

---
