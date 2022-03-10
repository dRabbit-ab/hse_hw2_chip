# hse_hw2_chip

## Ссылка на колаб

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

Таблица 4

| ENCFF000AWX | ENCFF000AWY | ENCFF036EGF |
| ----------------- | ----------------- | ----------------- |
| ![AWX_per_s](https://user-images.githubusercontent.com/79662580/157738580-4b4fa5b8-40f4-40af-a983-0ce429dac3c5.png) | ![AWY_per_s](https://user-images.githubusercontent.com/79662580/157738598-c8110bed-a8b6-4586-a330-c65a57e311f7.png) | ![C_per_s](https://user-images.githubusercontent.com/79662580/157738605-66b6f335-3c75-42c0-80c5-2046c169a5ff.png) |

| ENCFF000AWX (trimmed) | ENCFF000AWY (trimmed) | ENCFF036EGF |
| ----------------- | ----------------- | ----------------- |
| ![AWX_tr_per_s](https://user-images.githubusercontent.com/79662580/157738614-773f60b1-311c-4cab-8ad8-d681449f913b.png) | ![AWY_tr_per_s](https://user-images.githubusercontent.com/79662580/157738627-11ad2f5c-8f4f-4fc9-a997-c24520c25204.png) | ![C_per_s](https://user-images.githubusercontent.com/79662580/157738640-5a351acf-b05b-4925-9464-bf5c954e0d78.png) |

Таблица 5

| ENCFF000AWX | ENCFF000AWY | ENCFF036EGF |
| ----------------- | ----------------- | ----------------- |
|  |  |  |

| ENCFF000AWX (trimmed) | ENCFF000AWY (trimmed) | ENCFF036EGF |
| ----------------- | ----------------- | ----------------- |
|  |  |  |

### Статистика по выравниванию

|             | ENCFF000AWX | ENCFF000AWY | ENCFF036EGF |
| ----------- | ----------------- | ----------------- | ----------------- |
| Total       | 3151586 (100%) | 10876404 (100%) | 19175466 (100%) |
| Not aligned | 2525297 (80.13%) | 9278856 (85.31%) | 15342916 (80.01%) |
| Aligned 1 time | 141020 (4.47%) | 447519 (4.11%) | 854654 (4.46%) |
| Aligned >1 time | 485269 (15.40%) | 1150029 (10.57%) | 2977896 (15.53%) |

### Диаграммы Венна

Таблица 7

## Часть 2

### Хитмапы

### Выводы
