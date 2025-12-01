# branching

## Ссылка на Network Graph репозитория:

https://github.com/Nano-prototip/branching/network

## Выполненные шаги:

1. Созданы начальные файлы merge.sh и rebase.sh
2. Создана и развита ветка git-merge с двумя коммитами
3. Внесены изменения в main параллельно с разработкой в ветках
4. Создана ветка git-rebase от начального коммита
5. Выполнен merge ветки git-merge в main
6. Выполнен rebase ветки git-rebase на main с разрешением конфликтов
7. Завершен merge ветки git-rebase в main

Все операции выполнены успешно, конфликты разрешены.

## Промежуточные итоги

Промежуточное состояние файлов в скриншотах:

Первый коммит
![image](./image/git.png)

Создал ветку git-merge
![image](./image/git1.png)

Коммит в ветке git-merge
![image](./image/git2.png)

Состояние файлов после модификации
![image](./image/git3.png)

Второй коммит в ветке git-merge
![image](./image/git4.png)

Перемещение в ветку main и коммит
![image](./image/git5.png)

Получение хэша коммита и переключение на него. Далее создал ветку git-rebase от этого коммита.
![image](./image/git8.png)
![image](./image/git9.png)
![image](./image/git10.png)

Первый и второй коммиты в ветке git-rebase
![image](./image/git11.png)
![image](./image/git12.png)

Слияние веток main и git-merge(без конфликтов)
![image](./image/git13.png)
![image](./image/git14.png)

Состояние network graph после слияния
![image](./image/git15.png)

rebase веток main и git-rebase
![image](./image/git16.png)

Первый конфликт(выбрал current change)
![image](./image/git17.png)

Продолжение и второй конфликт(выбрал incoming change)
![image](./image/git18.png)

Слияние веток git-merge и main
![image](./image/git19.png)

Ошибка после git push(из за того, что изменили историю)
![image](./image/git21.png)

Форсируем push
![image](./image/git22.png)
![image](./image/git23.png)

Состояние netwotk graph после завершения работы
![image](./image/git24.png)