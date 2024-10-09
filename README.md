# **Практическая работа №1. Работа с Git. Основы**
## Работу выполнила студентка 4 курса Степанова Дарья
Git — это распределенная система управления версиями, которая используется для отслеживания изменений в исходном коде программного обеспечения и координации работы нескольких разработчиков над одним проектом. Он был создан Линусом Торвальдсом в 2005 году.
Основные цели Git:
1.	Отслеживание изменений.
2.	Коллаборация.
3.	Ветвление и слияние.
4.	Локальная работа.
6.	Откат к предыдущим версиям.

## Шаг 1. Установка GIT
После установки в контекстном меню появится Open Git Bash here, открываем его.
Итак, мы установили git, теперь нужно добавить немного настроек. Есть довольно много опций, с которыми можно играть, но мы настроим самые важные: наше имя пользователя и адрес электронной почты. Откройте терминал git bush и запустите команды:
- git config --global user.name "Ваше имя" 
- git config --global user.email ВашаПочта@example.com 
- git config --global color.ui true 
- git config --global color.status auto 
- git config --global color.branch auto
- 
Как мы отметили ранее, git хранит свои файлы и историю прямо в папке проекта. Чтобы создать новый репозиторий, нам нужно открыть терминал, зайти в папку нашего проекта и выполнить команду init. Это включит приложение в этой конкретной папке и создаст скрытую директорию. git, где будет храниться история репозитория и настройки.
