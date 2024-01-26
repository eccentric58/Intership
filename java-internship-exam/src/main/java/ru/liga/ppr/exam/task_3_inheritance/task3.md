## Задание 3 - Позвоночные

### Баллов за выполнение - 2

Требуется сделать так, чтобы тесты [Tests](../../../../../../../test/java/ru/liga/ppr/exam/task_3_inheritance/Task3Test.java) проходили успешно. Для этого необходимо дописать/исправить некоторые части кода для того,
чтобы приложение соответствовало условиям, описанным ниже. Изменять можно все классы внутри пакета [ru.liga.ppr.exam.task_3_inheritance](../task_3_inheritance) за исключением пакета [enums](enums)
Условия задачи:
1. Предположим, что наше приложение знает только о позвоночных ([Vertebrates](abstractions/Vertebrates.java)) животных. При этом каждое позвоночное животное имеет какое-то количество позвонков (разное для каждого вида животного, но одинаковое для животных одного вида).
2. Предположим, что наше приложение знает только 4 вида животных:
    +    Млекопитающие ([Mammal](abstractions/Mammal.java)), имеющие 33 позвонка
    +    Рептилии ([Reptile](abstractions/Reptile.java)), имеющие 40 позвонков
        -    Рептилия может обладать признаком того, что она умеет отбрасывать хвост
    +    Птицы ([Bird](abstractions/Bird.java)), имеющие 50 позвонков
        -    Умеют летать
    +    Рыбы ([Fish](abstractions/Fish.java)), имеющие 20 позвонков
        -    Умеют плавать
3. Из млекопитающих животных нам известен только человек ([Human](animals/Human.java))
4. Из рептилий известна только игуана ([Iguana](animals/Iguana.java)), которая не умеет отбрасывать хвост
5. Из птиц мы знаем альбатроса ([Albatross](animals/Albatross.java))
6. Из рыб мы знаем мурену ([Moray](animals/Moray.java)) и акулу ([Shark](animals/Shark.java))
7. Все птицы, о которых знает наше приложение летают с помощью взмаха крыльев
8. Акула плавает с помощью плавников, а мурена плавает с помощью изгибания тела