# Sprint_3

В этом файле описаны тесты и PO, которые удалось реализовать в проекте
Всего в проекте удалось реализовать 5 PO, 4 теста для 4 разных сценариев, 12 тест кейсов:
- Проверка выпадающих списков в разделе «Вопросы о важном» - main_page/test_1_main_page(8 тест кейсов)
- Оформление заказа с некорректными инпутами - reg_negatiive/test_2_reg_negative(1 тест кейс)
- Оформление заказа с корректными инпутами - reg_positive/test_2_reg_positive(1 тест кейс)
- Переход по ссылкам Яндекс и Самокат в хедэре - header_links/test_3_header_links(2 тест кейса)

Использовано 2 фикстуры: фикстура драйвера и фикстура перехода на главную страницу сайта

В PO registration_positive есть 2 метода, которые объединяют методы в шаги:
def set_inputs_correct(self) - метод объединяет корректное заполнение всех инпутов в форме 1 при регистрации
def set_inputs_correct_2(self) - метод объединяет корректное заполнение всех инпутов в форме 2 при регистрации

В PO registration_negative есть 3 метода, которые объединяют методы в шаги:
def set_inputs_incorrect(self) - метод объединяет некорректное заполнение всех инпутов в форме 1 при регистрации
def set_inputs_correct(self) - метод объединяет корректное заполнение всех инпутов в форме 1 при регистрации
def set_inputs_incorrect_2(self) - метод объединяет некорректное заполнение всех инпутов в форме 2 при регистрации

Есть PO для общих методов - base_page. Методы из этого PO используются в двух PO: reg_positive и reg_negative

Для каждого теста реализованы allure отчеты

Создан файл с внешними зависимостями requirements.txt.





