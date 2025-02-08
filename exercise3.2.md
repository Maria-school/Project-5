## XPath'ы

# Кнопки:
1.Квартира
//span[contains(text(),'Квартира')]/ancestor::button

2.Дом
//*[contains(text(),'Дом')]/ancestor::button

3.Для квартиры:  

3.1. Сдается в аренду

-Да  //*[@id="mat-button-toggle-40-button"]

-Нет //*[@id="mat-button-toggle-41-button"] 

3.2.  Расположена на первом или последнем этаже   

-Да  //*[@id="mat-button-toggle-43-button"]

-Нет   //*[@id='mat-button-toggle-44-button']

3.3. Установлена охранная сигнализация

-Да  //*[@class='mat-button-toggle mat-stroked-button mat-button-toggle-checked mat-button-toggle-appearance-standard']''

-нет //*[contains(text(),'Установлена охранная сигнализация')]/following::button[2] 

4.Для дома:  

4.1. Сдается в аренду 

-Да  //*[text()='Сдается в аренду']/following::button[1]  

-Нет   //*[text()='Сдается в аренду']/following::button[2]  

4.2. Установлена охранная сигнализация   

-Да  //*[contains(text(), 'Установлена')]/following::button[1]  

-Нет  //*[contains(text(), 'Установлена')]/following::button[2]   

4.3.  Материал несущих стен  

-Кирпич или монолит  Кирпич и монолит://span[contains(text(), 'Кирпич')]/ancestor::button  

-Дерево //span[contains(text(), 'Дерево')]/ancestor::button

5.Применить //*[contains(text(), 'Промокод')]/following::button

6.Оформить //*[contains(text(), 'Стоимость')]/following::button

7.Заполнить по сбер ID -\//button[@color='primary']

8.Мужской-\//button[@id="mat-button-toggle-100-button"][@aria-pressed="true"]

9.Женский- \//button[@id="mat-button-toggle-101-button"][@aria-pressed="false"]

10.Вернуться-\//button[@class="mat-focus-indicator action-back mat-stroked-button mat-button-base"]

11.Оформить-\//button[@class='mat-focus-indicator mat-flat-button mat-button-base mat-accent']

***
# Поля для ввода текста:

1. Регион проживания-\//input[@formcontrolname='registrationRegion']
2. Сумма-\//input[@id='mat-input-24'][@aria-invalid='false']
3. Промокод-\//input[@formcontrolname='promoCode']
4. Фамилия //*[contains(text(),'Фамилия')]
5. Имя //*[contains(text(),'Имя')]
6. Отчетсво //*[contains(text(),'Отчество')]
7. Серия //*[contains(text(),'Серия')]
8. Номер //*[contains(text(),'Номер')]
9. кем выдан //textarea
10. Код подразделения //*[contains(text(), 'Код')]/ancestor::span/preceding-sibling:: input
11. Регион проживания //input[@placeholder='Регион']
12. Город //*[contains(text(), 'Город')]/ancestor::span//preceding-sibling::input
13. Улица //input[@placeholder='Улица']
14. Дом-\//input[@formcontrolname='registrationHouse']
15. Квартира-\//input[@formcontrolname='registrationFlat']
16. Телефон-\//input[@formcontrolname='contactPhone']
17. Электронная почта-\//input[@formcontrolname='contactEmail']
18. Повтор электронной почты-\//input[@formcontrolname='repeatEmail']
***
# Датапикеры:
1. Дата начала полиса //*[@class='ng-tns-c61-1']
2. Дата рождения //*[@class='ng-tns-c61-6'] 
3. Дата выдачи //*[@class='ng-tns-c61-9']
***
# Чек-боксы:
1. Отчество отсутствует//*[@id='mat-checkbox-1']
2. Улица отсутствует //*[contains(text(), 'Улица отсутствует')]/preceding-sibling::div//input
***
# Прочее:
1. Слайдер в блоке выбора суммы //div[@class="mat-slider-thumb"]
2. Логотип "СБЕР СТРАХОВАНИЕ" //div[@class="sber-logo"]
3. Хедер Что будет застраховано? //h4[@class="block-header"] 
4. Мебель, техника и ваши вещи-\//div[contains (text(),'Мебель, техника и ваши вещи')]
5. Падение летательных аппаратов и их частей-\//div[contains (text(),'Падение летательных аппаратов и их частей')]
6. ЛЕВАЯ колонка под хедером "Страховая защита включенная в программу-\//div[text()='Чрезвычайная ситуация']/ancestor::ul
7. ПРАВАЯ колонка под хедером "Страховая защита включенная в программу-\//div[text()='Стихийные бедствия']/ancestor::ul








