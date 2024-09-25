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
###Variaveis

{{Biotipo Corporal}} = Endomorfo
{{Dias de Treino}} = 3 dias por semana
{{Tipos de Exercício}} = Funcional

## 🎯 Prompt de Resposta Proposto



Objetivo Geral
O foco do treino para um endomorfo deve ser a queima de gordura, melhoria da resistência cardiovascular, e desenvolvimento de força e funcionalidade. O treino funcional será baseado em movimentos compostos, que ajudam a queimar mais calorias e aumentar a eficiência do corpo.

Divisão do Treino (ABC)
Treinando 3 vezes por semana, vamos dividir o plano por grupos musculares, combinando diferentes movimentos funcionais que trabalham tanto a parte cardiovascular quanto a força.

Dia 1: Parte Superior do Corpo + Cardio Funcional
Aquecimento (5-10 minutos):

Polichinelos
Corrida no lugar com elevação de joelhos
Treino (3-4 séries de 12-15 repetições):

Flexão de braços (foco em peitoral, tríceps e ombros)
Remada invertida em barra ou TRX (foco nas costas)
Press Militar com halteres ou kettlebell (ombros)
Prancha com deslocamento lateral (abdômen e estabilidade)
Burpees (treino funcional para todo o corpo e cardio)
Finalização (2-3 séries de 30 segundos):

Mountain Climbers
Battle Rope (se disponível) ou saltos em caixa
Dia 2: Parte Inferior do Corpo + Core
Aquecimento (5-10 minutos):

Agachamentos com peso corporal
Passada (lunges) dinâmicas
Treino (3-4 séries de 12-15 repetições):

Agachamento com peso ou kettlebell (glúteos e quadríceps)
Passada com step-up (trabalha pernas e equilíbrio)
Deadlift Romeno (isquiotibiais e glúteos)
Swing com kettlebell (força e explosão)
Prancha com elevação de perna (abdômen e core)
Finalização (2-3 séries de 30 segundos):

Prancha lateral
Skater Jumps (cardio e pernas)
Dia 3: Corpo Inteiro Funcional + HIIT
Aquecimento (5-10 minutos):

Corda
Agachamento com salto
Treino HIIT Funcional (3-4 séries de 30 segundos de esforço com 15 segundos de descanso):

Burpees
Levantamento terra com kettlebell
Agachamento com salto
Arremesso de bola medicinal (se disponível)
Corrida no lugar com elevação de joelhos
Finalização (2-3 séries de 30 segundos):

Corrida lateral com cones ou objetos
Agachamento sumô com elevação de peso
Dicas Gerais
Descanso: Mantenha 1-2 dias de descanso entre os treinos, mas tente incluir caminhadas ou atividades leves nos dias de folga para manter o corpo ativo.
Alimentação: Para o biotipo endomorfo, a dieta deve ser focada em controle de calorias, com ênfase em proteínas magras, vegetais, e carboidratos de baixo índice glicêmico.
Cardio Adicional: Considere adicionar sessões leves de cardio nos dias de descanso, como caminhadas ou ciclismo leve, para auxiliar na queima de gordura.