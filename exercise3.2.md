# XPathы элементов страниц "Выбор полиса" и "Оформление"

## Кнопки
1) Квартира   
 //*[text()='Что будет застраховано?']/following::button[1]
 
2) Дом    
 //*[text()='Что будет застраховано?']/following::button[2]

3) Сдается в аренду "ДА"  
//*[text()='Сдается в аренду']/following::button[1]
4) Сдается в аренду "Нет"  
//*[text()='Сдается в аренду']/following::button[2]
5) Расположена на первом или последнем этаже "Да"  
//*[text()='Расположена на первом или последнем этаже']/following::button[1]
6) Расположена на первом или последнем этаже "Нет"  
//*[text()='Расположена на первом или последнем этаже']/following::button[2]
7) Установлена охранная сигнализация "ДА"  
//*[text()='Установлена охранная сигнализация']/following::button[1]
8) Установлена охранная сигнализация "Нет"  
//*[text()='Установлена охранная сигнализация']/following::button[2]
9) Применить  
//*[text()='Промокод']/following::button[1]
10) Оформить  
//*[text()='Стоимость и срок действия']/following::button[1]
11) Заполнить по Сбер-ID  
//*[text()='Страхователь']/following::button[1]
12) Мужской  
//*[text()='Страхователь']/following::button[3]

13) Женский  
//*[text()='Страхователь']/following::button[4]

14) Вернуться   
//*[text()='Контактные данные Страхователя']/following::button[1]
15) Оформить  
//*[text()='Контактные данные Страхователя']/following::button[2]

## Поля для ввода
1) Регион проживания   
 //input[@data-placeholder="Регион"]
2) Промокод  
 //input[@formcontrolname="promoCode"]
3) Фамилия   
//span[@class="mat-form-field-label-wrapper ng-tns-c61-3"]
4) Имя  
//span[@class="mat-form-field-label-wrapper ng-tns-c61-4"]
5) Отчество  
//span[@class="mat-form-field-label-wrapper ng-tns-c61-5"]
6) Дата рождения  
//span[@class="mat-form-field-label-wrapper ng-tns-c61-6"]
7) Серия   
//span[@class="mat-form-field-label-wrapper ng-tns-c61-7"]
8) Номер  
//span[@class="mat-form-field-label-wrapper ng-tns-c61-8"]
9) Дата выдачи  
//span[@class="mat-form-field-label-wrapper ng-tns-c61-9"]
10) Кем выдан  
//span[@class="mat-form-field-label-wrapper ng-tns-c61-10"]
11) Код подразделения  
//span[@class="mat-form-field-label-wrapper ng-tns-c61-11"]
12) Город или населенный пункт  
//span[@class="mat-form-field-label-wrapper ng-tns-c61-13"]
13) Улица  
//span[@class="mat-form-field-label-wrapper ng-tns-c61-14"]
14) Дом, литера, корпус, строение  
//span[@class="mat-form-field-label-wrapper ng-tns-c61-15"]
15) Квартира  
//span[@class="mat-form-field-label-wrapper ng-tns-c61-16"]
16) Телефон  
//span[@class="mat-form-field-label-wrapper ng-tns-c61-17"]
17) Электронная почта  
//span[@class="mat-form-field-label-wrapper ng-tns-c61-18"]
18) Повтор электронной почты  
//span[@class="mat-form-field-label-wrapper ng-tns-c61-19"]
19) Дата начала срока действия страхования  
//input[@formcontrolname="startDate"]


## Чек-боксы
1) Отчество отсутствует     
//*[@for="mat-checkbox-1-input"]
2) Улица отсутствует   
//*[@for="mat-checkbox-2-input"]

## Датапикеры
1) Дата начала срока действия страхования  
//*[@class="mat-datepicker-toggle ng-tns-c61-21"]/button
2) Дата рождения  
//*[@class="mat-datepicker-toggle ng-tns-c61-6"]/button
3) Дата выдачи  
//*[@class="mat-datepicker-toggle ng-tns-c61-9"]/button

## Логотип Сбер Страхование

//div[@class="sber-logo"]

## Слайдер в блоке выбора суммы
//div[@class="mat-slider-wrapper"]

## Хедер "Что будет застраховано"
//*[text()='Что будет застраховано?']

## Текстовые блоки
1) "Мебель, техника и ваши вещи"  

//div[contains(text(), 'Мебель, техника и ваши вещи')]  

2) "Падение летательных аппаратов и их частей"
//*[text()='Падение летательных аппаратов и их частей']

## Колонки под хедером "Страховая защита, включенная в программу"
1) Первая колонка:  
//*[text()='Страховая защита включенная в программу']/following::ul[1]
2) Вторая колонка:  
//*[text()='Страховая защита включенная в программу']/following::ul[2]
