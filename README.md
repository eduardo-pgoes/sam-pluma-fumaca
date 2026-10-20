# Segmentação de pluma de fumaça com SAM

<a href="https://colab.research.google.com/github/eduardo-pgoes/sam-pluma-fumaca/blob/main/sam_pluma_fumaca.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

Notebook: [`sam_pluma_fumaca.ipynb`](sam_pluma_fumaca.ipynb)

Segmenta a pluma de fumaça de `data/pluma.jpeg` com o Segment Anything Model (ViT-H), compara cinco configurações de prompts (caixa, pontos positivos, positivos + negativos e prompts gerados automaticamente a partir de uma regra de cor), mede cobertura e inclusões indevidas e analisa como iluminação, contraste e a semelhança entre fumaça e nuvens afetam o resultado.

Máscara final: `outputs/mascara_final.png` · sobreposição: `outputs/sobreposicao_final.png`
