Охотник за скидками — проект для AndroidIDE

Что умеет первая версия:
1. Добавлять товар в список отслеживания.
2. Указывать максимальную желаемую цену.
3. Открывать поиск товара в:
   - Ozon
   - Wildberries
   - Яндекс.Маркет
4. Работает светлая и тёмная тема Android.
5. Есть уведомление-напоминание каждые 6 часов.

Как открыть в AndroidIDE:
1. Скачай ZIP.
2. Распакуй архив.
3. Открой AndroidIDE.
4. Нажми Open Project.
5. Выбери папку DiscountHunter_AndroidIDE, где лежит settings.gradle.
6. Дождись Gradle Sync.
7. Нажми Build или Run.

Если AndroidIDE ругается на compileSdk 35:
Открой app/build.gradle и поменяй:

compileSdk 35
targetSdk 35

на:

compileSdk 34
targetSdk 34

Где менять цвета:
- app/src/main/res/values/colors.xml — светлая тема
- app/src/main/res/values-night/colors.xml — тёмная тема

Где основной код:
- app/src/main/java/com/vitlmet/discounthunter/MainActivity.java

Важно:
Это первая локальная версия. Она не парсит цены сама, потому что маркетплейсы часто блокируют прямой парсинг.
Сейчас приложение быстро открывает поиск и хранит твой список товаров.
Следующая версия может быть с сервером/ботом, который будет проверять цены автоматически.
