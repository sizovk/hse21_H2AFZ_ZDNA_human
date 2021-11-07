# hse21_H2AFZ_ZDNA_human

Целью работы над проектом является поиск и изучение участков генома, где гистоновая метка H2AFZ присутствует в местах образования ZDNA.

Для проекта был выбран геном человека сборки hg19, и тип клетки Parathyroid Adenoma. Взяты два ChIP-seq эксперимента с идентификаторами:

- [ENCFF042UAX](https://www.encodeproject.org/files/ENCFF042UAX/)
- [ENCFF452OXY](https://www.encodeproject.org/files/ENCFF452OXY/)

## Длины участков

### Гистограммы длин до фильтрации
<img src="https://github.com/sizovk/hse21_H2AFZ_ZDNA_human/blob/main/images/len_hist.png?raw=true"/>

### Ящик с усами длин до фильрации (для анализа порога)
<img src="https://github.com/sizovk/hse21_H2AFZ_ZDNA_human/blob/main/images/len_boxplot.png?raw=true"/>

### Гистограммы длин после фильтрации (длины не более 2000)
<img src="https://github.com/sizovk/hse21_H2AFZ_ZDNA_human/blob/main/images/filtered_len_hist.png?raw=true"/>

### Гистограммы длин участков Z-DNA DeepZ и их пересечения с H2AFZ
<img src="https://github.com/sizovk/hse21_H2AFZ_ZDNA_human/blob/main/images/zdna_len_hist.png?raw=true"/>

## Расположение пиков гистоновой метки относительно аннотированных генов

### ENCFF042UAX
<img src="https://github.com/sizovk/hse21_H2AFZ_ZDNA_human/blob/main/images/chip_seeker_H2AFZ_parathyroid_adenoma_ENCFF042UAX_hg19_filtered.png?raw=true"/>

### ENCFF042UAX
<img src="https://github.com/sizovk/hse21_H2AFZ_ZDNA_human/blob/main/images/chip_seeker_H2AFZ_parathyroid_adenoma_ENCFF452OXY_hg19_filtered.png?raw=true"/>

### DeepZ
<img src="https://github.com/sizovk/hse21_H2AFZ_ZDNA_human/blob/main/images/chip_seeker.DeepZ.plotAnnoPie.png?raw=true"/>

### Пересечения H2AFZ и DeepZ
<img src="https://github.com/sizovk/hse21_H2AFZ_ZDNA_human/blob/main/images/chip_seeker_H2AFZ_parathyroid_adenoma_intersect_with_DeepZ_plotAnnoPie.png?raw=true">


## Геномный браузер
Сохраненная сессия в UCSC Genome Browser: https://genome.ucsc.edu/s/sizovki/hse21_H2AFZ_ZDNA_human

### Участки с пересечениями
`chr1:762673-762896`
<img src="https://github.com/sizovk/hse21_H2AFZ_ZDNA_human/blob/main/images/section_1.png?raw=true"/>

`chr1:3712992-3713247`
<img src="https://github.com/sizovk/hse21_H2AFZ_ZDNA_human/blob/main/images/section_2.png?raw=true"/>


## GO-анализ
Был проведен GO-анализ для уникальных генов с использованием сайта http://pantherdb.org/

