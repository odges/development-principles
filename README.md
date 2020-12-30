# Design principles 

Guide to design of structure.

## Basic Provisions

1. Split class logic into small methods that do not exceed the screen height of 80 lines
2. Split long expressions and literals into multiple lines up to 80-120 characters wide
3. Strive to use as few nested constructs as possible (for, if, etc.)
4. Avoid complex flow control constructs like goto and recursion
5. Add a guard to the loops for the maximum number of iterations
6. Avoid unnecessary else block that can be omitted
7. Strive to use self-contained / self-speaking names of classes, functions, variables, etc.
8. Comment your code where it makes sense; write your code so that it doesn't need commenting
9. Follow the principles of Abstraction and DRY (Don’t Repeat Yourself), avoid code duplication
10. Avoid to low coupling between dependent classes of different system modules, use IoC, DI, Service Locator, etc.
11. Write tightly coupled classes and modules (high cohesion)
12. Store magic numbers in enum, constants, config or dictionary, avoid hardcodes
13. Always use curly braces for single-expression structures
14. Avoid creating a divine object (God object), follow SRP (Single Responsibility Principle)
15. Remove code that no longer works according to YDNIA (You Don't Need It Anymore)
16. Separate methods for obtaining information and performing actions according to CQS (Command-Query Separation)
17. Follow Safe Programming Practices (Secure coding)
18. Don't force classes to implement what they don't need according to the ISP (Interface Segregation Principle)
19. Always choose simple solutions whenever possible (KISS)
20. Encapsulate what changes
21. Code should depend on abstractions, not specific implementations
22. Keep a balance between efficiency and code clarity, avoid the pursuit of false efficiency
23. Don't add functionality unless you are sure you need it, according to YAGNI (You aren't gonna need it)
24. If it is possible to specify something — specify it explicitly
25. Delegate, don't do all the work yourself, assign it to the appropriate class

## Additional links
* [Coding Guidelines](https://medium.com/@luisacarrion/general-coding-guidelines-clean-code-from-day-1-9ab0804e5d91)
* [Object Calisthenics](https://williamdurand.fr/2013/06/03/object-calisthenics/)
* [The Power of 10](http://web.eecs.umich.edu/~imarkov/10rules.pdf)
* [Google JS Code Style](https://google.github.io/styleguide/jsguide.html#formatting-column-limit)
* [PHP Code Style](https://www.php-fig.org/psr/psr-2/)
* [Android Code Style](https://source.android.com/setup/contribute/code-style#limit-line-length)
* [OWASP Secure Coding Practices](https://owasp.org/www-pdf-archive/OWASP_SCP_Quick_Reference_Guide_v2.pdf)
* [Code Smell ](https://wiki.c2.com/?CodeSmell)
* [Cohesion and Coupling](https://enterprisecraftsmanship.com/posts/cohesion-coupling-difference/)
* [Abstraction Principle](https://en.wikipedia.org/wiki/Abstraction_principle_(computer_programming))
* [CQS Principle](https://martinfowler.com/bliki/CommandQuerySeparation.html)
* [Принципы ООП](https://habr.com/ru/company/skillbox/blog/454314/)
* [Rules of Trumb](https://medium.com/@vedantsopinions/software-engineering-rules-of-thumb-63060ca51)
* [Rules of Trumb](https://wou.edu/las/cs/csclasses/cs161/Lectures/rulesofthumb.html)
* [Zen of Python](https://www.python.org/dev/peps/pep-0020/)

## Another languages
[Russian](https://github.com/w3bsme/design-principles/blob/main/README_RU.md)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://github.com/w3bsme/design-principles/blob/main/LICENSE)
