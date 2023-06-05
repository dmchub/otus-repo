## Домашнее задание по теме Garbage Collectors

### Таблица результатов (начальное приложение)

| Garbage collector |  Heap  | Runtime, ms | App version | App result  |
|:------------------|:------:|------------:|:------------|:------------|
| G1                | 256 Mb |             | Basic       | OutOfMemory |
| G1                | 272 Mb |       11384 | Basic       | Success     |
| G1                | 512 Mb |        8815 | Basic       | Success     |
| G1                |  2 Gb  |        8276 | Basic       | Success     |


### Таблица результатов (оптимизированное приложение)

| Garbage collector |  Heap  | Runtime, ms | App version | App result |
|:------------------|:------:|------------:|:------------|:-----------|
| G1                | 256 Mb |        2208 | Optimized   | Success    |
| G1                | 512 Mb |        1506 | Optimized   | Success    |
| G1                |  2 Gb  |        1519 | Optimized   | Success    |
