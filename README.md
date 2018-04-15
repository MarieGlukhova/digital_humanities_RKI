# digital_humanities_RKI Проект "Это не его конёк"

1)	**Что нам нужно было сделать?**
Перед нами стояла задача определить создателя текста «Конёк-горбунок», авторство которого официально принадлежит Петру Павловичу Ершову. Несмотря на это, не утихает спор о том, действительно ли это так. Одной из самых популярных является версия с авторством Александра Сергеевича Пушкина.
2)	**Как это нужно было сделать?** 
Нам было предложено использовать программу R и ее расширение Stylo, которое используется для сравнения текстов и определения авторства. 
Мы создали корпус со стихотворными (в большей степени) и несколькими прозаическими произведениями авторов-современников (Ершов, Пушкин, Жуковский, Языков, Катенин, Крылов) по типу «author_nameofnovel.txt». Так как программа лучше работает для больших объемов текста, мы объединили некоторые произведения, принадлежащие одному автору. В этом случае в названии текстового файла были указаны все произведения, которые он содержит. 
3)	STYLO: Default Settings 
При дефолтных настройках Stylo:
•	Language – other
•	UTF-8
•	MWF: min-100, max-100
•	CULLING: min-0, max-0
•	Cluster Analysis 

При кластерном анализе мы получили такой граф (дерево): ![GitHub Logo](https://psv4.userapi.com/c834702/u5573227/docs/d1/482fd60cb4f4/kartinka_1.png?extra=HFJyiAQVCxeqm_yEvLYATe08BItpPK-nlnLpWCIC5-mD4ivnztU9J6951VVAguw3p4-AI2LuSEfZIEHeiWZ427AblBxkX6inYYIB1Dz4vjEsnLUhVJmKYQgo6-8sng-e3pmL9_sf)


![GitHub Logo]()
![GitHub Logo]()
![GitHub Logo]()
![GitHub Logo]()
![GitHub Logo]()
![GitHub Logo]()


*Список источников*
1. [П. Ершов Конек Горбунок](https://solnet.ee/skazki/777)
2. [П. Ершов Cибирский казак](http://libverse.ru/yershov/sibirskii-kazak.html)
3. [П. Ершов Сузге](http://libverse.ru/yershov/syzge.html)
4. [П. Ершов Осенние вечера](http://az.lib.ru/e/ershow_p_p/text_1856_osennie_vechera.shtml)
5. [П. Ершов Избранные стихотворения](http://az.lib.ru/e/ershow_p_p/text_0050.shtml)
6. [В. Жуковский Война мышей и лягушек](http://lib.ru/LITRA/ZHUKOWSKIJ/mouse.txt)
7. [В. Жуковский Сказка о царе Берендее, о сыне его Иване-царевиче, о хитростях Кощея Бессмертного и о премудрости Марьи-царевны, Кощеевой дочери](http://rvb.ru/19vek/zhukovsky/01text/vol3/02tales/300.htm)
8. [В. Жуковский Кот в сапогах](http://rvb.ru/19vek/zhukovsky/01text/vol3/02tales/303.htm)
9. [В. Жуковский Сказка о Иване-Царевиче и сером волке](http://az.lib.ru/e/ershow_p_p/text_0050.shtml)
10. [В. Жуковский Спящая царевна](http://rvb.ru/19vek/zhukovsky/01text/vol3/02tales/301.htm)
11. [Н. Языков Жар-птица](http://az.lib.ru/j/jazykow_n_m/text_0110.shtml)
12. [П. Катенин Княжна Милуша](http://public-library.ru/Katenin.Pavel/knyazhna_milusha.html)
13. [А. Пушкин Золотой петушок](http://rvb.ru/pushkin/01text/03fables/01fables/0801.htm)
14. [А. Пушкин Сказка о медведихе](http://rvb.ru/pushkin/01text/03fables/01fables/0797.htm)
15. [А. Пушкин Cказка о попе и работнике его балде](http://rvb.ru/pushkin/01text/03fables/01fables/0796.htm) 
16. [А. Пушкин Сказка о царе Салтане, о сыне его славном и могучем богатыре князе Гвидоне Салтановиче и о прекрасной царевне Лебеди](http://rvb.ru/pushkin/01text/03fables/01fables/0798.htm)
17. [А. Пушкин Сказка о рыбаке и рыбке](http://rvb.ru/pushkin/01text/03fables/01fables/0799.htm) 
18. [А. Пушкин Сказка о мертвой царевне и о семи богатырях](http://rvb.ru/pushkin/01text/03fables/01fables/0800.htm)
19. [А. Пушкин Сказка о золотом петушке](http://rvb.ru/pushkin/01text/03fables/01fables/0801.htm)
20. [А. Пушкин Руслан и Людмила](http://rvb.ru/pushkin/01text/02poems/01poems/0784.htm)
21. [А. Пушкин Жених](http://vseskazki.su/avtorskie-skazki/skazki-pushkina-online/zhenih-ballada.html)
22. [И. Крылов ]()
23. [И. Крылов ]()
24. [И. Крылов ]()
25. [И. Крылов ]()
26. [И. Крылов ]()
27. [И. Крылов ]()
28. [И. Крылов ]()





**Рабочая группа проекта**: 
1. Людмила Лучкова – сбор текстов Крылова и Баратынского, загрузка материалов на github 
2. Ольга Осиновская – сбор текстов Пушкина, ссылки (github) 
3. Юлия Яковлева – сбор текстов Катенина, Языкова, Ершова 
4. Мария Глухова – сбор текстов Жуковского, статьи об авторстве 
5. Анастасия Часовских – сбор корпуса, анализ на R

![GitHub Logo](https://www.hse.ru/images/main_en/hse_ru_logo.svg)
