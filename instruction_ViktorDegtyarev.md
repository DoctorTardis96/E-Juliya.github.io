# Работа с удаленным репозиторием git\github.com

1. Для начала нужно нажать выбрать репозиторий на github.com в котором мы хотим производить работы и нажимаем *"fork"* эта кнопушка копирует репозиторий в наши репозитории на github.com.
2. После того, как мы копипастнули репозиторий, заходим в него и нажимаем *""Code* и копипастим код этого репозитория.
3. Заходим в консоль git'a в VSCODE и прописываем слудющую команду
    *                  git clone копипастнутый адрес
4. После, для работы в копипастнутом репозиторием мы используем слудющую команду
    *                   CD имя папки с репозиторием (просто TAB'аем до тех пор пока не появится нужное)
5. В идеале создаем другую ветку для того, для того что бы в итоге владелец основного репозитория сам сделал мёрдж если он согласится с изменениями.
6. Производим какие то изменения или добавляем то, что считаем нужным.
7. Сохраняем, комитим, отправляем. Отправлять следующей командой
    *                     git push
8. Возвращаемся на github.com, заходим в репозиторий в который мы Push'или и нажимаем вкладку *"Pull requests"*. Нажимаем *"New pull request"*, выбираем ветку с которой предлагаем смержить и нажимаем *"create pull request"*.

   <u>ГОТОВО.</U>

## КАК ДОБАВИТЬ ДАННЫЕ С ГИТА В СВОЙ РЕПОЗИТОРИЙ НА GITHUB.COM
1. Создаем новый репозиторий на github.com
2. Копируем код репозитория.
3. Прописываем слудующую команду
    *             git remote add origin копипаст кода
4. Прописываем следующую команду в случае, если надо изменить название главной ветки
    *           git branch -M новое имя главной ветки
5. Указываем слудующей командой имя главной ветки для github.com
   *                git push -u origin имя ветки
6. После окончания работы с файлами своего репозитория сохраняем, комитим и отправляем командой 
    *                      git push 