# Analise-Acidentes-Rodoviarios_PRF_2025
# Acidentes nas Rodovias Federais Brasileiras (2025)
### O que torna um acidente mais letal?

Análise exploratória e diagnóstica dos dados abertos da **Polícia Rodoviária
Federal (PRF)** para identificar quais causas, horários, locais e condições
da via estão associados aos acidentes mais letais.

---

## Resumo

| Indicador | Valor |
|---|---|
| Acidentes analisados | 72.529 |
| Pessoas envolvidas | 177.479 |
| Mortes | 6.043 |
| Registros na base original | 584.010 |

**Métrica principal:** letalidade = mortes a cada 100 acidentes

---

## Principais achados

### 1. Contramão: a causa mais frequente e mortal
961 mortes e cerca de 39 mortes a cada 100 acidentes.

![Frequência x letalidade](imagens/frequencia_letalidade.png)

### 2. Os horários críticos seguem o ciclo do fim de semana
Picos na **sexta às 18h**, no **domingo às 19h** e na **segunda às 7h**.

![Mapa de calor](imagens/mapa_calor_dia_hora.png)

### 3. A noite tem menos acidentes, mas mata mais
A noite concentra 34% dos acidentes, mas **48% das mortes**: cada acidente
noturno é cerca de 2 vezes mais letal.

![Fase do dia](imagens/fase_dia_acidentes_mortes.png)

### 4. A pista simples é o fator mais associado à letalidade
Pistas simples têm 48% dos acidentes, mas **69% das mortes**. Entre os
estados, a correlação entre pista simples e letalidade é de **0,69**.

![Pista simples x letalidade](imagens/pista_simples_letalidade_uf.png)

### 5. Onde há mais acidentes não é onde se morre mais
Maranhão (22,3) e Pará (20,1) têm letalidade até **4 vezes maior** que
São Paulo (4,7). A BR-316 registra cerca de 16 mortes a cada 100 acidentes.

---

## Recomendações

- Priorizar a **duplicação** de rodovias de pista simples mais letais, especialmente no Norte e no Nordeste
- Reforçar a **fiscalização de ultrapassagens e contramão**
- Concentrar operações nas **janelas críticas** do fim de semana
- **Combater a fadiga ao volante** com pontos de parada e campanhas noturnas
- Melhorar a **segurança de pedestres** nos trechos urbanos

---

## Limitações

- A base cobre apenas **rodovias federais**
- **Correlação não é causalidade:** outros fatores também influenciam a letalidade
- Estados com poucos acidentes têm taxas mais instáveis
- A análise considera apenas o ano de 2025

---

## Ferramentas

Python · pandas · matplotlib · seaborn · Google Colab

## Estrutura do repositório


