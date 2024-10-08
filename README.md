# Домашнее задание к занятию "`Git`" - `Арзыбов Владислав`


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---

### Задание 1

**Что нужно сделать:**

1. Зарегистрируйте аккаунт на [GitHub](https://github.com/).

   ![изображение](https://github.com/user-attachments/assets/cfc47d0a-ace5-4850-8c50-35a042db7a6f)

1. Создайте  **новый отдельный публичный репозиторий**. Обязательно поставьте галочку в поле «Initialize this repository with a README».

   ![изображение](https://github.com/user-attachments/assets/3e940efd-aeb2-46d3-871c-77d51ea62d5c)

3. Склонируйте репозиторий, используя https протокол `git clone ...`.

   ![изображение](https://github.com/user-attachments/assets/f239ce45-7c2d-4c79-8e18-dec064e9ebc1)

5. Перейдите в каталог с клоном репозитория.

   ![изображение](https://github.com/user-attachments/assets/e5fd48bb-795b-44e6-ada3-baa52eba1c3d)

1. Произведите первоначальную настройку Git, указав своё настоящее имя и email: `git config --global user.name` и `git config --global user.email johndoe@example.com`.

   ![изображение](https://github.com/user-attachments/assets/0b0b9098-981c-4dee-84c0-2532bdfa1cee)

1. Выполните команду `git status` и запомните результат.

   ![изображение](https://github.com/user-attachments/assets/a00b4634-a2ad-4c8a-b39b-f65d87a61b4a)

1. Отредактируйте файл README.md любым удобным способом, переведя файл в состояние Modified.

   ![изображение](https://github.com/user-attachments/assets/93854cbf-491f-4a7a-a436-50357d9edc84)

1. Ещё раз выполните `git status` и продолжайте проверять вывод этой команды после каждого следующего шага.

   ![изображение](https://github.com/user-attachments/assets/7e1d7625-4468-476c-8e7f-5f432b356623)

1. Посмотрите изменения в файле README.md, выполнив команды `git diff` и `git diff --staged`.

   ![изображение](https://github.com/user-attachments/assets/e0b438ca-9845-420a-852e-ca525096f57c)

1. Переведите файл в состояние staged или, как говорят, добавьте файл в коммит, командой `git add README.md`.

   ![изображение](https://github.com/user-attachments/assets/755e47d1-8c8c-4977-a114-fd4a60b3ce9d)

1. Ещё раз выполните команды `git diff` и `git diff --staged`.

   ![изображение](https://github.com/user-attachments/assets/82cf3079-dc19-4432-84b5-5030061bb20b)

1. Теперь можно сделать коммит `git commit -m 'First commit'`.

   ![изображение](https://github.com/user-attachments/assets/f71080ce-6207-4aa8-8157-81e0ae9f2f54)

1. Сделайте `git push origin master`.

   ![изображение](https://github.com/user-attachments/assets/afb003ed-04cf-4722-bba1-66548a1f55d7)


В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.

https://github.com/vladislav-arzybov/8_1_git/commit/a0bf7302e28150d9201c879f7b3b520b0cba7083


---

### Задание 2

**Что нужно сделать:**

1. Создайте файл .gitignore (обратите внимание на точку в начале файла) и проверьте его статус сразу после создания.

   ![изображение](https://github.com/user-attachments/assets/03c70708-0d75-4f10-aee1-8d38d68ece53)

1. Добавьте файл .gitignore в следующий коммит `git add...`.

   ![изображение](https://github.com/user-attachments/assets/eb72bef5-09a0-46e6-a005-ccd3612653e7)

1. Напишите правила в этом файле, чтобы игнорировать любые файлы `.pyc`, а также все файлы в директории `cache`.

   ![изображение](https://github.com/user-attachments/assets/ae201a2a-32e5-4a90-adb7-6e03ac490d07)

1. Сделайте коммит и пуш.

   ![изображение](https://github.com/user-attachments/assets/cd8a7efc-490c-42de-b407-7b13baf31a80)


В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.

https://github.com/vladislav-arzybov/8_1_git/commit/4a4f571f7331c4a48ebc4c3162cff2e02f6c1544

---

### Задание 3

**Что нужно сделать:**

1. Создайте новую ветку dev и переключитесь на неё.

   ![изображение](https://github.com/user-attachments/assets/433b58df-d1dd-4bc2-9bb6-dc2d8a5940df)

3. Создайте в ветке dev файл test.sh с произвольным содержимым.

   ![изображение](https://github.com/user-attachments/assets/5fcbf019-6138-484b-b6b2-21d3e1b79b8a)

5. Сделайте несколько коммитов и пушей  в ветку dev, имитируя активную работу над  файлом в процессе разработки.

   ![изображение](https://github.com/user-attachments/assets/0fe183c0-39b9-4a79-86b8-29cf7540f1de)

   ![изображение](https://github.com/user-attachments/assets/e621ccd0-e197-4e3c-9b84-58b2be0aad7d)


7. Переключитесь на основную ветку.

   ![изображение](https://github.com/user-attachments/assets/cd769d89-3cae-4538-92fe-daa6f5967a2f)

9. Добавьте файл main.sh в основной ветке с произвольным содержимым, сделайте комит и пуш . Так имитируется продолжение общекомандной разработки в основной ветке во время разработки отдельного функционала в dev  ветке.

    ![изображение](https://github.com/user-attachments/assets/1d134b08-cddf-42b7-9cd9-0cb84c6780ab)

11. Сделайте мердж dev  ветки в основную с помощью git merge dev. Напишите осмысленное сообщение в появившееся окно комита.

    ![изображение](https://github.com/user-attachments/assets/5974e96a-7a7f-40e3-923a-e6f059c91362)

13. Сделайте пуш в основной ветке.

    ![изображение](https://github.com/user-attachments/assets/9aae49ef-6ed3-4690-bf40-2db370a5c3cf)

15. Не удаляйте ветку dev.

В качестве ответа прикрепите ссылку на граф коммитов https://github.com/ваш-логин/ваш-репозиторий/network в ваш md-файл с решением.

https://github.com/vladislav-arzybov/8_1_git/network

Ваш граф комитов должен выглядеть аналогично скриншоту:   

![скрин для Git](https://github.com/netology-code/sdvps-homeworks/assets/77622076/e73589cf-7e97-40e5-ac01-d1d55376f1b9)



---
## Дополнительные задания* (со звёздочкой)

Их выполнение необязательное и не влияет на получение зачёта по домашнему заданию. Можете их решить, если хотите лучше разобраться в материале.

---
### Задание 4*

Сэмулируем конфликт. Перед выполнением изучите [документацию](https://git-scm.com/book/ru/v2/%D0%98%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D1%8B-Git-%D0%9F%D1%80%D0%BE%D0%B4%D0%B2%D0%B8%D0%BD%D1%83%D1%82%D0%BE%D0%B5-%D1%81%D0%BB%D0%B8%D1%8F%D0%BD%D0%B8%D0%B5).

**Что нужно сделать:**

1. Создайте ветку conflict и переключитесь на неё.

   ![изображение](https://github.com/user-attachments/assets/ea39cca7-eb25-45c4-a831-2aa3ed39eb1e)

3. Внесите изменения в файл test.sh.

   ![изображение](https://github.com/user-attachments/assets/81d29da2-4524-4a6e-8634-18883a29e3a3)

5. Сделайте коммит и пуш.

   ![изображение](https://github.com/user-attachments/assets/561ffdcc-43c7-4437-af3a-95d46e561ab2)

   ![изображение](https://github.com/user-attachments/assets/1169148a-e159-4a30-bbd0-750af4c03f2a)


7. Переключитесь на основную ветку.

   ![изображение](https://github.com/user-attachments/assets/abfc8145-0f62-4397-9a0a-9edc9fe5b81c)

9. Измените ту же самую строчку в файле test.sh.

   ![изображение](https://github.com/user-attachments/assets/a253d8a4-5c40-436f-93cd-2844e6f517c7)

11. Сделайте коммит и пуш.

    ![изображение](https://github.com/user-attachments/assets/0bcf13d6-efe6-49ac-ac1f-d627eb71f892)

    ![изображение](https://github.com/user-attachments/assets/bf5552d1-f840-4723-bb68-50af7e4af50f)


13. Сделайте мердж ветки conflict в основную ветку и решите конфликт так, чтобы в результате в файле оказался код из ветки conflict.

    ![изображение](https://github.com/user-attachments/assets/3c481ee5-4e71-49c8-b360-f10044ef7ede)

    ![изображение](https://github.com/user-attachments/assets/d075ea17-2b48-4a90-8f07-8cba04c8c711)

    ![изображение](https://github.com/user-attachments/assets/ec3d901b-b6f1-4ecf-b6d0-710d0c110733)

    ![изображение](https://github.com/user-attachments/assets/3f894d80-40db-433f-97dc-0ce9ff84de5d)

    ![изображение](https://github.com/user-attachments/assets/2404ee83-e18b-4a89-b259-cf6bdfc36fc7)

В качестве ответа на задание прикрепите ссылку на граф коммитов https://github.com/ваш-логин/ваш-репозиторий/network в ваш md-файл с решением.

https://github.com/vladislav-arzybov/8_1_git/network

![изображение](https://github.com/user-attachments/assets/99c26cde-4cf7-423f-a7e5-d26e1b2a93b7)

