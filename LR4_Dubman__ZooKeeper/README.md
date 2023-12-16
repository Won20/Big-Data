# LR4_Dubman__ZooKeeper

# Что использовалось
- Scala 2.12.14
- JDK 1.8.0_362
- Apache ZooKeeper 3.8.3
- WSL Ubuntu 18.04

# Задание
- запустить ZooKeeper,
- изучить директорию с установкой ZooKeeper,
- запустить интерактивную сессию ZooKeeper CLI и освоить её команды,
- научиться проводить мониторинг ZooKeeper,
- разработать приложение с барьерной синхронизацией, основанной на ZooKeeper,
- запустить и проверить работу приложения.


# Реализация
## Установка ZooKeeper
![image](https://github.com/Won20/Big-Data/assets/102918065/86b50b1a-369f-4d92-aeca-91abf4791023)
![image](https://github.com/Won20/Big-Data/assets/102918065/b37ad688-5c90-4e08-a8ab-90992e8ba16e)

## Создание конфигурационного файла
![image](https://github.com/Won20/Big-Data/assets/102918065/d84841d4-df6d-4dbd-bd3b-ff373add007e)

## Запуск ZooKeeper-сервер
 ![image](https://github.com/Won20/Big-Data/assets/102918065/962cb2c0-81d1-4afe-bb32-3f60df549e30)

## Был реализован класс Animal
![image](https://github.com/Won20/Big-Data/assets/102918065/29745f9d-fcad-415e-9c7b-6879512f818c)
![image](https://github.com/Won20/Big-Data/assets/102918065/923cdf23-c669-4337-bfc4-d1bbaa6f97f8)

## Был реализован класс Main
![image](https://github.com/Won20/Big-Data/assets/102918065/9f988bff-392a-4953-b0b9-5c4d20ece94e)

## Были добавлены следующие конфигурации запуска Monkey
![image](https://github.com/Won20/Big-Data/assets/102918065/b25dad97-5eb9-434e-b89c-dc9479c40cec)

## Были добавлены следующие конфигурации запуска Fox
![image](https://github.com/Won20/Big-Data/assets/102918065/516858a9-845d-40ea-a9cc-58437419e59a)

# Запуск программы с конфигурацией Monkey
![image](https://github.com/Won20/Big-Data/assets/102918065/e6500422-8b2a-4b94-a11d-9f972312075d)

## В результате этого запуска на сервере появился узел monkey
![image](https://github.com/Won20/Big-Data/assets/102918065/02a04cf8-e9b0-4395-839b-a143aa4ee144)

# Запуск программы с конфигурацией Fox
![image](https://github.com/Won20/Big-Data/assets/102918065/0e3b68af-b712-4603-85ad-ca51fffea688)
![image](https://github.com/Won20/Big-Data/assets/102918065/12bedf5b-8ced-43e2-be8d-499d02fd7c5d)
Количество узлов достигло 2, узел fox был удалён по завершении цикла.

### После остановки программы все узлы были автоматически удалены
![image](https://github.com/Won20/Big-Data/assets/102918065/508de27b-311b-4e20-a338-0d60820e694c)


