 - настройка Git на компьютере:
        - `git config --global -l` посмотреть текущие настройки
        - `git config --global user.name "Ivan Ivanov"` настройка имени
        - `git config --global user.email "my_email@example.org"` настройка email

        - выгрузить публичный ключ на GitHub
        - просмотр публичного ключа (если ошибка, то надо сгенерировать)
            - `cat ~/.ssh/id_ed25519.pub`
            - `cat ~/.ssh/id_rsa.pub`
        - `ssh-keygen -t ed25519 -C 'email@example.org'` сгенирировать пару ключей (ВЫПОЛНИТЬ ТОЛЬКО В НАЧАЛЕ КАРЬЕРЫ)
        - скопировать публичный ключ на GitHub
        - `ssh -T git@github.com` проверить, что ключ выгружен на GitHub
        **Сохранение**
    - индексация файлов (добавить в очередь на сохранение)
        - `git add .`
    - фиксация (сохранение как таковое)
        - `git commit -m 'описание изменений'`