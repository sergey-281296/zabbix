Система мониторинга Zabbix
Задание 1
Установите Zabbix Server с веб-интерфейсом.

Процесс выполнения
Выполняя ДЗ, сверяйтесь с процессом отражённым в записи лекции.
Установите PostgreSQL. Для установки достаточна та версия, что есть в системном репозитороии Debian 11.
Пользуясь конфигуратором команд с официального сайта, составьте набор команд для установки последней версии Zabbix с поддержкой PostgreSQL и Apache.
Выполните все необходимые команды для установки Zabbix Server и Zabbix Web Server.

Требования к результатам

Прикрепите в файл README.md скриншот авторизации в админке.
Приложите в файл README.md текст использованных команд в GitHub.
Ответ:

<img width="1804" height="867" alt="Снимок экрана 2025-11-18 211047" src="https://github.com/user-attachments/assets/16b026a5-0598-4776-b9ca-0e7c5b2c2096" />

<img width="929" height="425" alt="Снимок экрана 2025-11-18 211658" src="https://github.com/user-attachments/assets/c79cfead-d438-444b-85d8-39fa3b37c822" />

Задание 2
Установите Zabbix Agent на два хоста.

Процесс выполнения
Выполняя ДЗ, сверяйтесь с процессом отражённым в записи лекции.
Установите Zabbix Agent на 2 вирт.машины, одной из них может быть ваш Zabbix Server.
Добавьте Zabbix Server в список разрешенных серверов ваших Zabbix Agentов.
Добавьте Zabbix Agentов в раздел Configuration > Hosts вашего Zabbix Servera.
Проверьте, что в разделе Latest Data начали появляться данные с добавленных агентов.
Требования к результатам
Приложите в файл README.md скриншот раздела Configuration > Hosts, где видно, что агенты подключены к серверу
Приложите в файл README.md скриншот лога zabbix agent, где видно, что он работает с сервером
Приложите в файл README.md скриншот раздела Monitoring > Latest data для обоих хостов, где видны поступающие от агентов данные.
Приложите в файл README.md текст использованных команд в GitHub
Ответ:

<img width="1829" height="1020" alt="Снимок экрана 2025-11-21 205320" src="https://github.com/user-attachments/assets/0ddc3d4d-3173-4f0d-b5b0-1ee728360b12" />

<img width="1625" height="224" alt="Снимок экрана 2025-11-21 205355" src="https://github.com/user-attachments/assets/0b172528-97b3-4f4d-af6d-8cfe2d010dc0" />

<img width="1618" height="207" alt="скрин2" src="https://github.com/user-attachments/assets/599032a5-f921-4889-a831-d2a45cedeb5a" />

<img width="924" height="508" alt="скрин" src="https://github.com/user-attachments/assets/3950bf92-a698-423e-ae14-081d6a27691a" />

<img width="1282" height="515" alt="Снимок экрана 2025-11-21 205558" src="https://github.com/user-attachments/assets/3e9f2aa9-a2f1-4dc0-a34f-39dca4cc74be" />


