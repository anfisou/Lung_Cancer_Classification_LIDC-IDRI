# English Version

This project was developed for the subject 'Laboratório de IACD' by the students [André Sousa](https://github.com/anfisou), [David Scarin](https://github.com/davidmscarin), [Paulo Silva](https://github.com/WrekingPanda) and [Pedro Sousa](https://github.com/TottyAmadeus).

The project consists of using Computerized Tomography (CT) images as input data to build one or more learning models capable of classifying new images as i.e. predicting whether there is a malignant nodule on the scan or not.

The input data is obtained from the Lung Image Database Consortium image collection (LIDC-IDRI), a public dataset of thoracic CT scans. Utilizing python open source libraries (namely pylidc and pyradiomics) we were able to extract from the scans in this dataset several features and a label which we use to train and developed various machine learning algorithms.

Our main objective is to develop an algorithm that not only generalizes well to unseen data (meaning it performs well at classifying new images) but also treat the available data so that the classification task is much simpler.

We used various normalization techniques, a Random Forest to select the most important features, as well as, different target data. We also employed multiple models, such as K-Nearest Neighbors, Support Vector Machines and Neural Networks.

The final version of the work developed is specified in the following files:

- main_notebook.ipynb - jupyter notebook, collection of the code progress along with comments and explanations
- extracted features.CSV - CSV of the combined data (pylidc and pyradiomics, all patients)


# Versão Portuguesa

Este projeto foi desenvolvido no âmbito da unidade curricular 'Laboratório de IACD' pelos alunos [André Sousa](https://github.com/anfisou), [David Scarin](https://github.com/davidmscarin), [Paulo Silva](https://github.com/WrekingPanda) e [Pedro Sousa](https://github.com/TottyAmadeus).

O projeto consiste em utilizar imagens de Tomografia Computadorizada (TC) como dados de input para construir um ou mais modelos capazes de classificar novas imagens, ou seja, prever se há ou não um nódulo maligno no exame.

Os dados de input são obtidos da coleção de imagens do Lung Image Database Consortium (LIDC-IDRI), um conjunto de dados público de exames de TAC's toráxicos. Utilizando bibliotecas open source em Python (nomeadamente pylidc e pyradiomics), conseguimos extrair dos exames, um conjunto de dados com várias características e os sues resultados que usamos para treinar e desenvolver vários algoritmos.

Nosso principal objetivo é desenvolver um algoritmo que não apenas se generalize bem a dados não vistos (ou seja, que consiga classificar corretamente novas imagens), mas também tratar dos dados disponíveis de forma a que a tarefa de classificação seja muito mais simples.

Utilizamos diversas técnicas de normalização, um Random Forest para selecionar as características mais importantes, assim como diferentes diferentes distribuições de resultados. Também empregamos vários modelos, como K-Nearest Neighbors, Support Vector Machines e Redes Neurais.

A versão final do trabalho desenvolvido está disponível nos seguintes ficheiros:

- main_notebook.ipynb - jupyter notebook, progressão do código, comentado e explicado
- extracted features.CSV - CSV com os dados extraídos (pylidc e pyradiomics de todos os patients)
