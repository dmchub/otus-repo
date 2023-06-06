## Домашнее задание по теме Garbage Collectors

### Таблица результатов (начальное приложение)

| Garbage collector |  Heap  | Runtime, ms | App version | App result  |
|:------------------|:------:|------------:|:------------|:------------|
| G1                | 256 Mb |             | Basic       | OutOfMemory |
| G1                | 272 Mb |       11384 | Basic       | Success     |
| G1                | 320 Mb |       10585 | Basic       | Success     |
| G1                | 384 Mb |        9608 | Basic       | Success     |
| G1                | 512 Mb |        8815 | Basic       | Success     |
| G1                |  2 Gb  |        8276 | Basic       | Success     |
| SerialGC          | 256 Mb |             | Basic       | OutOfMemory |
| SerialGC          | 272 Mb |       41702 | Basic       | Success     |
| SerialGC          | 320 Mb |       18060 | Basic       | Success     |
| SerialGC          | 512 Mb |       12295 | Basic       | Success     |
| SerialGC          |  2 Gb  |        7384 | Basic       | Success     |
