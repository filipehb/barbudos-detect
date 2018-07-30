# Rede neural para reconhecimento de homens barbudos

Nasceu com base em uma bricadeira para alguns colegas do trabalho e como aprendizagem de IA.

Faz uso de aprendizagem supervisionada de máquina, ou mais especificamente, [CNN](https://en.wikipedia.org/wiki/Convolutional_neural_network) para classificação de imagens.

### Requisitos

Instale as libs que são usadas no projeto.

```
pip install -r requirements.txt
```

Crie as pastas para o nosso dataset.

/dataset/test_set<br/>
/dataset/test_set/barbudo<br/>
/dataset/test_set/nao_barbudo<br/><br/>

/dataset/train_set<br/>
/dataset/train_set/barbudo<br/>
/dataset/train_set/nao_barbudo<br/>

Pegue diversas imagens de homens com barba e sem barba no formato .jpg e mova elas para suas respectivas pastas (É importante ter uma boa quantidade (~60) em todas as pastas).

### Execução

Execute o [Jupyter notebook](http://jupyter.org/).

```
jupyter notebook
```

e abra o arquivo barbudos_prediction.ipynb

## Referências

https://becominghuman.ai/building-an-image-classifier-using-deep-learning-in-python-totally-from-a-beginners-perspective-be8dbaf22dd8
