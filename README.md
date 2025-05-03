# Jogo Dinossauro com IA

Este projeto recria o clássico jogo do dinossaurinho do Chrome, onde um algoritmo de **inteligência artificial (IA)** joga o jogo de forma autônoma. A IA é treinada para reconhecer os obstáculos do jogo (como cactos e pássaros) e realizar as ações necessárias para evitar colisões, como saltar ou agachar.

Esse projeto foi feito por [Nicholas Renotte](https://www.youtube.com/watch?v=vahwuupy81A)

## Objetivo

O objetivo principal deste projeto é aplicar técnicas de **Machine Learning** para treinar um modelo de IA que possa jogar o Jogo do Dinossauro de forma eficaz, sem intervenção humana. O projeto visa explorar conceitos de aprendizado por reforço, onde a IA aprende a tomar decisões com base em recompensas e penalidades.

## Estrutura do Projeto

1. **Captura de Tela**: Usando OpenCV para capturar a tela do jogo e identificar os obstáculos (cactos, pássaros).
2. **Modelo de IA**: Um modelo baseado em aprendizado por reforço (sendo nesse caso DQN) é treinado para tomar decisões (pular ou não pular) com base nas observações do jogo.
3. **Treinamento da IA**: A IA é treinada utilizando feedback do jogo para melhorar a sua performance.
4. **Execução**: A IA joga o jogo automaticamente, aplicando o conhecimento adquirido durante o treinamento.

## Como Rodar o Projeto

### Instalação

1. Clone o repositório:

   ```bash

   git clone https://github.com/MatheusPolletti/jogoDinossauroIa.git

   cd jogoDinossauroIa

   code .
