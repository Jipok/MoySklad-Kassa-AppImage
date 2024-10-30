# МойСклад Касса AppImage

Это неофициальная сборка программы "МойСклад Касса" в формате AppImage для Linux.

## Что такое AppImage?

[AppImage](https://ru.wikipedia.org/wiki/AppImage) - это формат портативных приложений для Linux, который позволяет запускать программы без установки. Основные преимущества:

- Не требует установки и root-прав
- Работает на большинстве Linux-дистрибутивов
- Содержит все необходимые зависимости
- Легко обновлять и удалять

## Как использовать

1. Скачайте последний релиз из раздела [Releases](https://github.com/Jipok/MoySklad-Kassa-AppImage/releases)

2. Сделайте файл исполняемым:
   ```bash
   chmod +x ./moysklad-kassa*.AppImage
   ```
   Или через графический файловый менеджер: ПКМ -> Свойства -> Права -> Поставить галочку "Исполняемый"

3. Запустите приложение двойным кликом или через терминал:
   ```bash
   ./moysklad-kassa*.AppImage
   ```

4. Для обновления скачайте новый AppImage файл и замените им старый.

## Возможные проблемы

При обновлении или откате на старую версию могут возникнуть проблемы (белый экран, приложение не запускается). Это происходит из-за того, что разработчики периодически меняют формат локальных данных (авторизация, кеши и т.д.). Особенно вероятно, если пропустить несколько версий обновлений.

Для решения удалите локальные данные приложения:
```bash
rm -rf ~/.config/moysklad-kassa
```
После этого потребуется заново авторизоваться в приложении.

По вопросам, связанным с этой AppImage-сборкой, можете обращаться в Telegram: @Jipok. Однако учтите, что я не имею отношения к разработке приложения и компании МойСклад.
