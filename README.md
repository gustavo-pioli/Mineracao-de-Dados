# Classificação de Termogramas Mamários — ViT vs. CNN



Projeto final da disciplina de Mineração de Dados. Aplica um pipeline de mineração de dados e aprendizado profundo sobre a base pública \*\*DMR-IR\*\* (termogramas mamários), comparando um modelo \*\*Vision Transformer (ViT-Tiny)\*\* com uma \*\*CNN (DenseNet121)\*\* para classificação binária (Healthy vs. Sick), incluindo uma etapa de balanceamento de classes via `WeightedRandomSampler`.



> Todo o desenvolvimento e treinamento dos modelos foi feito no \*\*Google Colab\*\*, utilizando GPU gratuita fornecida pela plataforma.



## Conteúdo do repositório



- `Projeto\_Mineração\_Análise\_+\_VIT.ipynb` — treinamento do ViT (configuração sem balanceamento).

- `Projeto\_Mineração\_CNN.ipynb` — treinamento da DenseNet121 (configuração sem balanceamento).

- `Projeto\_Mineração\_VIT\_Balanceamento.ipynb` — treinamento do ViT com `WeightedRandomSampler`.

- `Projeto\_Mineração\_CNN\_Balanceamento.ipynb` — treinamento da DenseNet121 com `WeightedRandomSampler`.

- `relatorio/` — artigo final no formato IEEE (`.tex` + figuras).



## Como executar



1. Abra o notebook desejado no \[Google Colab](https://colab.research.google.com/).

2. Ative o ambiente de execução com GPU (\*\*Ambiente de execução > Alterar tipo de ambiente de execução > GPU\*\*).

3. Monte seu Google Drive contendo a base DMR-IR (as imagens térmicas organizadas por paciente).

4. Execute as células em ordem.



## Base de dados



[DMR-IR — Database for Mastology Research with Infrared Image](http://visual.ic.uff.br/dmi/), disponibilizada pelo projeto PROENG.

