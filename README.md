# Curso de aprendizado de máquina em sistemas embarcados 
_Tiny Machine Learning - TinyML_
###### Professora: [Rosana Rego](https://github.com/roscibely)
--- 

Este repositório abriga uma coleção de slides, material de leitura, solicitações de projetos e exemplos para você começar a criar seu próprio projeto de aprendizado de máquina em sistema embarcado.

### Pré requisitos 

Os alunos devem estar familiarizados com os seguintes tópicos para completar os exemplos de perguntas e tarefas práticas:

* Álgebra
    - Resolvendo equações lineares
* Probabilidade e Estatística
    - Expressando probabilidades de eventos independentes
     - Distribuições normais
     - Média e mediana
* Programação
    - Programação Arduino/C++ (condicionais, loops, arrays/buffers, ponteiros, funções)
    - Programação Python (condicionais, loops, arrays, funções, NumPy)

### Hardware e Software Necessários

Os alunos precisarão de um computador e acesso à Internet para realizar treinamento em modelo de aprendizado de máquina e exercícios práticos com o Edge Impulse Studio e o Google Colab.

* É necessária uma conta do Google para o [Google Colab](https://colab.research.google.com/).

* Um Edge Impulse é necessário para o [Edge Impulse Studio](https://edgeimpulse.com/).

* Os alunos precisarão instalar o [Arduino IDE](https://www.arduino.cc/en/software) mais recente.

## Cronograma de Estudos 

* [Módulo 1: Machine Learning embarcado](#módulo-1-machine-learning-embarcado)
* [Módulo 2: Iniciando com Deep Learning](#módulo-2-iniciando-com-deep-learning)
* [Módulo 3: Fluxo de trabalho com Machine Learning](#módulo-3-fluxo-de-trabalho-com-machine-learning)
* [Módulo 4: Implantação de modelos](#módulo-4-implantação-de-modelos)
* [Módulo 5: Prática Detecção de anomalia](#módulo-5-prática-detecção-de-anomalia)
* [Módulo 6: Classificação de imagens com aprendizado profundo](#módulo-6-classificação-de-imagens-com-aprendizado-profundo)
* [Módulo 7: Detecção de objetos e segmentação de imagens](#módulo-7-detecção-de-objetos-e-segmentação-de-imagens)

### Material de apoio

* [Curso TinyML](https://www.coursera.org/learn/introduction-to-embedded-machine-learning?action=enroll)
* [Arduino Nano 33 BLE Sense](https://docs.edgeimpulse.com/docs/development-platforms/officially-supported-mcu-targets/arduino-nano-33-ble-sense#connecting-an-off-the-shelf-ov7675-camera-module)

--- 


### Módulo 1: Machine Learning Embarcado

### Módulo 2: Iniciando com Deep Learning

### Módulo 3: Fluxo de trabalho com Machine Learning

### Módulo 4: Implantação de modelos

Este módulo aborda as etapas para implantar um modelo de machine learning treinado no _Edge Impulse_ em uma placa Arduino. 

* Objetivos 
    - Forneça exemplos de como o aprendizado de máquina embarcado pode ser usado para resolver problemas (onde outras formas de aprendizado de máquina seriam limitadas ou inadequadas);
    - Descrever os desafios associados à execução de algoritmos de aprendizado de máquina em sistemas embarcados 
    - Descreva amplamente o que acontece durante o treinamento do modelo de aprendizado de máquina;
    - Demonstrar a capacidade de realizar inferência em um sistema embarcado para resolver um problema.



#### Microcontroladores embarcados

##### Material

| ID | Descrição | Links | Fonte |
|----|-------------|:-----:|:-----------:|
| 4.1.1 | Sistemas embarcados | [slides](Module%204%20-%20Model%20Deployment/4.2.1.embedded-systems.3.pptx?raw=true) | [[3]](#3-slides-and-written-material-for-tinyml-courseware-by-harvard-university-is-licensed-under-cc-by-nc-sa-40) |
| 4.1.2 | Diversidade de sistemas embarcados | [doc](Module%204%20-%20Model%20Deployment/4.2.2.diversity-of-embedded-systems.3.docx?raw=true) | [[3]](#3-slides-and-written-material-for-tinyml-courseware-by-harvard-university-is-licensed-under-cc-by-nc-sa-40) |
| 4.1.3 | Hardware de computação embarcado| [slides](Module%204%20-%20Model%20Deployment/4.2.3.embedded-computing-hardware.3.pptx?raw=true) | [[3]](#3-slides-and-written-material-for-tinyml-courseware-by-harvard-university-is-licensed-under-cc-by-nc-sa-40) |
| 4.1.4 | Microcontroladores | [doc](Module%204%20-%20Model%20Deployment/4.2.4.embedded-microcontrollers.3.docx?raw=true) | [[3]](#3-slides-and-written-material-for-tinyml-courseware-by-harvard-university-is-licensed-under-cc-by-nc-sa-40) |
| 4.1.5 | TinyML kit peripherals | [doc](Module%204%20-%20Model%20Deployment/4.2.5.tinyml-kit-peripherals.3.docx?raw=true) | [[3]](#3-slides-and-written-material-for-tinyml-courseware-by-harvard-university-is-licensed-under-cc-by-nc-sa-40) |
| 4.1.6 | TinyML kit peripherals | [slides](Module%204%20-%20Model%20Deployment/4.2.6.tinyml-kit-peripherals.3.pptx?raw=true) | [[3]](#3-slides-and-written-material-for-tinyml-courseware-by-harvard-university-is-licensed-under-cc-by-nc-sa-40) |
| 4.1.7 | Arduino core, frameworks, mbedOS, and bare metal | [doc](Module%204%20-%20Model%20Deployment/4.2.7.arduino-core-frameworks-mbedos-and-bare-metal.3.docx?raw=true) | [[3]](#3-slides-and-written-material-for-tinyml-courseware-by-harvard-university-is-licensed-under-cc-by-nc-sa-40) |
| 4.1.8 | Software de ML embarcados | [slides](Module%204%20-%20Model%20Deployment/4.2.8.embedded-ml-software.3.pptx?raw=true) | [[3]](#3-slides-and-written-material-for-tinyml-courseware-by-harvard-university-is-licensed-under-cc-by-nc-sa-40) |

#### Implantando um modelo em uma placa Arduino

##### Material

| ID | Descrição | Links | Fonte |
|----|-------------|:-----:|:-----------:|
| 4.2.1 | Usando um modelo para inferência | [video](https://www.youtube.com/watch?v=UKeZFIqMk2U&list=PL7VEa1KauMQqZFj_nWRfsCZNXaBbkuurG&index=18) [slides](Module%204%20-%20Model%20Deployment/4.3.1.using-a-model-for-inference.1.pptx?raw=true) | [[1]](#1-slides-and-written-material-for-introduction-to-embedded-machine-learning-by-edge-impulse-is-licensed-under-cc-by-nc-sa-40) |
| 4.2.2 | Testando inferência com um smartphone | [video](https://www.youtube.com/watch?v=OWakb-oDAOg&list=PL7VEa1KauMQqZFj_nWRfsCZNXaBbkuurG&index=19) | [[1]](#1-slides-and-written-material-for-introduction-to-embedded-machine-learning-by-edge-impulse-is-licensed-under-cc-by-nc-sa-40) |
| 4.2.3 | Implantar modelo no Arduino | [video](https://www.youtube.com/watch?v=uUh61R8Hu0o&list=PL7VEa1KauMQqZFj_nWRfsCZNXaBbkuurG&index=20) [slides](Module%204%20-%20Model%20Deployment/4.3.3.deploy-model-to-arduino.1.pptx?raw=true) | [[1]](#1-slides-and-written-material-for-introduction-to-embedded-machine-learning-by-edge-impulse-is-licensed-under-cc-by-nc-sa-40) |
| 4.2.4 | Implantar modelo no Arduino | [tutorial](https://docs.edgeimpulse.com/docs/deployment/running-your-impulse-arduino) | |


### Módulo 5: Prática Detecção de anomalia

### Módulo 6: Classificação de imagens com aprendizado profundo

### Módulo 7: Detecção de objetos e segmentação de imagens


### Fontes

<!-- omit in toc -->
 [1] Slides and written material for "[Introduction to Embedded Machine Learning](https://www.coursera.org/learn/introduction-to-embedded-machine-learning)" by [Edge Impulse](https://edgeimpulse.com/) is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

<!-- omit in toc -->
 [2] Slides and written material for "[Computer Vision with Embedded Machine Learning](https://www.coursera.org/learn/computer-vision-with-embedded-machine-learning)" by [Edge Impulse](https://edgeimpulse.com/) is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

<!-- omit in toc -->
 [3] Slides and written material for "[TinyML Courseware](https://github.com/tinyMLx/courseware)" by Prof. Vijay Janapa Reddi of [Harvard University](http://tinyml.seas.harvard.edu/) is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

---
<div>
  <img src="https://github.com/roscibely/algorithms-and-data-structure/blob/develop/root/ufersa.jpg" width="900" height="250">
</div>
<i>UFERSA - Campus Pau dos Ferros</i>
