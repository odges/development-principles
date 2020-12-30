# Принципы разработки

Гайд по принципам разработки.

## Основные положения

1. Дробите логику класса на небольшие методы, не превышающие высоту экрана в 80 строк
2. Дробите длинные выражения и литералы на несколько строк, не превышающих ширину экрана в 80-120 символов
3. Стремитесь использовать как можно меньше вложенных друг в друга конструкций (for, if, и тд)
4. Избегайте сложные конструкции управления потоком, такие как goto и рекурсии
5. Добавляйте в циклы защитный ограничитель на максимальное количество итераций
6. Избегайте лишний else блок, который можно опустить
7. Стремитесь использовать самодостаточные/самоговорящие имена классов, функций, переменных и тд
8. Комментируйте код там, где это имеет смысл; пишите код так, чтобы он не нуждался в комментировании
9. Следуйте принципам Абстракции и DRY (Don’t Repeat Yourself), избегайте дублирования кода
10. Стремитесь к слабому сцеплению (low coupling) между зависимыми классами разных модулей системы, применяйте IoC, DI, Service Locator и тд
11. Пишите классы и модули с сильной связностью (high cohesion)
12. Храните магические числа в enum, константах, конфиге или словаре, избегайте хардкодов
13. Всегда используйте фигурные скобки для структур с одним выражением
14. Избегайте создания Божественного объекта (God object), следуйте SRP (Single Responsibility Principle)
15. Удаляйте код, который больше работать не будет, согласно YDNIA (You Don't Need It Anymore)
16. Разделяйте методы для получения информации и выполнения действий, согласно CQS (Command-Query Separation)
17. Следуйте методикам Безопасного программирования (Secure coding)
18. Не заставляйте классы реализовывать то, что им не надо, согласно ISP (Interface Segregation Principle)
19. По возможности всегда выбирайте простые решения (KISS)
20. Инкапсулируйте то, что изменяется
21. Код должен зависеть от абстракций, а не от конкретных реализаций
22. Держите баланс между эффективностью и ясностью кода, не допускайте погоню за ложной эффективностью
23. Не добавляйте функциональности, пока вы точно не уверены в её надобности, согласно YAGNI (You aren't gonna need it)

## Содействие
Pull request'ы приветствуются. В случае серьезных изменений сначала откройте вопрос, чтобы обсудить, что вы хотите изменить.

Не забудьте обновить тесты по мере необходимости.

## Лицензия
[MIT](https://github.com/w3bsme/design-principles/blob/main/LICENSE)