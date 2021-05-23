## База знаний учебного проекта "Интеллектуальный планировщик"

### **Требования к сборке**: 

ostis-web-platform версии 0.5.0: https://github.com/ostis-apps/dockerized-ostis/

### **Требования к фрагментам**:

Связывать фрагменты друг с другом и с фрагментами из [ims](http://ims.ostis.net/)

Понятия объявлять в файле [constants.scs](https://intelligent-scheduler.jetbrains.space/p/ische/repositories/knowledge-base/files/constants.scs), который лежит в корне

Не дублировать объявления в файле [constants.scs](https://intelligent-scheduler.jetbrains.space/p/ische/repositories/knowledge-base/files/constants.scs)

Указывать основной идентификатор понятия в файле [constants.scs](https://intelligent-scheduler.jetbrains.space/p/ische/repositories/knowledge-base/files/constants.scs) в комментарии после объявления

Ещё не формализованные константы класть в файл [constants.scs](https://intelligent-scheduler.jetbrains.space/p/ische/repositories/knowledge-base/files/constants.scs) после комментария //wanted

Перед формализацией испольуемых констант, нужно добавить пункт с названием этой константы в [соответствующий список](https://intelligent-scheduler.jetbrains.space/p/ische/checklists/2Wicfp32nLyC) и создать на её основе задачу (**Issue**), а затем назначить её себе

Если понятие существует в [ims](http://ims.ostis.net/), то при его использовании нужно добавлять комментарий //ims 

Блоки текста выносить в html-файл и добавлять гиперссылки, пример: [nrel_subtask](https://intelligent-scheduler.jetbrains.space/p/ische/repositories/knowledge-base/files/intelligent_scheduler/sections/tasks/relations/nrel_subtask/nrel_subtask.scs)

Следовать кодстайлу и порядку блоков, с которым можно ознакомиться в [шаблонах](https://intelligent-scheduler.jetbrains.space/p/ische/repositories/knowledge-base/files/templates/concept_template.txt)

Указывать в названии понятия его тип в качестве префикса

Для каждого фрагмента интеллектуального планировщика нужно формализовать пример в KBE и добавить его во фрагмент в виде картинки

В основном идентификаторе отношения после звёздочки должен стоять пробел, потому что иначе плагин в Visual Studio Code находит в звёздочке ошибку

### **Требования к названиям файлов и их структуре**:

Использовать нижнее подчёркивание, а не дефис вместо пробела

Название файла должно соответствовать названию понятия

Создавать для каждого фрагмента папку

Папка фрагмента, принадлежащего разделам интеллектуального планировщика, должна иметь следующий путь: .../*раздел, включающий в себя рассматриваемый фрагмент*/*тип рассматриваемого фрагмента*/

Папка фрагмента, используемого в качестве константы, но не принадлежащего разделам интеллектуального планировщика, должна иметь следующий путь: /other/*тип рассматриваемого фрагмента*/

Папка фрагмента должна содержать папку html и, если фрагмент содержит в себе изображение, папку png

html и png класть в соответствующие папки

Следовать существующей в репозитории структуре

### **Важное** уточнение:

Наборы символов = >, - >, - | >, < -, = >, < = при отображении в Space объединяются в [лигатуры](https://www.jetbrains.com/ru-ru/lp/mono/#ligatures)
