# Kotlin

### 1.  Безопасная работа с обнуляемыми переменными (null safety)
![image](https://user-images.githubusercontent.com/43163262/202920404-597fbb12-40f8-4bf4-9b74-21cbdd026dd6.png) 

### 2. Изменяемые (mutable) и неизменяемые (immutable) типы в Kotlin, var и val
![image](https://user-images.githubusercontent.com/43163262/202920531-902d1638-c596-4aa7-a5f4-dfdee41d4d88.png)

### 3. Mutable и Immutable коллекции
![image](https://user-images.githubusercontent.com/43163262/202920575-13600ecf-9aab-4be8-9d09-6fa29ebef30b.png)

### 4. Отличия наследования Kotlin и Java
![image](https://user-images.githubusercontent.com/43163262/202920749-549e8614-b774-47ae-9795-e9420e46624f.png)

### 5. Модификаторы доступа
![image](https://user-images.githubusercontent.com/43163262/202920815-a33cc8c1-b74c-4f01-a7be-3bc3e8e6fd1e.png)

### 6. Конструкторы в Kotlin
![image](https://user-images.githubusercontent.com/43163262/202920870-f9cb00c3-c162-4485-b4b8-0f37c2fa202f.png)

### 7. Extensions в Kotlin
![image](https://user-images.githubusercontent.com/43163262/202920981-792ab35f-0b5f-440e-bedc-2c4bfe1812b3.png)

### 8. Функции высшего порядка
![image](https://user-images.githubusercontent.com/43163262/202921061-849f6885-1765-409a-ba03-938ab67ae6a3.png)

### 9. Data-классы
![image](https://user-images.githubusercontent.com/43163262/202921474-23292f3d-a9d0-4dd6-b566-153ee5257a46.png)

### 10. Статические члены
![image](https://user-images.githubusercontent.com/43163262/202921566-0bafc0ab-7784-41b6-bf03-cefd498d56de.png)

### 11. Ленивая иницализация
![image](https://user-images.githubusercontent.com/43163262/202921786-58b2f441-1c46-4b19-af3e-2011c5bad9a2.png)

# Android

## С чего начинаем

### 1. Файл AndroidManifest
![image](https://user-images.githubusercontent.com/43163262/202922347-d433aad9-2363-4bef-b8ab-99f866122b56.png)

### 2. Основыне группы разрешений
Назвать 2 группы обычные и опасные, привести примеры

### 3. Основные компоненты Android-приложения
![image](https://user-images.githubusercontent.com/43163262/202922427-caaea8de-b285-4173-9f2a-7de6b5c669e0.png)

### 4. Что такое Activity
![image](https://user-images.githubusercontent.com/43163262/202922700-4d10b3b8-d0bb-40d9-b385-d37da86a80f1.png)

### 5. Жизненный цикл Activity
![image](https://user-images.githubusercontent.com/43163262/202922727-1863ac5b-79a2-45b1-bd91-0dd86b0551f3.png)

### 6. Как пережить поворот экрана
![image](https://user-images.githubusercontent.com/43163262/202923086-8d85752f-a5d7-4bdb-b1ab-d8abf0f48570.png)

### 7. Что такое Bundle
![image](https://user-images.githubusercontent.com/43163262/202924417-9875c92a-f26e-445e-a82e-399817ef6a73.png)

### 8. Навигация между Activity и как передать данные между ними
Перейти на другое Activity можно методом startActivity и передачей туда Intent. В Intent мы можем положить примитивы и parcelize-объекты, для передачи их на другое Activity
![image](https://user-images.githubusercontent.com/43163262/202924197-3a133929-7626-44f2-9e01-d7e62fc17eda.png)

### 9. Что такое Intent и почему мы можем положить в него данные
![image](https://user-images.githubusercontent.com/43163262/202924445-82d6d2db-4137-4eec-a7d8-21d1e0b75fd9.png)

### 10. Что такое Fragment
![image](https://user-images.githubusercontent.com/43163262/202923644-aab074f6-47cc-4e1e-bf73-2e875d0efd9d.png)

### 11. Жизненный цикл Fragment
![image](https://user-images.githubusercontent.com/43163262/202923702-c9986ce1-a6af-4634-ad74-ec8c77f8236c.png)

### 12. Навигация между фрагментами
Через стандартные FragmentManager и FramentTransaction или с помощью библиотек NavigationComponent или Ciceron.
![image](https://user-images.githubusercontent.com/43163262/202924804-324a19ce-d8b2-4449-adbd-bf560c353eac.png)

## Как показываем и привязываем представления к коду

### 13. Layouts в Android
![image](https://user-images.githubusercontent.com/43163262/202924988-2634008d-9830-4e69-9f77-9c2b956dfd74.png)

### 14. Как делать списки. RecyclerView, в чём отличие от ListView
![image](https://user-images.githubusercontent.com/43163262/202925075-5d2e93ac-78d9-4769-a9df-170aa7a43e45.png)

### 15. Связывание вёрстки и кода
![image](https://user-images.githubusercontent.com/43163262/202925239-06168235-aa2d-43e5-9b8c-8a0add6e458c.png)

## Чуть чуть архитектуры

### 16. Что такое ViewModel
![image](https://user-images.githubusercontent.com/43163262/202925413-71f26b35-1cc7-4f59-b022-03d32283828a.png)

### 17. Что такое LiveData
![image](https://user-images.githubusercontent.com/43163262/202925447-83422c49-2375-4399-9557-e04fc0de3501.png)

### 18. Подписка на LiveData во фрагментах
![image](https://user-images.githubusercontent.com/43163262/202925869-3dd96559-f44f-4e8e-8be6-6de6f443091d.png)

### 19. Разница между LiveData.observe() и LiveData.observeForever()
![image](https://user-images.githubusercontent.com/43163262/202925916-07c47671-5c16-4915-9307-b975ad4739e3.png)

## Остальное

### 20. Как работать с сетью, с REST API.
Хотелось бы услышать про Retrofit и как его объявить. Практически всегда нам нужен один инстанс Retrofit, соответственно синглтон. И если мы не используем DI, то лучше нам это сделать в классе Application, т.к. это нативный синглтон.
![image](https://user-images.githubusercontent.com/43163262/202990445-74d05c37-1f67-4f15-a7d4-0968d9e42bc2.png)
Также сетевые и вообще долгие операции нельзя выполнять в UI-потоке и нужно выносить их в фоновый поток. 

### 21. Способы работы с многопоточностью. Как ты будешь работать с этим
### Почему не стоит использовать asyncTask. 
 - AsyncTask не привязаны к жизненному циклу активити. При пересоздании активити onPostExecute() выполнится, но активити будет не та (и она может утечь, что совсем не круто).
 - Соответственно, чтобы правильно использовать AsyncTask нужно заморочиться.
 - Неудачный API. Часто работа с бэкграунд тредом в андроид-приложениях – это запрос в сеть или базу данных. Для обработки результата достаточно методов onSuccess() и onError(). AsyncTask предоставляет обычно ненужные коллбэки onPreExecute() и onProgressUpdate(), а также метод onPostExecute(), который вызывается в случаях и успешного выполнения, и ошибки. Это требует писать больше бойлерплейта.
 - На разных версиях андроида выполнение нескольких AsyncTask реализовано по-разному:
 1) До Api level 4 использовался единственный тред и все AsyncTask выполнялись по очереди.
 2) Начиная с Api level 4 и до 11 использовался тред пул и AsyncTask выполнялись параллельно.
 3) Начиная с Api level 11 снова начали использовать единственный тред.

### Что удобно использовать для сетевых запросов (RxJava, Корутины). Что использовать для долгих опреаций (WorkManager с воркерами).
