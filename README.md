# CP l - APPLIED COMPUTER VISION

**RM:** preencher com o RM

**Repositório:** [github.com/guicvsub/CPl-APPLIED-COMPUTER-VISION](https://github.com/guicvsub/CPl-APPLIED-COMPUTER-VISION)

## Descrição

Atividade de Visão Computacional utilizando Python, OpenCV, NumPy e Matplotlib.

O projeto aplica os filtros `Blur` e `GaussianBlur` em uma imagem. Depois, utiliza máscaras circulares para combinar a imagem original com as imagens desfocadas.

## Arquivos

- `atvidade_vc_revisada.ipynb`: notebook com o código da atividade.
- `lenna.jpg`: imagem utilizada no processamento.

## Como executar no VS Code

1. Clone o repositório:

```bash
git clone https://github.com/guicvsub/CPl-APPLIED-COMPUTER-VISION.git
```

2. Abra a pasta clonada no **VS Code**.

3. Instale a extensão **Jupyter** no VS Code.

4. Abra o arquivo `atvidade_vc_revisada.ipynb`.

5. Selecione um kernel Python no canto superior direito do notebook.

6. Execute as células em ordem usando o botão de execução de cada célula.

A imagem `lenna.jpg` deve permanecer na mesma pasta do notebook, na raiz do repositório.

## Opção: executar no Google Colab

Também é possível abrir o notebook diretamente pelo Google Colab:

[ Abrir notebook no Google Colab ](https://colab.research.google.com/github/guicvsub/CPl-APPLIED-COMPUTER-VISION/blob/main/atvidade_vc_revisada.ipynb)

Depois de abrir o notebook, envie o arquivo `lenna.jpg` para o ambiente do Colab e execute as células em ordem.

## Resultado

O resultado final combina:

- A imagem original no círculo menor;
- O efeito `GaussianBlur` no círculo maior;
- O efeito `Blur` no fundo da imagem.
