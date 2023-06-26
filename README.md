# Примеры для курса OTUS "Разработчик Java"
| Опции                                                         |Результат|После оптимизации|
|---------------------------------------------------------------|---------|-----------------|
|-Xms256m -Xmx256m -XX:+HeapDumpOnOutOfMemoryError -XX:+UseG1GC |java.lang.OutOfMemoryError: Java heap space|java.lang.OutOfMemoryError: Java heap space|
|-Xms512m -Xmx512m                                             |spend msec:14497, sec:14|spend msec:5158, sec:5|
|-Xms1024m -Xmx1024m                                           |spend msec:13709, sec:13|spend msec:3298, sec:3|
|-Xms2048m -Xmx2048m|spend msec:12267, sec:12|spend msec:3634, sec:3|
|-Xms4096m -Xmx4096m|spend msec:12158, sec:12|spend msec:3683, sec:3|
|-Xms8192m -Xmx8192m|spend msec:22980, sec:22|spend msec:3468, sec:3|