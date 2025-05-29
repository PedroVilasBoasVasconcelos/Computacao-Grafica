
# 🎬 Projeto 2 — Manipulação de Vídeo com Python

Este projeto tem como objetivo aplicar técnicas de edição e manipulação de vídeos utilizando a biblioteca **MoviePy**, juntamente com conceitos abordados em sala de aula. Foram realizados efeitos como espelhamento, alteração de áudio e reordenação dos trechos do vídeo.

---

## 📑 Descrição do Projeto

O projeto é dividido em três etapas principais de transformação do vídeo original, aplicando diferentes técnicas de edição:

---

## 🧠 Etapas do Projeto

### 1️⃣ 📊 **Análise do Vídeo**

- O vídeo base utilizado se chama `Video_Projeto2.mp4`.
- São analisadas as características principais do vídeo:
  - ✅ Tamanho (resolução)
  - ✅ FPS (quadros por segundo)
  - ✅ Duração total
  - ✅ Número de frames

Essa etapa é essencial para entender como serão aplicados os efeitos.

---

### 2️⃣ 🔍 **Espelhamento Horizontal a Cada 20 Segundos**

- O vídeo é dividido em blocos de **20 segundos**.
- Cada bloco **par** recebe um efeito de **espelhamento horizontal (mirror_x)**.
- Ao final, os blocos são reunidos para gerar um novo vídeo.

✔️ Arquivo gerado: `VP_espelhado_20_a_20.mp4`

---

### 3️⃣ 🔊 **Redução Gradual do Volume e Silenciamento Final**

- O vídeo espelhado é dividido em blocos de **30 segundos**.
- O volume de cada bloco é reduzido para **20%** do volume original.
- Nos **últimos 10 segundos**, o áudio é completamente silenciado.

✔️ Arquivo gerado: `VP_volume_reduzido_e_mudo.mp4`

---

### 4️⃣ ✂️ **Corte e Reorganização dos Trechos**

- O vídeo é cortado em três partes:
  - 🕑 Do início até 60 segundos.
  - 🕓 De 80 segundos até o final.
  - 🕒 De 60 a 80 segundos.
- As partes são reorganizadas na seguinte ordem:
  - 1️⃣ Início → 60 segundos
  - 2️⃣ De 80 até o final
  - 3️⃣ De 60 até 80 (movido para o final)

✔️ Arquivo gerado: `VP_corte_e_reorganizado.mp4`

---

## 🚀 Como Executar

1. 🔗 Clone o repositório:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

2. 📁 Acesse a pasta do projeto:

```bash
cd seu-repositorio
```

3. 🔧 Instale as dependências necessárias:

```bash
pip install moviepy==1.0.3 numpy
```

4. ▶️ Execute o script:

```bash
python projeto2.py
```

---

## ⚠️ Observações Importantes

- É recomendado utilizar a versão `1.0.3` do **MoviePy** para garantir total compatibilidade.
- Verifique se o arquivo `Video_Projeto2.mp4` está na mesma pasta do script antes de executar.

---

## 🎯 Resultado Final

Ao final da execução, você terá três vídeos com os seguintes efeitos aplicados:

| Arquivo                         | Descrição                                  |
| ------------------------------- | ------------------------------------------- |
| `VP_espelhado_20_a_20.mp4`       | Efeito de espelhamento horizontal a cada 20 segundos |
| `VP_volume_reduzido_e_mudo.mp4`  | Redução de volume a cada 30 segundos e silêncio nos últimos 10 segundos |
| `VP_corte_e_reorganizado.mp4`    | Corte e reorganização dos trechos do vídeo |

---

## 🧠 Tecnologias Utilizadas

- Python 🐍
- Biblioteca [MoviePy](https://zulko.github.io/moviepy/) 🎥
- NumPy 🔢

---

## 💻 Feito por

Pedro Vilas Boas Vasconcelos 💙
