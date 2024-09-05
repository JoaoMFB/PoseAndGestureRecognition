# Análise de Poses com MediaPipe

Este projeto utiliza a biblioteca MediaPipe da Google para detectar e analisar poses corporais e movimentos das mãos em tempo real. O código faz uso dos modelos `Holistic` e `DrawingUtils` para detectar e visualizar landmarks do corpo humano, com foco na identificação de poses específicas e movimentos das mãos.

## Funcionalidades

1. **Detecção de Poses Inferiores e Superiores:**
   - **Membros Inferiores:** Identifica se a perna direita ou esquerda está levantada.
   - **Membros Superiores:** Detecta se uma pose específica (como um braço estendido) está sendo realizada e verifica se o dedo médio está levantado.

2. **Visualização:**
   - Desenha pontos e conexões entre landmarks detectados no vídeo da câmera.
   - Exibe mensagens de texto na tela para indicar quando uma pose ou movimento específico é detectado.

## Requisitos

Certifique-se de que você tenha as seguintes bibliotecas instaladas:

- `mediapipe`
- `opencv-python`

Você pode instalar as bibliotecas necessárias usando o pip:

```bash
pip install mediapipe opencv-python
