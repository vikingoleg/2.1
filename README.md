1. Створіть новий каталог "new-project" в своєму робочому середовищі.

```
mkdir new-project
cd new-project
```

2. Ініціалізуйте новий Git-репозиторій всередині каталогу "new-project".

```
git init
```

3. Створіть файл "README.md" та додайте початковий текст. Відкрийте його у вашому улюбленому текстовому редакторі та напишіть опис для розробників.

```
touch README.md
```

4. Підготуйте файл "README.md" до коміту, додавши його до стадії.

```
git add README.md
```

5. Закомітьте зміни у репозиторій з коміт-повідомленням "init".
```
git commit -m "init"
```

6. Створіть нову гілку "development" і перейдіть до неї.
```
git branch development
git checkout development
```

7. Додайте інструкцію до файлу "README.md" та підготуйте їх до коміту.
```
# Відкрийте README.md у вашому текстовому редакторі та додайте інструкцію
```

8. Закомітьте зміни у гілці "development" з повідомленням про коміт.
```
git add README.md
git commit -m "Add instructions to README"
```

9. Переключіться на гілку "main".
```
git checkout main
```

10. Об'єднайте зміни з гілки "development" у гілку "main".
```
git merge development
```

11. Переконайтеся, що все актуально та відсутні конфлікти.
```
git status
```

12. Закомітьте зміни.
```
git commit -m "Merge changes from development to main"
```
