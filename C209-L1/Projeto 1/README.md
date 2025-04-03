# Trabalho Prático - Computação Gráfica e Multimídia

**Disciplina:** C209 - L1 - Computação Gráfica e Multimídia  
**Nome:** Pedro Vilas Boas Vasconcelos  
**Matrícula:** 427 - Ges
**Período:** Sétimo

---

## Descrição do Projeto:

O trabalho consiste em modificar uma imagem inicial utilizando técnicas de computação gráfica.

As seguintes etapas foram feitas **nesta ordem**:

1. **Juntar todas as imagens em uma única**
2. **Trocar as cores** (alterar a cor dos pinguins para cores diferentes)
3. **Aplicar o espelhamento**
4. **Recortar seu pinguim favorito** (descartar os outros, deixando apenas um na imagem)
5. **Analisar o histograma** do pinguim recortado e escolher um valor de threshold (justificar a escolha)
6. **Aplicar uma conversão** para que todos os píxeis abaixo do pinguim sejam pintados de roxo

Cada etapa foi feita utilizando o resultado da etapa anterior como base.

---

## Estrutura do Repositório:

- [Projeto 1]/
  -img/
    - imagens necessárias
  - pinguins_juntos.png
  - imagem_recolorida.png
  - imagem_espelhada.png
  - pinguim_segundo_quadrante.png
  - Projeto1_C209-L1.ipynb

**Organização das Imagens:**
Cada imagem resultante de uma etapa está sendo mostrada ao final de seu treixo de codigo:

- `questao 1/` - pinguins_juntos.png - Imagem combinada
- `questao 2/` - imagem_recolorida.png - Imagem com cores alteradas
- `questao 3/` - imagem_espelhada.png - Imagem espelhada
- `questao 4/` - pinguim_segundo_quadrante.png - Pinguim recortado
- `questao 5/` - Análise do histograma
- `questao 6/` - pinguim_colorido.png - Conversão de cor aplicada

As imagens são fundamentais para validar o processo realizado em cada etapa.
