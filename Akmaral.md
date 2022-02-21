## Инструкция по работе с удалённым репозиторием

Для того чтобы работать с чужим репозиторием и вносить изменения в локальном репозитории, нужно в своём аккаунте на GitHub найти нужный нам репозиторий, нажать на кнопку Fork и скопировать HTTPS code.  
Создать папку на своем ПК, запустить терминал и набирать следующую команду: 
`git clone <HTTPS код>`
После того, как запустили чужой репозиторий на своём ПК, при успешном клонировании откроются файлы, дальше нужно перейти в эту папку командой: `cd <имя файла>`, и проверить наличие чужого удалённого репозитория командой: `git remote` 

Пример того, как это выглядит:

```
Akmaral@DESKTOP-DKUPT35 MINGW64 ~/Desktop/попытка 4 (Akmaral)
$ git clone https://github.com/akmaralxxx/SCV_Git_1702.git
Cloning into 'SCV_Git_1702'...
remote: Enumerating objects: 15, done.
remote: Counting objects: 100% (15/15), done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 15 (delta 3), reused 15 (delta 3), pack-reused 0
Receiving objects: 100% (15/15), done.
Resolving deltas: 100% (3/3), done.   

Akmaral@DESKTOP-DKUPT35 MINGW64 ~/Desktop/попытка 4 (Akmaral)
$ cd SCV_Git_1702

Akmaral@DESKTOP-DKUPT35 MINGW64 ~/Desktop/попытка 4/SCV_Git_1702 (main)
$ git remote
origin
```