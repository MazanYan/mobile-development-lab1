# Додаток на React Native до курсу "Програмування мобільних систем"

## Складнощі, що виникли під час виконання завдання
Як таких склоднощів не виникло. Виникла необхідність використати 
замість полів "Organisation Name" і "Organisation Identifier",
що використовуються в описових файлах для проєктів на Swift,
на поля "Author" та "Contributors" у package.json.

Для того, щоб змінити deployment target для iOS із версії ОС 10.0
до 11.0, довелося змінити поле "platform" у Podfile. 

Іконки довелось для кожної із платформ додати у відповідні для них
теки:

Android: ./android/app/src/main/res/minmap-*/ic_launcher.png
iOS: ./ios/MobileDevelopmentCourseApp/Images.xcassets/appstore.png
