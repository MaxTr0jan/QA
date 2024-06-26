Общие вопросы:

1. QA инженер - специалист, который обеспечивает качество продукта, проверяет его на работоспособность, наличие багов и ошибок. А так же, разрабатывает тестовые планы, пишет тест-кейсы и анализирует их результаты.

2. Тестирование - процесс, при котором продукт проверяется на соответствие требованиям, ожидаемый функционал, и работоспособность.

3. Проверку необходимо проводить для обеспечения качества конечного продукта, и удовлетворение потребностей пользователей ПО.



Логическая задача:

Первый пират должен предложить распределение, которое обеспечит ему поддержку как минимум двух пиратов. Среди всех пиратов, в первую очередь, нужно договориться с пиратом номер 5. Пират номер 5 находится в самом невыгодном положении, до него очередь точно не дойдёт, и, если они останутся вдвоём с пиратом номер 4, то пират номер 4 сможет забрать всё себе. Следующим, на мой взгляд, нужно заручиться поддержкой пирата номер 3, т.к. если пирата номер 1 убьют, то пират номер 2, к которому перейдёт право распределения, может договориться с пиратом номер 4 или 5, т.к. пират номер 3 почти в любом случае будет голосовать против пирата номер 2, чтобы право голоса перешло к нему. Относительно распределения средств: пирату номер 5 можно предложить одну монету, это лучше, чем ничего. Неизвестно будет ли согласен ни одну монету пират номер 3, но я бы рискнул распределить средства так. В итоге у пирата номер 1 останется 98 монет и будет 2 дополнительных голоса при голосовании.


Второй вариант: В условиях задачи не сказано, могут ли пираты просто так взять и ограбить первого, если их что-то не устроит. Если да - то в таком случае, первому стоит просто убить их всех и оставить себе 100 монет.



Задачи на тестирование:

Как протестировать сломанный тостер:

1. Визуальный тест: проверить тостер и кабель питание на наличие повреждений, трещин, следов огня
2. Тест электропитания: попробовать подключить тостер к источнику питания, проверить работоспособность кнопки вкл/выкл
3. Тест работоспособности: проверка кнопки регулировки мощности нагрева, включить тостер на короткий цикл, оценить нагрев и его равномерность, убедиться, что тостер не выделяет неприятные запахи
4. Тест на автоматическое отключение: проверить, срабатывает ли автоматическое отключение при достижении определенной температуры.
5. Тест на безопасность: убедиться, что тостер безопасно выключается и не представляет угрозу возгорания или поражения электрическим током.



Рекомендации по улучшению:

1. На макете дата указана без года.
2. После даты, без переход на следующую строку, сразу указан адрес. Адрес самовывоза лучше указать на следующей строке.
3. В адресе самовывоза не указан город.
4. Фразу: "Не забудьте паспорт" лучше перенести на следующую строку.
5. Кнопки для закрытия окна с информацией различаются. Текст на кнопке изменить с "Готово" на "Закрыть", как уже реализовано в рабочем приложении.
6. На макете, в тексте, поставлены точки после каждого сокращения ("ул.", "корп."). В уже рабочем приложении точка поставлена только после сокращения "кв.". Нужно либо это исправить в рабочем приложении, либо вообще не ставить точки после сокращений.



Тестирование калькулятора:

1. Тест №3: Калькулятор не распознал операцию "плюс" (т.к. слово-аналог не "плюс", а "плюсс")
2. Тест №4: Фактический результат не соответствует ожидаемому (ожидаемый результат математически не верен).
3. Тест №5: Фактический результат не соответствует ожидаемому (фактический результат не был округлён, в отличии от ожидаемого)
4. Тест №6: Фактический результат не соответствует ожидаемому (не выполнено сложение. И, судя по описанию функций калькулятора, оба числа должны быть введены в одном формате, то есть числовом, либо текстовом)
5. Тест №7: Фактический результат не соответствует ожидаемому (скорее всего, калькулятор не должен был вообще выполнить данную операцию)
