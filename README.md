# CourseTaskServer
Серверная часть клиент-серверного приложения для расчета заработной платы сотрудников.

Сервер взаимодействует с клиентом по стеку протоколов tcp/ip. Данные перед отправкой клиенту сереализуются в json формат (json строки). 
Следовательно при получении данных от клиента, происходит их json десериализация. Применены (подключены вручную через IDE) следующие инструменты: 
Hibernate, соответствующий СУБД MySQL драйвер, библиотеки Jackson. Применена многоуровневая архитектура, DAO. Велась работа с базой данных из пяти таблиц,
четыре из которых связаны и имеют связи один-ко-многим и многие-к-одному.

Сервер реализует возможности авторизации, регистрации пользователей, расчета заработной платы, просмотра различной информации о ней. 
