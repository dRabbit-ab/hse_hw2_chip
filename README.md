# hse_hw2_chip

## Ссылка на колаб

https://colab.research.google.com/drive/1pfU_bJXyCzGpTYvNJmfDrZvGVCjQbBNK?usp=sharing

## Часть 1

### Анализ FastQC

При анализе FastQC мне понадобилось использовать тримеринг для обеих реплик, чтобы добиться удовлетворительного качества

| ENCFF000AWX | ENCFF000AWY | ENCFF036EGF |
| ----------------- | ----------------- | ----------------- |
|![AWX_total](https://user-images.githubusercontent.com/79662580/157737749-08598ecb-c74d-478b-8f6e-c9cce0e8f90c.png) | ![AWY_total](https://user-images.githubusercontent.com/79662580/157737347-199ce493-0430-428d-8e5f-39f3ba78d55a.png) | ![C_total](https://user-images.githubusercontent.com/79662580/157737356-4e893175-af5e-4b70-8165-63140ad25bfa.png) |

| ENCFF000AWX (trimmed) | ENCFF000AWY (trimmed) | ENCFF036EGF |
| ----------------- | ----------------- | ----------------- |
| ![AWX_tr_total](https://user-images.githubusercontent.com/79662580/157737593-2efdf0b0-dbc0-4e93-82d0-7c62dcf4f849.png)| ![AWY_tr_total](https://user-images.githubusercontent.com/79662580/157737613-68001295-f330-48ba-bf38-a42d1e3f982c.png)| ![C_total](https://user-images.githubusercontent.com/79662580/157737623-810630b9-eafb-436f-9e26-6f07e375c005.png)|

| ENCFF000AWX | ENCFF000AWY | ENCFF036EGF |
| ----------------- | ----------------- | ----------------- |
| ![AWX_per_base](https://user-images.githubusercontent.com/79662580/157738054-3304257a-dbf8-4242-b802-896070d3c49d.png)| ![AWY_per_base](https://user-images.githubusercontent.com/79662580/157738064-78e42ce3-3e9f-43c9-920d-7c6700ab098d.png)| ![C_per_base](https://user-images.githubusercontent.com/79662580/157738081-3b7fa3ee-7859-405a-b474-2f5141c1dde5.png)|

| ENCFF000AWX (trimmed) | ENCFF000AWY (trimmed) | ENCFF036EGF |
| ----------------- | ----------------- | ----------------- |
| ![AWX_tr_per_base](https://user-images.githubusercontent.com/79662580/157738107-e47564cd-6e2c-40bb-b936-73f177859dd5.png)| ![AWY_tr_per_base](https://user-images.githubusercontent.com/79662580/157738113-f5998e1e-f533-4eec-8bfe-8f0a08915b04.png)| ![C_per_base](https://user-images.githubusercontent.com/79662580/157738125-9fccf24c-b36c-4dcb-84ec-4f493fcc5e57.png) |

| ENCFF000AWX | ENCFF000AWY | ENCFF036EGF |
| ----------------- | ----------------- | ----------------- |
| ![AWX_per_tile](https://user-images.githubusercontent.com/79662580/157738337-ebffd2a1-53b1-41b2-bdee-fa8c7cc291b3.png) | ![AWY_per_tile](https://user-images.githubusercontent.com/79662580/157738346-d47910ef-dc90-4ce6-aaf4-89e1f417b324.png) | ![C_per_tile](https://user-images.githubusercontent.com/79662580/157738351-457ce290-57f6-43da-941a-c4e0502a1447.png) |

| ENCFF000AWX (trimmed) | ENCFF000AWY (trimmed) | ENCFF036EGF |
| ----------------- | ----------------- | ----------------- |
| ![AWX_tr_per_tile](https://user-images.githubusercontent.com/79662580/157738364-d6b494b0-56e1-475b-b980-cb3c409ddd3c.png) | ![AWY_tr_per_tile](https://user-images.githubusercontent.com/79662580/157738378-b6cbcd39-5b3f-491f-b647-29e6f61add3a.png) | ![C_per_tile](https://user-images.githubusercontent.com/79662580/157738385-332c48cc-d4c1-4f5f-9223-3fbc1bbfa88b.png) |

| ENCFF000AWX | ENCFF000AWY | ENCFF036EGF |
| ----------------- | ----------------- | ----------------- |
| ![AWX_per_s](https://user-images.githubusercontent.com/79662580/157738580-4b4fa5b8-40f4-40af-a983-0ce429dac3c5.png) | ![AWY_per_s](https://user-images.githubusercontent.com/79662580/157738598-c8110bed-a8b6-4586-a330-c65a57e311f7.png) | ![C_per_s](https://user-images.githubusercontent.com/79662580/157738605-66b6f335-3c75-42c0-80c5-2046c169a5ff.png) |

| ENCFF000AWX (trimmed) | ENCFF000AWY (trimmed) | ENCFF036EGF |
| ----------------- | ----------------- | ----------------- |
| ![AWX_tr_per_s](https://user-images.githubusercontent.com/79662580/157738614-773f60b1-311c-4cab-8ad8-d681449f913b.png) | ![AWY_tr_per_s](https://user-images.githubusercontent.com/79662580/157738627-11ad2f5c-8f4f-4fc9-a997-c24520c25204.png) | ![C_per_s](https://user-images.githubusercontent.com/79662580/157738640-5a351acf-b05b-4925-9464-bf5c954e0d78.png) |

| ENCFF000AWX | ENCFF000AWY | ENCFF036EGF |
| ----------------- | ----------------- | ----------------- |
| ![AWX_per_bs](https://user-images.githubusercontent.com/79662580/157738910-63e1cb71-6965-4082-a7d1-a18054eab32e.png) | ![AWY_per_bs](https://user-images.githubusercontent.com/79662580/157738924-48a0a38a-2168-4af4-b974-829fa3443b91.png) | ![C_per_bs](https://user-images.githubusercontent.com/79662580/157738939-f1bc3587-c9e6-4fb0-a5cc-2fdfc3b3b90b.png) |

| ENCFF000AWX (trimmed) | ENCFF000AWY (trimmed) | ENCFF036EGF |
| ----------------- | ----------------- | ----------------- |
| ![AWX_tr_per_bs](https://user-images.githubusercontent.com/79662580/157738955-e772ba61-b85c-4eb9-bbf4-43f8f19f7437.png) | ![AWY_tr_per_bs](https://user-images.githubusercontent.com/79662580/157738969-6fb406e7-0082-4193-8046-72a1d936a9aa.png) | ![C_per_bs](https://user-images.githubusercontent.com/79662580/157738977-1c254ade-3dcf-4f7f-9dc0-47304348e11a.png) |

| ENCFF000AWX | ENCFF000AWY | ENCFF036EGF |
| ----------------- | ----------------- | ----------------- |
| ![AWX_gc](https://user-images.githubusercontent.com/79662580/157739399-1984a2be-9f3c-4012-b686-03cce1bca34b.png) | ![AWY_gc](https://user-images.githubusercontent.com/79662580/157739417-8da5e19e-145b-433d-a2a9-51e77e82fc5f.png) | ![C_gc](https://user-images.githubusercontent.com/79662580/157739431-d524482a-8da7-4144-b29b-2d82c7e36051.png) |


| ENCFF000AWX (trimmed) | ENCFF000AWY (trimmed) | ENCFF036EGF |
| ----------------- | ----------------- | ----------------- |
| ![AWX_tr_gc](https://user-images.githubusercontent.com/79662580/157739449-30b250d0-7f7e-44b6-a77d-12b08aca9b94.png) | ![AWY_tr_gc](https://user-images.githubusercontent.com/79662580/157739461-ec87925c-90ce-445e-aa56-cdfe9e1b1f59.png) | ![C_gc](https://user-images.githubusercontent.com/79662580/157739472-19ee350a-c8b0-40c0-bc86-9a17c30a2f9e.png) |

Вывод:
Как видно на графиках, триминг помог улучшить качетсво. В конечном итоге, полученное качество чтений можно назвать удовлетворительным: распределения близки к теоретическим, соотношения TACG тоже близки к нормальным и т.д.

### Статистика по выравниванию

|             | ENCFF000AWX | ENCFF000AWY | ENCFF036EGF |
| ----------- | ----------------- | ----------------- | ----------------- |
| Total       | 3151586 (100%) | 10876404 (100%) | 19175466 (100%) |
| Not aligned | 2525297 (80.13%) | 9278856 (85.31%) | 15342916 (80.01%) |
| Aligned 1 time | 141020 (4.47%) | 447519 (4.11%) | 854654 (4.46%) |
| Aligned >1 time | 485269 (15.40%) | 1150029 (10.57%) | 2977896 (15.53%) |

Вывод: 
Процент выравниваний получился таким небольши, так как данные были выравнены на одну 14-ую хромосому

### Диаграммы Венна

| ENCFF000AWX.1 | ENCFF000AWX.2 |
| ----------------- | ----------------- |
| ![AWX_venn_1](https://user-images.githubusercontent.com/79662580/157740172-23e49d35-882c-4f6d-9fa6-7d279df7c3e4.png) | ![AWX_venn_2](https://user-images.githubusercontent.com/79662580/157740181-d12cdaf7-c7b4-41bc-a8a8-7477b7e6dd3c.png) |

| ENCFF000AWY.1 | ENCFF000AWY.2 |
| ----------------- | ----------------- |
| ![AWY_venn1](https://user-images.githubusercontent.com/79662580/157740192-80fbfd9c-518f-49a2-b1a6-fb838100a205.png) | ![AWY_venn2](https://user-images.githubusercontent.com/79662580/157740207-4f654463-cc1e-4089-a3b8-7cf5fc522cd2.png) |

Вывод:
На диаграммах мы можем увидеть пересечения из размеченных нами пиков и отмеченных в ENCODE и наоборот. Я думаю, что пересечения не совпадают, так как мы по-разному их определяем, а именно в начале из одного файла на другой, а затем наоборот.

## Часть 2 : Бонсуное задание

### Хитмапы

| ENCFF270IOE.bam -> ENCFF613OKL.bigWig | ENCFF171RVK.bam -> ENCFF894VJK.bigWig |
| ----------------- | ----------------- |
| ![result1](https://user-images.githubusercontent.com/79662580/157740450-fb0d6d5a-7b84-47f4-804a-a86585617184.png) | ![result2](https://user-images.githubusercontent.com/79662580/157740460-ffa17715-2e52-4d71-9ef1-beb5088e6376.png) |

Выводы:
Для первого графика можно с натяжкой заключить о совпадении расположения гистоновой метки относительно референтного генома, для второго сделать этого не получится.
