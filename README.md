# hse_hw2_chip

Ссылка на colab: https://colab.research.google.com/drive/1jqkiI0GwQ60wKy6urOtTWYrZhUWCTCE4?usp=sharing

Что выдал FastQC (полные отчеты есть в файлах):

ENCFF698KIR

<image src="/src/Screenshot from 2023-03-01 21-19-17.png">

<image src="/src/Screenshot from 2023-03-01 21-19-44.png">

<image src="/src/Screenshot from 2023-03-01 21-21-32.png">

ENCFF543NGQ

<image src="/src/Screenshot from 2023-03-01 21-23-56.png">

<image src="/src/Screenshot from 2023-03-01 21-24-09.png">

<image src="/src/Screenshot from 2023-03-01 21-24-24.png">

ENCFF197MRK

<image src="/src/Screenshot from 2023-03-01 21-23-11.png">

<image src="/src/Screenshot from 2023-03-01 21-23-28.png">

<image src="/src/Screenshot from 2023-03-01 21-23-43.png">

В целом, выглядит не идеально, но качетсво у ридов не плохое, поэтому подрезать не стала.

Стастика:

| Образец | Число ридов | Число ридов уникальное | Число ридов не уникальное | Число ридов не выровнялось |
| ------- | ----- | ----- | ------ | ----- |
| ENCFF698KIR | 31451138 | 1205416 (3.83%) | 3254701 (10.35%) | 26991021 (85.82%) |
| ENCFF543NGQ | 34660616 | 1383319 (3.99%) | 3925882 (11.33%) | 29351415 (84.68%) |
| ENCFF197MRK | 39403529 | 1663531 (4.22%) | 5263860 (13.36%) | 32476138 (82.42%) |

Диаграммы Венна:

ENCFF698KIR

<image src="/src/vienn_KIR_1.png">

<image src="/src/vienn_KIR_2.png">

ENCFF543NGQ

<image src="/src/vienn_NGQ_1.png">

<image src="/src/vienn_NGQ_2.png">

Пересечений мало, это связано с тем, что выравнивание производилось только на одну хромосому (14). 
