# FAQ

Сборник полезных ответов на вопросы созданный коллективным разумом

# Java Performance
## Чем профилировать?
JMC (Mission Control) + JFR (Flight Records). Работает только на Oracle JDK, возможность использования при указании ключей
```
-XX:+UnlockCommercialFeatures -XX:+FlightRecorder
```
Для анализа результатов и хотспотов удобно использовать https://github.com/chrishantha/jfr-flame-graph

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
