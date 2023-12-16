для переноса кода или какого-либо проекта с GH на свой ПК создаем папку, НЕ ДЕЛАЕМ git init, этот шаг пропускаем, сразу в терминале пишем git clone <URL>
а вот для добавления документа с ПК в GH надо:
* создать новый репозиторий в GH и последовательно выполнить 3 команды
git remote add origin https://github.com/NatPws/Connect_PC_GH.git
git branch -M main
git push -u origin main
