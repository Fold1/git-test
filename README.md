git config --list           проверка конфига
cd "C:\Users\cff22\Desktop\my-projects\git-test"         переход к папке
git init            инициализация  
git remote add origin URL          соединение локального репозитория с удалённым
git clone URL           скачивает все файлы из удалённого репозитория, создавая локальную копию этого репозитория
git status          показывает текущий статус всех несохранённых изменений фалов в репозитории
git add .         подготавливает данные файлы к следующему коммиту, добавляя их в хранилище файлов, готовых к коммиту
git commit -m "message"           запоминает версию (коммит) всех файлов в репозитории из индекса и присваивает ей уникальный код, по которому затем к этой версии можно вернуться
git log         показывает историю всех коммитов в данной ветке с их хэшами и сообщениями
git checkout хэш            позволяет вернуться к конкретной версии коммита по хэш номеру
git push имя_репозитория(origin) ветка(master)          публикует коммиты из вашего локального репозитория в удалённый с данным именем в данной его ветке
git pull имя_реп ветка          скачивает из данного удалённого репо все коммиты в данной ветке, которых ещё нет в локальном репо
git branch          выводит список локальных веток, доступных прямо сейчас в данном локальном репозитории
git branch имя_ветки            создаёт новую локальную ветку из той, на которой прямо сейчас находится пользователь
git checkout имя_ветки          переключает пользователя на данную локальную ветку. Все новые коммиты после этого будут делаться именно в этой ветке
git merge имя_ветки             производит слияние данной ветки в ветку, на которой прямо сейчас находится пользователь в виде одного нового коммита в текущую ветку          