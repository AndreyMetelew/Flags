# Flags
Вторая моя практическая работа. 
Задачка немного глуповатая - работая со слоями, нужно реализовать... флаги России и Италии. 

Сначала я прописал их в самой программе, но позже реализовал их с помощью отдельных файлов ресурсов - russia.xml и italy.xml, а потом отработал их вставку. 
Здесь же, в файле activity_main.xml я создал как обычную, так и "альбомную" версию расположения флагов.  
В файле colors.xml я прописал дополнительные id цветов для флагов. Понадобилось всего 4 цвета, ибо они совпадали для двух флагов.
В файле activity_main.xml флаги прописаны как те самые ресурсы, составленые из таким образом: прописанные по ID цвета, использовались в файлах ресурсов, а их слои с прописанными id использовались как в книжной, так и в альбомной ориентации устройства.
