# Processamento de Imagens — Aula 4

Notebook com exercícios de **visualização de imagens de exemplo** da biblioteca `scikit-image` e de **filtragem espacial** com OpenCV.

## Conteúdo

- Visualização de imagens de teste: astronauta, gato, café, lua, câmera, retina e outras.
- Geração de uma galeria das imagens disponíveis em `skimage.data`.
- Visualização de fatias de coleções volumétricas.
- Comparação entre a imagem original e filtros de suavização, média, detecção de bordas e nitidez.

## Notebook

**[Proc_Img_Aula_4.ipynb](./Proc_Img_Aula_4.ipynb)**

O arquivo contém **18 figuras de resultado salvas**, de modo que podem ser visualizadas diretamente no GitHub, sem executar as células. As imagens de resultado foram comprimidas para tornar o notebook mais leve.

## Dependências

Python com `numpy`, `matplotlib`, `opencv-python` e `scikit-image`.

As imagens de teste são carregadas por `skimage.data`, sem exigir arquivos locais. Algumas coleções podem demandar downloads adicionais, memória significativa ou tempo de processamento ao executar todas as células.

## Correções feitas na organização

- Nome de arquivo padronizado para o nome da branch.
- Títulos e seções adicionados para facilitar a leitura.
- Kernel de média corrigido para **5×5 com pesos normalizados** (em vez de 4×5 sem normalização), evitando a saturação desnecessária.
- Gráficos dos filtros recalculados após a alteração; os demais resultados de imagem foram preservados.

> **Nota sobre a numeração:** esta aula foi colocada na primeira branch de aula livre após as aulas já preenchidas. A correspondência com o número real da aula não consta do arquivo original.
