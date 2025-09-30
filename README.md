Богдан Фурса
ИТ-11.24.5
FursaBA23@spb.ithub.ru
Git Pull

1.  Скопировать URL на GitHub.
    *   Зайдите на страницу репозитория.
    *   Нажмите зеленую кнопку Code.
    *   Скопируйте ссылку.

2.  Открыть терминал

3.  Перейти в папку, куда вы хотите сохранить проект, с помощью команды cd. Например:
        cd Documents/GitHub
    

4.  Выполнить команду `git clone`:
        git clone https://github.com/your-username/your-repository-name.git
    

5.  Перейти в папку проекта:
        cd your-repository-name
    

Git Push

1.  Добавить измененные файлы в область staged.
    *   Чтобы добавить все измененные файлы:
                git add .
        
    *   Чтобы добавить конкретный файл:
                git add README.md
        

2.  Создать коммит с комментарием, описывающим изменения.
        git commit -m "Описание изменений"
    
    Например: git commit -m "Добавлен README.md с инструкциями по работе с Git"

3.  Загрузить коммит в удаленный репозиторий с помощью команды git push.
        git push origin main
    
    *   origin — стандартное имя для вашего удаленного репозитория.
    *   master — название ветки.

4.  Ввести учетные данные, если будет запрошено:
    *   Username: Ваш логин на GitHub.
    *   Password: Использовать Personal Access Token, а не пароль

Получение токена доступа для GitHub

Для работы через терминал потребуется токен доступа, а не пароль от сайта.

1.  Нажать на аватарку в правом верхнем углу GitHub.
2.  В выпадающем меню выберать Settings.
3.  В меню слева прокрутить вниз и выбрать Developer settings.
4.  Далее выберать Personal access tokens -> Tokens (classic).
5.  Нажать кнопку Generate new token -> Generate new token (classic).
6.  Дать токену название.
7.  Установить срок действия (**Expiration**).
8.  Выбрать scopes.
9.  Нажать Generate token внизу страницы.
10. Скопировать полученный токен, его видно одмн раз.
<img width="1214" height="372" alt="image" src="https://github.com/user-attachments/assets/3baedeb2-852a-426e-a271-43f81d0e0e2e" />
<img width="1206" height="420" alt="image" src="https://github.com/user-attachments/assets/dfd82ae6-363e-4801-80f0-fdfb12154585" />
<img width="1227" height="876" alt="image" src="https://github.com/user-attachments/assets/887975b1-3e6f-4767-beeb-0bea1d734cf0" />
<img width="1053" height="856" alt="image" src="https://github.com/user-attachments/assets/395d39a2-6113-4d9c-8350-7f8aba9e009f" />
<img width="1189" height="327" alt="image" src="https://github.com/user-attachments/assets/99066f1c-c26e-418e-b3d4-1db921575978" />




