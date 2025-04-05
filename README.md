# Análise de sentimentos com Language Studio no Azure AI

## Sobre o Language Studio

O Azure AI Language Studio é uma plataforma da Microsoft que oferece ferramentas de Processamento de Linguagem Natural (NLP) para analisar e interpretar textos.

## Principais Funcionalidades:

✔ Análise de Sentimento – Detecta emoções (positivo, neutro, negativo) em textos, como visto nas frases analisadas.

✔ Mineração de Opiniões – Extrai avaliações sobre produtos, serviços ou pessoas.

✔ Reconhecimento de Entidades – Identifica nomes, datas, lugares e termos importantes.

✔ Sumarização Automática – Gera resumos de textos longos.

# Processo de Criação 

## Criação do recurso Azure Languague Studio 

- (Criação do Recurso Languague Studio) :
  
   ![image](https://github.com/user-attachments/assets/90d5ecb8-6209-4586-9c8e-d60e05b6692c)

- Definição de noções básicas, rede e identity:


  ![image](https://github.com/user-attachments/assets/5818adfe-ac6b-4355-b32b-269327578fc1)

- Selecionado o recurso do Language Studio:

  ![image](https://github.com/user-attachments/assets/f50be9c9-2b70-429a-b943-da3251cc6c70)

- Acesando o serviço de sentimentos e opinião com o trecho do livro Mémorias Póstumas de Brás Cubas:
 
    ![image](https://github.com/user-attachments/assets/f6e9fec1-9c3e-4852-a599-24568f1b8a3e)

# Análise de Sentimento e Opiniões das Frases Sobre as Memórias Póstumas de Brás Cubas

## Visão Geral

A análise mostra predominantemente sentimentos negativos nas frases analisadas, com algumas exceções neutras. A confiança nas classificações negativas é geralmente alta (acima de 90%), enquanto as classificações positivas são quase inexistentes.

## Análise Detalhada por Sentença: 

### Sentença 1

- Sentimento: Negativo (100% negativo)

![image](https://github.com/user-attachments/assets/a36e8695-ee82-479e-8a4c-15c4058c88fa)

### Sentença 2 e 3

- Sentimento: Negativo (sentença 2 - 99% negativo) e  Negativo (sentença 3 - 91% negativo)

O contéudo da sentença 2 está expressando frustração por não alcançar certos status sociais, já a sentença 3 fala sobre a "boa fortuna" de não ter que trabalhar duro, mas com tom irônico/negativo

![image](https://github.com/user-attachments/assets/acfe3e88-451a-4683-b1f4-1b3d1620a190)

### Sentença 4 e 5

- Sentimento: Neutro (sentença 4 - 98% confiança) e Negativo (sentença 5 -100% negativo)

O contéudo da sentença 4 apenas identificou a palavra "Mais", já a sentença 5 menciona sofrimento e perda

![image](https://github.com/user-attachments/assets/05e6b88c-e6c2-41ad-9ab8-677b4644bcf7)

### Sentença 6 e 7

- Sentimento: Negativo (sentença 6 - 76% negativo) e Negativo (sentença 7 - 98% negativo)

O conteúdo da sentença 6 sugere um balanço neutro da vida, mas com viés negativo, já a sentença 7 contradiz a afirmação anterior de forma negativa.

![image](https://github.com/user-attachments/assets/20dbb3c8-ace8-4e98-babc-a1110677641d)

### Sentença 8 e 9

- Sentimento: Negativo (sentença 8 -100% negativo) e Neutro (sentença 9 -99% neutro)

O conteúdo da sentença 8 fala sobre solidão e falha em perpetuar a espécie, já a setença 9 apenas o título da obra foi mencionado.

![image](https://github.com/user-attachments/assets/3f0e14ae-eb36-4c2c-b0a1-16d7723e78f1)


# Conclusão

O texto analisado apresenta um tom marcadamente negativo, refletindo frustrações, arrependimentos e visões pessimistas sobre a vida. As poucas frases neutras são extremamente curtas ou meramente descritivas. A análise de sentimentos foi consistente em capturar essa negatividade predominante, com altos níveis de negatividade nas classificações.
