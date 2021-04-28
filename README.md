cd ~/.ssh/
ssh-keygen -t rsa -C "username@mail.ttt"

Enter file in which to save the key: github

Переходим в настройки аккаунта (Settings)
Переходим в SSH and GPG keys
New SSH key

Вставляем содержимое файла
cat github.pub
