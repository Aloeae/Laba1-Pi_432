# ОТЧЁТ ПО ЛАБОРАТОРНОЙ РАБОТЕ №2
## Автоматизация сборки и деплоя Python Docker-приложений через Jenkins с интеграцией GitHub
---

## ФИО и группа

Студент: *Ефремова Алёна Андреевна*  
Группа: *ПИ-432Б*

---

# Ход выполнения работы

---

## 1. Создание и конфигурирование Jenkins Job

Авторизуемся на Jenkins-сервере, создаём новый проект. В открывшемся окне переходим к разделу Pipeline и редактируем код, добавляя своё  имя. Редактируем параметры.
<img width="1893" height="829" alt="Снимок экрана 2025-11-08 164906" src="https://github.com/user-attachments/assets/d97f593b-21a2-4ab9-a645-8f3de34f7140" />
<img width="1896" height="823" alt="Снимок экрана 2025-11-08 164847" src="https://github.com/user-attachments/assets/ccadfeb3-1326-4ce6-a09c-7918b6fca52e" />

---

## 2. Настройка GitHub webhook для автоматического запуска сборки

Открываем GitHub, во вкладке Settings выбераем пункт Webhooks и вносим необходимые изменения.
<img width="1276" height="850" alt="2025-11-08_17-54-13" src="https://github.com/user-attachments/assets/7292d6fc-9a37-4948-b3a3-6f1561ab61ab" />

---

## 3. Работа с Jenkins и проверка

Инициируем сборку и меняем в коде цвет.
<img width="1885" height="800" alt="Снимок экрана 2025-11-08 173641" src="https://github.com/user-attachments/assets/90c648b5-9bf6-4203-a120-b5a3e4b44881" />
<img width="1919" height="834" alt="Снимок экрана 2025-11-08 174024" src="https://github.com/user-attachments/assets/2ed08f27-a8d4-45f0-a447-5694bcfb53b8" />

---

# Заключение

В результате лабораторной работы мы научились работать в Jenkins.
