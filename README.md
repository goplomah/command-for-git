### Команды для связывания удаленного и локального репозитория.

- Заходим в папку проекта локального репозитория и инициализируем git командой git init
- Далее заходим на github и создаём удалённый репозиторий (имя локального и удалённого репозитория не обязательно должны совпадать)
- Связывание локального и удалённого репозитория происходит командой git remote add origin *здесь должна быть ссылка на удалённый репозиторий*
- Проверка связанности репозиториев производится командой git remote -v
- Далее производим связывание веток локального и удалённого репозитория. Выполняется данное действие при пуше первого коммита командой git push -u origin main. 
При дальнейших пушах можно использовать просто команду git push.


Более удобный способ - копирование удалённого репозитория на локальную машиину. Производится командой git clone *здесь должна быть ссылка на удалённый репозиторий*


Проба mermaid схемы:

```mermaid
graph LR;
%% стрелка без текста для примера:
A-->B;