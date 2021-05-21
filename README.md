## База знаний учебного проекта "Интеллектуальный планировщик"

### **Требования к сборке**: 

ostis-web-platform версии 0.5.0: https://github.com/ostis-apps/dockerized-ostis/

### **Требования к фрагментам**:

Связывать фрагменты друг с другом и с фрагментами из [ims](http://ims.ostis.net/)

Узлы объявлять в файле [constants.scs](https://intelligent-scheduler.jetbrains.space/p/ische/repositories/knowledge-base/files/constants.scs), который лежит в корне

Не дублировать объявления в файле [constants.scs](https://intelligent-scheduler.jetbrains.space/p/ische/repositories/knowledge-base/files/constants.scs)

Ещё не формализованные константы класть в файл [constants.scs](https://intelligent-scheduler.jetbrains.space/p/ische/repositories/knowledge-base/files/constants.scs) после комментария //wanted

Фрагменты хранятся в соответствующих разделах

Формализуемые используемые константы, которые не относятся к существующим разделам, класть в папку other

Если понятие существуюет в [ims](http://ims.ostis.net/), то при его использовании нужно добавлять комментарий //ims 

Блоки текста выносить в html-файл и добавлять гиперссылки, пример: [concept-property.scs](https://intelligent-scheduler.jetbrains.space/p/ische/repositories/knowledge-base/files/other/property/concept-property.scs)

Следовать кодстайлу и порядку блоков, с которым можно ознакомиться в шаблонах

Указывать в названии понятия его тип в качестве префикса

Для каждого фрагмента интеллектуального планировщика нужно формализовать пример в KBE и добавить его во фрагмент в виде картинки

В идентификаторе отношения должна быть конструкция <<'*'>>, потому что иначе плагин в Visual Studio Code находит в звёздочке ошибку (перед защитой курсовой я ручками удалю все апострофы)

### **Требования к названиям файлов и их структуре**:

Использовать дефис, а не нижнее подчёркивание вместо пробела

Название файла должно соответствовать названию понятия

Следовать существующей в репозитории структуре

### **Важное** уточнение:

Наборы символов = >, - >, - | >, < -, = >, < = при отображении в Space объединяются в [лигатуры](https://www.jetbrains.com/ru-ru/lp/mono/#ligatures)
