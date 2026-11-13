# Processamento de Imagens — Aula 5

Conteúdo reconstruído a partir de uma exportação em PDF do Google Colab.

**Tema:** visualização de imagens de exemplo (`skimage.data`), suavização gaussiana, limiarização de Otsu, limiarização adaptativa gaussiana e detecção/numeração de contornos com OpenCV.

## Arquivos

- [`Proc_Img_Aula_5.ipynb`](./Proc_Img_Aula_5.ipynb): notebook **executado**, com figuras e saída de 24 contornos preservadas.
- [`Proc_Img_Aula_5.py`](./Proc_Img_Aula_5.py): o mesmo código em Python para consulta ou execução como script.

## Execução

Requer Python com `numpy`, `opencv-python`, `matplotlib` e `scikit-image`. No Colab, abra o `.ipynb` e execute todas as células. As imagens usadas são exemplos fornecidos por `skimage.data`, sem necessidade de upload manual.

## Observação sobre a reconstrução

O PDF cortou a parte final do comando `cv2.adaptiveThreshold(...)`. Foram usados `cv2.THRESH_BINARY, 101, -10`, parâmetros **reconstruídos por teste**, que reproduziram visualmente o resultado e a contagem de **24 contornos** mostrados no material. Não é possível confirmar que são exatamente os argumentos da versão original. O restante do código foi preservado em estrutura e finalidade.

A numeração **Aula 5 é provisória**: foi escolhida por ser a primeira branch livre, e não por constar no documento.