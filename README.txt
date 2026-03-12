MatveyCraft Ultimate APK Wrapper

Что это:
- Android Studio проект, который открывает игру MatveyCraft Ultimate внутри WebView.
- Игра полностью офлайн и хранит прогресс локально.
- Есть GitHub Actions workflow для сборки APK без Android Studio.

Как собрать APK в GitHub:
1. Создайте пустой репозиторий на GitHub.
2. Загрузите все файлы из этой папки.
3. Откройте вкладку Actions.
4. Запустите workflow: Build Android APK.
5. Скачайте артефакт MatveyCraft-debug-apk.

Как собрать в Android Studio:
1. Откройте папку проекта.
2. Дождитесь синхронизации Gradle.
3. Build -> Build APK(s).

Важно:
- Внутри assets/index.html лежит сама игра.
- Если захотите поменять мир или тексты, редактируйте assets/index.html.
