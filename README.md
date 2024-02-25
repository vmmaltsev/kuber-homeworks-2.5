# Домашнее задание к занятию «Helm» - `Мальцев Виктор`

---

Задание 1. Подготовить Helm-чарт для приложения

    1. Необходимо упаковать приложение в чарт для деплоя в разные окружения.
    2. Каждый компонент приложения деплоится отдельным deployment’ом или statefulset’ом.
    3. В переменных чарта измените образ приложения для изменения версии.

Ответ:

![alt text](https://github.com/vmmaltsev/screenshot/blob/main/Screenshot_148.png)

![alt text](https://github.com/vmmaltsev/screenshot/blob/main/Screenshot_149.png)

Чарт доступен по ссылке https://github.com/vmmaltsev/kuber-homeworks-2.5/tree/main/myapp

---

Задание 2. Запустить две версии в разных неймспейсах

    1. Подготовив чарт, необходимо его проверить. Запуститe несколько копий приложения.
    2. Одну версию в namespace=app1, вторую версию в том же неймспейсе, третью версию в namespace=app2.
    3. Продемонстрируйте результат.

Ответ:

![alt text](https://github.com/vmmaltsev/screenshot/blob/main/Screenshot_150.png)

![alt text](https://github.com/vmmaltsev/screenshot/blob/main/Screenshot_151.png)

Чарт доступен по ссылке https://github.com/vmmaltsev/kuber-homeworks-2.5/tree/main/myapp