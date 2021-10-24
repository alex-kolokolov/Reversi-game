# Приложение "Викторины"
<b>Приложение позволит проходить и создавать викторины и тесты. Вопросы можно создавать с использованием медиафайлов. Сохраняться тесты будут в базу данных. Пользователи будут объеденены в базу данных, вход в учетную запись будет по логину и паролю. Результаты тестов можно будет посмотреть на главной странице.

ТЗ:
При первом входе в программу должно бужет открываться окно с двумя кнопками: входом или регистрацией. При регистрации будет требоваться логин и пароль, также по желанию можно заполнить личную информацию(ФИО, дату рождения и описание). Для каждого параметра будет собственне поле ввода. Также в форме будет присутстувать кнопка, при нажатии на которую будет проверяться корректность введеных данных:
1.	Заполнены ли обязательные поля
2.	Сложный ли пароль
3.	Существует ли такой логин в базе данных польщователей
Окно входа состоит из двух виджетов ввода и кнопки, которая проверяет корректность данных.
Если вход уже был совершен в предыдущих запусках программы, то тогда будет открываться гланое меню программы. В нем есть два виджета кнопки, при нажатии на которые можно либо создать тест, либо пройти его. Также юудет третья кнопка, отвечающая за профиль польщователя.
После нажатия на кнопку для прохождения, откроется меню, в котором есть викторины, присутствующие в баззе данных. Они будут показаны в виде таблицы, которая состоит из следующих столбцов: id, название, количество прошеших тест. Сортировать их можно будет по алфавиту, количеству прошедших и id, также снизу будет виджет ввода и кнопки которая отвечает за поиск по названию или id, который будет показывать несколько тестов, наиболее подходящих по поисковым критериям. После выбора теста мы перейдем в окно его прохожденич , где будет progress bar,окно с вопросом и выбором ответа. Сохранить ответ можно по кнопке, которая также переведет на следующий вопрос. Если вы завершили тест, то появится окно с результатом теста(Скошлько из всех ответов праавильных, процент верных ответов). Снузу будут две кнопки: пройти тест заново или просмотреть ошибки. При нажатии на вторую кнопку моожно будет помотреть, где были добущены, ошибки, а где верные ответы(верные ответы будут подсвечены зеленым, неверные — красным).
При нажатии на кнопку создания будет открываться окно в котором можно будет верхнее меню из пунктов создать или сохранить.Вопрос будет соответствовать определенному, слайду, как в презентации. Сам вопрос может быть написан в специальном  виджете, который будет вызываться из пункта верхнего верхнего меню «создать». Варианты ответов могут быть разными: либо radio button, либо строка ввода. Также можно прикрепить изображение. Изображение можно будет редактировать по размеру пикселей и перемещать по всей форме. Сохранение викторины будет в файле csv, в котором будут столбцы, позвященный номеру вопроса, затем виджету, затем его свойствам, такие как размер, координаты, при имользовании кнопок можно настроить цвет.
В профиле пользователя будут отображены Информация о профиле и  две кнопки: пройденные тесты и ваши тесты. При нажатии на вторую кнопку будут отображены созданные вами тесты, а при нажатии на любой из  них будут показаны все прошедшие его польщователи в виде таблицы, ктоторую можно будет сортировать по лучшим баллам или по алфавиту. Таблица будет имет столбцы id, имя, процентное количество правильных ответов. 
В пройденных тестах будет показываться таблица, состоящая из столбцов названия теста, количества правильных ответов и места среди других пользователей в нем.
