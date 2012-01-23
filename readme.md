# RFC для диапазона статусов HTTP 7XX - Ошибки Разработчика

     Это мой перевод документа от John Barton, см. оригинал тут - https://github.com/joho/7XX-rfc
     Изменения и корректировки принимаются в виде пулл реквестов. Всегда ваш, Бобук.

На Railscamp X стало понятно, что есть громадная дыра в текущей спецификации HTTP.

У разработчика есть множество путей облажаться в реализации, но нет HTTP кодов, позволяющих поделиться сутью ошибки с конечным пользователем.

Мы скромно предлагаем следующие коды статусов к включению в спецификацию HTTP в диапазоне 7XX.

  * 701 - Мнэээ
  * 702 - Emacs
  * 711 - Закрыто
  * 719 - Я не чайник
  * 72X - Крайние случаи
    - 720 - Невозможно
    - 721 - Известное Неизвестное
    - 722 - Неизвестное Неизвестное
    - 723 - Что-то хитрое
    - 724 - Эта строка не должна была выполниться
    - 725 - А на моей машине работает
    - 730 - Это не баг, а фича
  * 73X - Блядство
    - 731 - Блядский Rubygems
    - 732 - Блядский юникод
    - 733 - Блядский дедлок
    - 734 - Блядский дефферед
    - 735 - Блядский IE
    - 736 - Блядский рейскондишн
    - 737 - БлядТредыские
    - 738 - Блядский Bundler
    - 739 - Блядский Windows
  * 74X - Про мемы
    - 741 - Компилируется
    - 742 - Котенок умер
    - 743 - Я надеялся что умею писать регулярные выражения
    - 744 - Чо ты не писал интеграционные тесты?
    - 745 - Я не всегда тестирую код, но когда тестирую, то всегда в продакшне
    - 746 - Промахнулся мимо пика Балмера
    - 747 - Ебаные змеи на ебаном самолете
    - 781 - Проклято пони
  * 76X - Разработчик под препаратами
    - 761 - Похмелье
    - 762 - Обкурен
    - 763 - Перекофеинился
    - 764 - Недокофеинился
    - 765 - Конференция
    - 766 - Трезвый
  * 77X - Предсказуемые проблемы
    - 771 - Перезакеширован
    - 772 - Недозакеширован
    - 773 - Не закеширован
    - 774 - Почему это закшировано?
    - 776 - Ошибка в Исключении
    - 777 - Случайность
    - 778 - Из-за одной ошибки
    - 779 - Из-за очень многих ошибок
  * 78X - Чужие проблемы
    - 781 - Финансисты
    - 782 - Тестировщики
    - 783 - Так попросил заказчик, честное слово!
    - 784 - Менеджеры, скорее всего
