

# [Minicursos do SBBD 2022](https://sbbd.org.br/2022/minicursos-program/): Uso de Meta-Learning em Tarefas de Aprendizado Profundo

**DOI:** doi.org/10.5753/sbc.10309.7

---

## Abstract

*Deep Learning is a subarea of Machine Learning that uses neural networks with successive layers of data representation, which allow the performance of more complex tasks. Generally, these models produce better results when working with large volumes of data. However, in some situations, obtaining labeled data in large quantities for training these networks is not feasible. The meta-learning strategy aims to mitigate this problem, enabling learning models to learn quickly from other models initially trained for different tasks. This work introduces some meta-learning techniques, focusing on their use with Deep Learning models to solve tasks with fewer data.*

## Resumo

*Aprendizado Profundo é uma subárea de Aprendizado de Máquina que utiliza redes neurais com sucessíveis camadas de representação dos dados, as quais permitem a realização de tarefas mais complexas. Em geral, esses modelos produzem melhores resultados quando trabalhados com grandes volumes de dados. Entretanto, em algumas situações, não é possível obter dados rotulados em grande quantidade para o treinamento dessas redes. A estratégia de meta-learning visa mitigar esse problema, fazendo com que modelos de aprendizagem consigam aprender, de forma rápida, a partir de outros modelos inicialmente treinados para diferentes tarefas. Este trabalho introduz algumas técnicas de meta-learning, focando em seu uso com modelos de Aprendizado Profundo para a resolução de tarefas com quantidade de dados reduzida.*

## Apresentação & Drive

- [Apresentação de *slides*](https://docs.google.com/presentation/d/1hTtmbd_hydWP5a5AvTSQ72eB8u7hdOHnnYuOjOAVJyA/edit?usp=sharing) do minicurso feita no SBBD, dia 21 de Setembro de 2022.

## Dependências

- conda install -c anaconda python
- conda install -c anaconda jupyter
- pip install 'git+https://github.com/PyTorchLightning/lightning-flash.git'
- pip install 'git+https://github.com/PyTorchLightning/lightning-flash.git#egg=lightning-flash[image]'
- conda install -c anaconda scikit-learn
- pip install learn2learn
- pip install Pillow==7.1.2

## Citação

```
@article{do2022uso,
  title={Uso de Meta-Learning em Tarefas de Aprendizado Profundo},
  author={do R{\^e}go, Luis Gustavo Coutinho and Oliveira, B{\'a}rbara St{\'e}phanie Neves and Gaspar, Lucas Peres and Branco, Jo{\~a}o Ara{\'u}jo Castelo and de Mac{\^e}do, Jos{\'e} Ant{\^o}nio Fernandes},
  journal={Sociedade Brasileira de Computa{\c{c}}{\~a}o},
  year={2022}
}

```

## Autores
- [Gustavo Coutinho](https://github.com/gustavolgcr) - admin do curso, conteúdo e código
- [Bárbara Neves](https://github.com/barbaraneves) - conteúdo e código
- [Lucas Peres](https://github.com/lucaspg96) - conteúdo e código
- [João Castelo Branco](https://github.com/castelojb) - conteúdo e código
- Ticiana Linhares - conteúdo
- José Macêdo - conteúdo