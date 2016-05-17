# FAQ

Сборник полезных ответов на вопросы созданный коллективным разумом

# Java Performance
## Чем профилировать?
JMC (Mission Control) + JFR (Flight Records). Работает только на Oracle JDK, возможность использования при указании ключей
```
-XX:+UnlockCommercialFeatures -XX:+FlightRecorder
```
Для анализа результатов и хотспотов удобно использовать https://github.com/chrishantha/jfr-flame-graph

# Самообучение
## Алгоритмы и структуры данных
[Algorithm Design Manual by Steven Skiena](https://www.amazon.com/Algorithm-Design-Manual-Steven-Skiena-ebook/dp/B00B8139Z8?ie=UTF8)

Курсы на курсере:
* [Алгоритмы, часть первая](https://www.coursera.org/course/algs4partI)
* [Алгоритмы, часть вторая](https://www.coursera.org/course/algs4partII)

# Самоорганизация и прочее
## Что почитать эффективного про это?
На Coursera есть хороший курс [Learning How To Learn](https://www.coursera.org/learn/learning-how-to-learn/home/info?source=cdpv2) о организации в самообучении.
Есть книжка одного из авторов курса Барбары Окли: [Думай как математик](https://www.ozon.ru/context/detail/id/33253422/)
## Как планировать свою работу?
Горячо рекомендуем Pomodoro technique. Удобные приложения:
* [Pomotodo](https://pomotodo.com/),
* [Pomodone](http://pomodoneapp.com/).

Для расписывания задач: [Trello](https://trello.com/). Pomodone может с ним интегрироваться и считать статистики по помидорам за конкретную задачу.
Есть еще [Kanbanflow](https://kanbanflow.com), который включает в себя и канбан-доску (как в Trello), и pomodoro-таймер.

На текущий момент рекомендуется либо связка Pomodone+Trello, либо Kanbanflow.

# Java Conferences
## Java Point 2016
* [Тагир Валеев, Странности Stream API](https://www.youtube.com/watch?v=hxL5HejbvgE&index=2&list=PLO9lWyBRzDwhu-JiHk8x_Qemxdv1RwnJp)
* [Андрей Паньгин, Глубже стек-трейсов, шире хип-дампов](https://www.youtube.com/watch?v=5Hyqwks1F7c&index=23&list=PLO9lWyBRzDwhu-JiHk8x_Qemxdv1RwnJp)
* [Олег Анастасьев, Распределенные системы в Одноклассниках](https://www.youtube.com/watch?v=WdR8LYTeD8o&index=26&list=PLO9lWyBRzDwhu-JiHk8x_Qemxdv1RwnJp)
* [Николай Алименков, Сага о том, как Java-разработчики должны тестировать (часть 1)](https://www.youtube.com/watch?v=2FFoSUGwZaw&list=PLO9lWyBRzDwhu-JiHk8x_Qemxdv1RwnJp&index=32)
* [Николай Алименков, Сага о том, как Java-разработчики должны тестировать (часть 2)](https://www.youtube.com/watch?v=RSwlnd4VjCU&list=PLO9lWyBRzDwhu-JiHk8x_Qemxdv1RwnJp&index=33)
* [Егор Бугаенко, ORM — это обидно](https://www.youtube.com/watch?v=zAl1toXfMA8&list=PLO9lWyBRzDwhu-JiHk8x_Qemxdv1RwnJp&index=11)
