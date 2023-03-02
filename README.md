# cb_communication_clarity

#Этот код принимает на вход текст в формате txt и выдает следующие метрики: оценка удобочитаемости нейросетевой моделью, 
оценка удобочитаемости по классическому автоматизированному индексу (на основе средней длины слов и предложений), 
44 лингвистические характеристики текста, значимые для принятия решения об удобочитаемости. 


Содержание пакета:

файл Clarity_bot.ipynb - основной код 

NN_model_May21.h5 - обученная нейросетевая модель классифкации текстов по уровню доступности 

freqrnc2011.csv - словарь частотности слов русского языка 

Tikhonov.csv - морфологический словарь русского языка

Testing_text.txt - тестовый файл для оценки

std_scaler.bin - внутренний словарь

readability_simple_bot.ipynb - автономный простой робот для оценки удобочитаемости только на основе средней длины слов и предложений

Архив с ru_core_news_lg - https://disk.yandex.ru/d/0w-gKVZkYOfA0Q 

ЦИТИРОВАНИЕ:
Evstigneeva, A. and Sidorovskiy, M. (2021). Assessment of Clarity of Bank of Russia Monetary Policy Communication by Neural Network Approach. 
Russian Journal of Money and Finance, 80(3), pp. 3–33. doi: 10.31477/rjmf.202103.03
