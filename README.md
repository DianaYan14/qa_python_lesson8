
# Тестируем классы интернет-магазина
Вам нужно реализовать и протестировать классы интернет-магазина.
Все места, которые нужно дописать как в тестах, так и классах, отмечены `# TODO`.

При реализации обращайте внимание на типизацию аргументов методов и возвращаемых значений.
Так же обратите внимание на организацию тестов в файле с тестами:
- Тесты сгруппированы по классу, который они тестируют.
- Каждый тест называется именем соответствующего ему метода.

Вы можете начать как с реализации классов, так и с тестов.


# Дополнительные вопросы:
1. С чего проще начать выполнение домашнего задания: с тестов или с реализации классов?
 >с классов
2. Почему для хранения товаров в корзине используется словарь, а не список?
 >для цен лучше использовать словари, можно указать для чего конкретно цена. Удобней обращаться по ключам.
3. Зачем нужен __hash__ в классе Product? Изучите этот метод и объясните, почему он нужен.
 >Чтобы значения были ключами словаря (???)