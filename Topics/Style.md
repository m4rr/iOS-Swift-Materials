Style guide
-----

1. [Именование коммитов](http://chris.beams.io/posts/git-commit/#seven-rules)
1. Форматирование кода, желательно с помощью [BBUncrustify](http://chris.beams.io/posts/git-commit/#seven-rules)

Архитектура:

1. Не использовать синглетоны (но можно `static` переменные если они неизменяемые и в `@implementation`)
1. Подключать библиотеки с CocoaPods

