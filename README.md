# Домашнее задание к занятию "`Zabbix часть 2`" - `Ivanov Danila`

# Задание 1. Шаблон для мониторинга CPU и RAM хоста.
Задание 1
Создайте свой шаблон, в котором будут элементы данных, мониторящие загрузку CPU и RAM хоста.

Процесс выполнения
Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
В веб-интерфейсе Zabbix Servera в разделе Templates создайте новый шаблон
Создайте Item который будет собирать информацию об загрузке CPU в процентах
Создайте Item который будет собирать информацию об загрузке RAM в процентах
Требования к результату
 Прикрепите в файл README.md скриншот страницы шаблона с названием «Задание 1»

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/bfd716ab-d1c5-4fd3-9601-a460638f700b" />



<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/cf4cff65-d5c9-46fb-954f-5fbe0263c69f" />

# РАБОЧИЕ ХОСТЫ
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/59435142-6e6e-4460-911c-fa56c21707ab" />


 
Задание 2
Добавьте в Zabbix два хоста и задайте им имена <фамилия и инициалы-1> и <фамилия и инициалы-2>. Например: ivanovii-1 и ivanovii-2.

Процесс выполнения
Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
Установите Zabbix Agent на 2 виртмашины, одной из них может быть ваш Zabbix Server
Добавьте Zabbix Server в список разрешенных серверов ваших Zabbix Agentов
Добавьте Zabbix Agentов в раздел Configuration > Hosts вашего Zabbix Servera
Прикрепите за каждым хостом шаблон Linux by Zabbix Agent
Проверьте что в разделе Latest Data начали появляться данные с добавленных агентов
Требования к результату
 Результат данного задания сдавайте вместе с заданием 3
# Задание 3
Привяжите созданный шаблон к двум хостам. Также привяжите к обоим хостам шаблон Linux by Zabbix Agent.
Процесс выполнения
Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
Зайдите в настройки каждого хоста и в разделе Templates прикрепите к этому хосту ваш шаблон
Так же к каждому хосту привяжите шаблон Linux by Zabbix Agent
Проверьте что в раздел Latest Data начали поступать необходимые данные из вашего шаблона
Требования к результату
 Прикрепите в файл README.md скриншот страницы хостов, где будут видны привязки шаблонов с названиями «Задание 2-3».
<img width="1919" height="1079" alt<img width="1918" height="1073" alt="забикс 3 задание" src="https://github.com/user-attachments/assets/4dd1f545-1972-41c1-bf0a-61866b460bff" />
="image" src="https://github.com/user-attachments/assets/48c6b939-81cd-4427-ba1c-e9236b563419" />
<img width="1919" height="1079" alt="Снимок экрана 2026-01-29 003103" src="https://github.com/user-attachments/assets/8d5ccce3-11e3-4369-9f03-f0ce4ed79e03" />
# ПРИВЯЗКА к хостам

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/7bea6b60-f571-4e43-a499-96dcc2415ff9" />


Задание 4
Создайте свой кастомный дашборд.

Процесс выполнения
Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
В разделе Dashboards создайте новый дашборд
<img width="1919" height="1079" alt="забикс 1 задание" src="https://github.com/user-attachments/assets/5b6241e5-4141-4836-b28a-c7764b53714c" />

Разместите на нём несколько графиков на ваше усмотрение.
Требования к результату
 Прикрепите в файл README.md скриншот дашборда с названием «Задание 4»

<img width="1901" height="981" alt="image" src="https://github.com/user-attachments/assets/cc456376-2bbf-4cd2-b7a1-1fb8013478e2" />
<img width="1873" height="946" alt="image" src="https://github.com/user-attachments/assets/d8368940-01ac-4508-a5f8-4b5e3a91205c" />



