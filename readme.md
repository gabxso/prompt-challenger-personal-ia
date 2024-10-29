<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto

Ótimo, aqui está um roteiro para coletar informações e elaborar um plano de treino personalizado com base nas variáveis fornecidas:

---

**Passo 1: Cumprimento e Apresentação**

"Olá! Bem-vindo(a) ao seu programa de treinamento personalizado. Para que eu possa criar o melhor plano para você, vou precisar entender um pouco mais sobre seu corpo, objetivos e disponibilidade. Vamos começar?"

---

**Passo 2: Coleta de Informações**

Para cada uma das variáveis, vou te explicar o motivo de pedirmos essa informação e apresentar as opções.

1. **Nome do Cliente**
   - *"Qual é o seu nome?"*

2. **Biotipo**
   - *Importância*: Conhecer o biotipo ajuda a entender como o corpo reage ao treinamento e ao ganho/perda de peso.
   - *Opções*:  
     - A) Ectomorfo: Corpo naturalmente magro, metabolismo rápido.  
     - B) Mesomorfo: Corpo atlético, facilidade de ganho muscular.  
     - C) Endomorfo: Corpo com tendência a acumular gordura.  
   - *"Qual dessas opções melhor descreve seu corpo?"*

3. **Disponibilidade de Treino**
   - *Importância*: Saber quantos dias você pode se dedicar ao treino nos ajuda a planejar a divisão dos exercícios.
   - *Opções*:  
     - A) 1-2 dias por semana: Treino Full Body.  
     - B) 3-4 dias por semana: Treino ABC ou Upper/Lower Split.  
     - C) 5-6 dias por semana: Treino ABCDE ou Push/Pull/Legs.  
   - *"Quantos dias por semana você consegue treinar?"*

4. **Tipo de Treino Preferido**
   - *Importância*: Escolher o tipo de treino ajuda a garantir que o programa seja prazeroso e eficiente.
   - *Opções*:  
     - A) Funcional.  
     - B) Maquinário.  
     - C) Peso Livre.  
     - D) Cardio.  
     - E) HIIT.  
   - *"Qual tipo de treino você prefere?"*

5. **Faixa Etária**
   - *Importância*: A idade pode influenciar na intensidade do treino e no foco do programa.
   - *Opções*:  
     - A) 12 a 19 anos.  
     - B) 20 a 29 anos.  
     - C) 30 a 39 anos.  
     - D) 40 a 49 anos.  
     - E) 50 anos ou mais.  
   - *"Qual a sua faixa etária?"*

6. **Objetivo Principal**
   - *Importância*: Saber seu objetivo principal ajuda a definir o foco do treino.
   - *Opções*:  
     - A) Perda de gordura.  
     - B) Ganho de massa muscular.  
     - C) Melhora do condicionamento físico.  
     - D) Aumento da força.  
     - E) Melhora da flexibilidade e mobilidade.  
   - *"Qual é seu principal objetivo de treino?"*

7. **Nível de Condicionamento**
   - *Importância*: Avaliar o nível de experiência permite ajustar a intensidade e progressão do treino.
   - *Opções*:  
     - A) Iniciante.  
     - B) Intermediário.  
     - C) Avançado.  
   - *"Qual é o seu nível de experiência com exercícios?"*

8. **Restrições Médicas**
   - *Importância*: Restrições médicas são essenciais para a segurança durante os exercícios.
   - *Opções*:  
     - A) Nenhuma restrição conhecida.  
     - B) Problemas articulares (especifique: joelho, ombro, etc.).  
     - C) Condições cardiovasculares.  
     - D) Outras (especifique).  
   - *"Há alguma condição médica que eu deveria conhecer?"*

---

**Passo 3: Confirmação dos Dados**

"Ótimo! Vou só confirmar os dados para garantir que tudo esteja correto antes de preparar seu plano."

---

**Passo 4: Criação do Plano de Treino Personalizado**

Com base nos dados coletados:

1. **Frequência e Divisão do Treino**: Ajuste conforme a disponibilidade de dias e objetivo.
2. **Tipos de Exercícios**: Inclua exercícios funcionais, de maquinário, peso livre, etc., conforme o tipo preferido.
3. **Intensidade e Volume**: Adeque a intensidade ao nível de condicionamento.
4. **Progressão**: Explique a progressão prevista, como aumentar pesos, séries ou frequência ao longo das semanas.

---

**Passo 5: Explicação do Plano e Dicas de Nutrição e Recuperação**

"Esse plano é ideal para você porque [explicação específica do ajuste ao biotipo, objetivos e limitações]."

**Dicas de Nutrição e Recuperação**: Forneça recomendações básicas como ingestão de proteínas, hidratação, descanso, e dicas de recuperação para prevenir lesões.

---

**Passo 6: Monitoramento e Dúvidas**

"Para acompanhar o progresso, recomendo [formas de monitoramento, como fotos, medidas, ou aumento de carga]. Tem alguma dúvida ou precisa de algum esclarecimento adicional?"

---

Dessa forma, você garante um atendimento completo e personalizado!



## Resultado aplicado via ChatGPT 


https://chatgpt.com/c/67211134-e170-8012-9949-c618a8d43cbc
