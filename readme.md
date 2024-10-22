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

Você é um personal trainer e precisa me ajudar a montar um treino de acordo com as regras que eu irei passar. Identifique o biótipo corporal informado, dias disponíveis na semana para treinar e tipos de exercícios favoritos(Escolha do Usuário):

- Biótipos -> Ectomorfo, Mesomorfo e Endomorfo. 
- Dias disponíveis na semana -> 1 dia: Treino Fullbody, 3 dias: Treino ABC, 5 dias: Treino ABCDE.
- Tipos de exercícios -> Máquinario, Peso Livre, Cardio e HIIT.
------------------------------------------------------------------------
Resposta do  Usuário ->
- Biótipo: Ectomorfo.
- Dias disponíveis na semana: 5 dias.
- Tipos de exercícios: Peso livre, Máquinario e cardio. 

## Resposta 

Com base nas informações fornecidas, vamos montar um treino focado em te ajudar a ganhar massa muscular, considerando suas características de ectomorfo e suas preferências por exercícios.

Objetivo: Ganho de massa muscular e força.

Frequência: 5 vezes por semana (treino ABCDE).

Tipos de exercício: Peso livre, máquinas e cardio.

Considerações importantes para ectomorfos:

* Nutrição: É fundamental consumir uma quantidade adequada de calorias e proteínas para promover o crescimento muscular.
* Descanso: O descanso é crucial para a recuperação muscular.
* Intensidade: Os treinos devem ser intensos, com foco em movimentos compostos e cargas progressivas.

## Sugestão de Treino:

Dia 1: Peito e Tríceps
* Supino reto com barra: 3 séries de 8-12 repetições
* Supino inclinado com halteres: 3 séries de 10-12 repetições
* Crucifixo declinado: 3 séries de 12-15 repetições
* Desenvolvimento com halteres: 3 séries de 10-12 repetições
* Triceps testa: 3 séries de 12-15 repetições
* Extensão de tríceps na polia: 3 séries de 12-15 repetições

Dia 2: Costas e Bíceps
* Pull-up: 3 séries até a falha
* Remada curvada com barra: 3 séries de 8-12 repetições
* Remada unilateral com halteres: 3 séries de 10-12 repetições por lado
* Rosca direta com barra: 3 séries de 10-12 repetições
* Rosca concentrada: 3 séries de 12-15 repetições
* Barra fixa: 3 séries até a falha

Dia 3: Pernas
* Agachamento livre: 3 séries de 8-12 repetições
* Leg press: 3 séries de 10-12 repetições
* Stiff: 3 séries de 12-15 repetições
* Extensão de joelho: 3 séries de 12-15 repetições
* Flexão de joelho: 3 séries de 12-15 repetições

Dia 4: Ombros
* Desenvolvimento com halteres acima da cabeça: 3 séries de 8-12 repetições
* Elevação lateral: 3 séries de 12-15 repetições
* Remada alta: 3 séries de 10-12 repetições


Dia 5: Cardio e Abdômen
* Corrida ou bicicleta: 30 minutos
* Plank: 3 séries de 30 segundos a 1 minuto
* Abdominal superior: 3 séries de 15-20 repetições
* Abdominal inferior: 3 séries de 15-20 repetições
* Russian twist: 3 séries de 20-25 repetições

Observações:
* Aquecimento: Realize um aquecimento de 5-10 minutos antes de cada treino, incluindo exercícios leves e alongamento.
* Descanso entre as séries: Descanse cerca de 1-2 minutos entre as séries.
* Progressão de carga: Aumente gradualmente a carga dos exercícios para continuar desafiando seus músculos.
* Varie os exercícios: A cada 4-6 semanas, varie os exercícios para evitar o platô e estimular o crescimento muscular.
* Nutrição: Consulte um nutricionista para montar um plano alimentar personalizado.
