# Тестирование производительности приложений Rails

Это руководство раскрывает различные способы тестирования производительности приложения на Ruby on Rails.

После прочтения этого руководства, вы узнаете:

* О различных типах метрик бенчмаркинга и профилирования.
* Как создавать тесты производительности и бенчмаркинга.
* Как использовать двоичный файл Ruby, пропатченого GC, для измерения использования памяти и размещения объектов.
* О бенчмаркинговой информации, предоставленной Rails в файлах лога.
* О различных инструментах, помогающих бенчмаркигу и профилированию.

Тестирование производительности это неотъемлемая часть цикла разработки. Очень важно, чтобы конечные пользователи не ждали долго полной загрузки страницы. Обеспечение приятного серфинга для конечных пользователей и снижение расходов на ненужное оборудование важны для любого нетривиального веб приложения.