# Embedding Company Name

### Resumo 

Este trabalho é uma resposta ao [Case de embeddings](https://github.com/CaioMar/case_data_science_embeddings) do Caio Martins 


### Metodo
Este Estudo foi dividido em três partes
1. pré-processamento dos dados no arquivo `preprocess.ipynb`.
Limpeza de palavras, normalização. 
2. treinamento e validação do modelo fasttext `model_train.ipynb`
3. treinamento e validação do modelo biencoders `model_train_biencoders.ipynb`
4. o arquivo `teste_avaliação.ipynb` é a maneira mais rápida de executar o modelo. basta alterar o nome da fonte dos dados e rodar o notebook 

### Resultados 

* fasttext
```
============================================================
Top-1 Accuracy: 0.4931
Top-5 Accuracy: 0.7535
============================================================
```
* bert
``` 
============================================================
Acurácia Top-1: 0.5710
Acurácia Top-5: 0.8404
============================================================
```

### Informaçoes complementares

* versoes das bibliotecas utilizadas, disponível em `bibliotecas.md`

### Modelos Criados .zip

* Fasttext
[modelo](https://www.4shared.com/folder/AgIItsxV/Modelo-fasttext.html)

* Bert
[bert-bi-encoder](https://www.4shared.com/s/fl4VZLvZ1ku)

### Modelos de treinamento

* FastText
  [Modelo em PT 7GB descompactado](https://dl.fbaipublicfiles.com/fasttext/vectors-crawl/cc.pt.300.bin.gz)

* BERT
  [Modelo em PT-Br 1.7GB](https://huggingface.co/neuralmind/bert-base-portuguese-cased/tree/main)

### Referências

* Statquest - Neural Networks
  [Redes neurais - parte 1: Dentro da caixa preta](https://www.youtube.com/watch?v=CqOfi41LfDw&list=PLblh5JKOoLUIxGDQs4LFFD--41Vzf-ME1&index=2)
  [Gradiente descendente, passo a passo](https://www.youtube.com/watch?v=sDv4f4s2SB8&list=PLblh5JKOoLUIxGDQs4LFFD--41Vzf-ME1&index=4)
  [Redes Neurais Pt. 2: Ideias principais de retropropagação](https://www.youtube.com/watch?v=IN2XmBhILt4&list=PLblh5JKOoLUIxGDQs4LFFD--41Vzf-ME1&index=5)
  [Neural Networks Pt. 4: Multiple Inputs and Outputs](https://www.youtube.com/watch?v=83LYR-1IcjA&list=PLblh5JKOoLUIxGDQs4LFFD--41Vzf-ME1&index=9)
  [Neural Networks Part 5: ArgMax and SoftMax](https://www.youtube.com/watch?v=KpKog-L9veg&list=PLblh5JKOoLUIxGDQs4LFFD--41Vzf-ME1&index=10)
  [The SoftMax Derivative, Step-by-Step](https://www.youtube.com/watch?v=M59JElEPgIg&list=PLblh5JKOoLUIxGDQs4LFFD--41Vzf-ME1&index=11)
  [Neural Networks Part 6: Cross Entropy](https://www.youtube.com/watch?v=6ArSys5qHAU&list=PLblh5JKOoLUIxGDQs4LFFD--41Vzf-ME1&index=12)
  [Word Embedding e Word2Vec, claramente explicados](https://www.youtube.com/watch?v=viZrOnJclY0)

* Code basics
  [https://www.youtube.com/watch?v=Br-Ozg9D4mc](https://www.youtube.com/watch?v=Br-Ozg9D4mc)

* Data ICMC
  [Transfer Learning com o BERT em PT-BR](https://www.youtube.com/watch?v=kRyOAapLpIo)

* Jay Lammar - Github
  [The Illustrated BERT, ELMo, and co. (How NLP Cracked Transfer Learning)](https://jalammar.github.io/illustrated-bert/)
  [A Visual Guide to Using BERT for the First Time](https://jalammar.github.io/a-visual-guide-to-using-bert-for-the-first-time/)
