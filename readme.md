1.Создайте пустой репозиторий на сервисе github.com (или gitlab.com, или bitbucket.com).
2.Выполните инструкцию по созданию первого коммита на странице репозитория, созданного на предыдещем шаге.
![изображение](https://user-images.githubusercontent.com/65495621/170830346-c185f9b0-5695-4cd0-89de-a47c5fcb793a.png)
3.Создайте файл hello_world.cpp в локальной копии репозитория (который должен был появиться на шаге 2). Реализуйте программу Hello world на языке C++ используя плохой стиль кода. Например, после заголовочных файлов вставьте строку using namespace std;.
4.Добавьте этот файл в локальную копию репозитория.
5.Закоммитьте изменения с осмысленным сообщением.
![изображение](https://user-images.githubusercontent.com/65495621/170830392-5935e962-ad6a-4f99-b172-1e693bac9883.png)
![изображение](https://user-images.githubusercontent.com/65495621/170830454-d757b469-d79b-4338-8972-3971cdfe47be.png)
![изображение](https://user-images.githubusercontent.com/65495621/170830517-0b7ca074-0b25-4b0f-98ca-2655f73d23e0.png)
6.Изменитьте исходный код так, чтобы программа через стандартный поток ввода запрашивалось имя пользователя. А в стандартный поток вывода печаталось сообщение Hello world from @name, где @name имя пользователя.
![изображение](https://user-images.githubusercontent.com/65495621/170831054-459c3d90-3d22-41d6-afb9-0645a2ac3c62.png)
7.Закоммитьте новую версию программы. Почему не надо добавлять файл повторно git add?
8.Запуште изменения в удалёный репозиторий.
9.Проверьте, что история коммитов доступна в удалёный репозитории.
Part II
1.В локальной копии репозитория создайте локальную ветку patch1.
![изображение](https://user-images.githubusercontent.com/65495621/170831445-90821be7-bbb5-4b0c-ae2f-31d456b3d653.png)
2.Внесите изменения в ветке patch1 по исправлению кода и избавления от using namespace std;.
![изображение](https://user-images.githubusercontent.com/65495621/170831272-31e7c8eb-e47c-4cad-b58e-798656f392b4.png)
3.commit, push локальную ветку в удалённый репозиторий.
![изображение](https://user-images.githubusercontent.com/65495621/170831470-26270133-6f63-48cc-b5d3-568332497297.png)
4.Проверьте, что ветка patch1 доступна в удалёный репозитории.
5.Создайте pull-request patch1 -> master.
6.В локальной копии в ветке patch1 добавьте в исходный код комментарии.
7.commit, push.
![изображение](https://user-images.githubusercontent.com/65495621/170831711-7b93da9b-9760-4414-9101-e4c22ce8a20e.png)
![изображение](https://user-images.githubusercontent.com/65495621/170831786-7d7b5573-b2e3-4590-9442-a359f274a902.png)
![изображение](https://user-images.githubusercontent.com/65495621/170831902-e04d39a4-2f3a-49b0-9f27-76d80693ba5b.png)
Локально выполните pull.
С помощью команды git log просмотрите историю в локальной версии ветки master.
Удалите локальную ветку patch1.
Part III
Создайте новую локальную ветку patch2.
Измените code style с помощью утилиты clang-format. Например, используя опцию -style=Mozilla.
![изображение](https://user-images.githubusercontent.com/65495621/170832615-ce200d2c-6e65-481b-a0ba-4cb6c1b0ea77.png)
commit, push, создайте pull-request patch2 -> master.
![изображение](https://user-images.githubusercontent.com/65495621/170832747-c41fa917-1dce-4043-9595-3bdffcafd68a.png)
![изображение](https://user-images.githubusercontent.com/65495621/170832898-3634a978-69bf-4e3a-a94f-9d6aba019299.png)






