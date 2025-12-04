# Wave-Height-Prediction-Using-Linear-Regression-and-Random-Forest
O objetivo é construir um modelo rápido, interpretável e que demonstre domínio de aprendizado automático aplicado ao mar.

1. Introdução

A previsão de ondas é fundamental para navegação, operações navais, segurança de embarcações e planejamento costeiro. Embora modelos numéricos como o WaveWatch III (WW3) sejam amplamente utilizados, modelos simples de aprendizado de máquina também podem capturar relações básicas entre variáveis atmosféricas e a altura significativa de onda.

Este mini-projeto usa um dataset sintético, porém realista, para treinar modelos que estimam a altura da onda com base em:

velocidade do vento (m/s)

direção do vento (graus)

fetch (km) — distância sobre a qual o vento sopra

pressão atmosférica (hPa)

O objetivo é construir um modelo rápido, interpretável e que demonstre domínio de aprendizado automático aplicado ao mar.

2. Metodologia

Gerar dataset sintético inspirado em relações físicas conhecidas.

Separar treino e teste (80/20).

Treinar dois modelos:

Regressão Linear

Random Forest Regressor

Avaliar com RMSE e R².

Plotar valores reais vs previstos.
