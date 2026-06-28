# Тестирование мобильного приложения Todo List

> Проект выполнен в рамках курса "Функциональное тестирование ПО"  
> **Цель проекта** – протестировать небольшое мобильное приложение, составить базовую тестовую документацию и оформить её, потренироваться работать с эмулятором в Android Studio  

---

## 📱 Описание приложения

<table>
  <tr>
    <td width="250">
      <img src="screenshots/app_1.jpg" alt="Главный экран приложения" width="300">
    </td>
    <td width="250">
      <img src="screenshots/app_2.jpg" alt="Редактирование задачи" width="300">
    </td>
    <td style="vertical-align: top;">
      <p><strong>Todo List</strong> — это простое приложение для ведения списка задач на Android</p> 
      <p>Позволяет добавлять, редактировать, удалять задачи и отмечать их как выполненные</p>
      <p><strong>Основные экраны / функциональность</strong></p>
      <p>Экран списка задач:
      <ul style="margin-top: 0; padding-left: 20px;">
        <li>Поле ввода</li>
        <li>Кнопка добавления задач</li>
        <li>Список задач с чекбоксами</li>
        <li>Кнопки удаления задач</li></ul></p>
    <p>Редактирование задач (долгое нажатие):
      <ul style="margin-top: 0; padding-left: 20px;">
        <li>Поп-ап с полем ввода</li>
        <li>Кнопка сохранения изменений</li>
        <li>Кнопка отмены изменений</li>
      </ul>
    </td>
  </tr>
</table>

---

## 🛠 Инструменты тестирования

|    |    |
|-----------|-------------|
| Тестирование | Ручное, исследовательское, функциональное |
| Среда разработки | Android Studio |
| Документация | TestIT, GitHub |
| Управление тестами | Чек-лист, тест-кейсы |
| Отслеживание багов | Баг-репорты |

---

## 🚀 Инструкция по запуску 

### 1. Установить Android Studio
Скачать и установить [Android Studio](https://developer.android.com/studio) с официального сайта

### 2. Склонировать репозиторий проекта
Открыть терминал, перейти в нужную директорию для сохранения проекта и выполнить:
```bash
git clone git@github.com:softpaw-mango-cat/todo-list-app.git
```

### 3. Запустить эмулятор в Android Studio

<details>
<summary>Открыть проект в Android Studio</summary>
<img src="screenshots/project_1.png" alt="Настройка проекта в Studio" width="600">
</details><br>
<details>
<summary>Найти Device Manager и создать устройство для эмуляции (например, Pixel 9 Pro)</summary>
<img src="screenshots/project_2.png" alt="Настройка проекта в Studio" width="600">
</details><br>
<details>
<summary>Выбрать конфигурацию устройства (или использовать рекомендуемую) и подождать загрузки необходимых компонентов</summary>
<img src="screenshots/project_3.png" alt="Настройка проекта в Studio" width="600">
</details><br>
<details>
<summary>Запускаем выбранное устройство в Device Manager, перетаскиваем app.apk из папки проекта на устройство</summary>
<img src="screenshots/project_4.png" alt="Настройка проекта в Studio" width="600">
</details><br>
<details>
<summary>Нажимаем на иконку приложения на эмулированном телефоне, чтобы запустить его. Приложение можно тестировать 🔥</summary>
<img src="screenshots/project_5.png" alt="Настройка проекта в Studio" width="600">
</details><br>

*Опционально - приложение можно также запустить на своём физическом устройстве (телефоне на Android) или добавить его в Android Studio, чтобы тестировать через интерфейс Studio.*


## ✅ Результаты тестирования 

Чтобы протестировать основную функциональность приложения, был написан чек-лист необходимых проверок, и затем разработаны тест-кейсы. По итогам тестирования были найдены несколько дефектов и оформлены в виде баг-репортов. Все артефакты тестирования содержатся в папке [test_artifacts](test-artifacts)

[Чеклист](test-artifacts/Чек-лист.md) 
  

[Тест-кейсы - ссылка на гугл-таблицу](https://docs.google.com/spreadsheets/d/1_VVhHwFq_Km8h8RHfvCSrSh-xr8J6LFAfSyv45_wKmU/edit?usp=sharing)

[Баг-репорты - ссылка на гугл-таблицу](https://docs.google.com/spreadsheets/d/1J04u481pCNr-XKiKd7lTxV1RqD-THbXV9NBfCxVvCPg/edit?usp=sharing) 

<details>
  <summary><i>Тест-кейсы были выполнены в системе управления тестированием TestIT - ниже пара скриншотов проекта</i></summary>
  <img src="screenshots/project_6.png" alt="Скриншот проекта в TestIT" width="600"> 
  <img src="screenshots/project_7.png" alt="Скриншот проекта в TestIT" width="600"> 
</details>  