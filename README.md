# Разметка данных
## Модальности
Текст + Аудио
## Источники
Dusha + YouTube
## Аннотационная схема
|Уровень разметки|Тип разметки|Модальность|Формат|Визуализация|Связывание
|-|--------|---|-|-|-|
|Морфологические признаки|Части речи|Текст|CoNNL-U|INCEpTION|word_id, phrase_id, emotion_id
|Леммы|Леммы|Текст|CoNNL-U|INCEpTION|word_id, phrase_id, emotion_id
|Громкость звука|Громкие/тихие участки|Аудио|TextGrid|Praat|phrase_id, emotion_id
|Тональность|Высокий/низкий тон|Аудио|TextGrid|Praat|phrase_id, emotion_id
|Слова|Интервалы слов|Аудио|TextGrid|Praat|word_id, phrase_id, emotion_id
