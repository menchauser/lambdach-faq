# FAQ

Сборник полезных ответов на вопросы созданный коллективным разумом

# Java
## Performance
### Чем профилировать?
JMC (Mission Control) + JFR (Flight Records). Работает только на Oracle JDK, возможность использования при указании ключей
```
-XX:+UnlockCommercialFeatures -XX:+FlightRecorder
```
Для анализа результатов и хотспотов удобно использовать https://github.com/chrishantha/jfr-flame-graph
