# Aetheris Mobile Visuals (Fabric 1.21.4 — PojavLauncher / Zalith Edition)

Готовый проект визуального клиента со всеми распакованными и адаптированными ресурсами из `Destra-assets.zip`.

## Главное управление
* **Открыть / Закрыть меню (ClickGUI):** клавиша **Правый Shift (`Right Shift`)** (`GLFW_KEY_RIGHT_SHIFT`).
  * В **PojavLauncher / Zalith Launcher / FCL** назначьте на удобную экранную кнопку клавишу `SHIFT_RIGHT` (Правый Шифт). В коде реализован двойной опрос (`KeyBinding` + прямой опрос `GLFW_KEY_RIGHT_SHIFT`), поэтому меню открывается и закрывается безотказно при любом типе привязки.

## Как собрать готовый `.jar` за 2 минуты (прямо с телефона через GitHub Actions)
1. Создайте новый репозиторий на GitHub.
2. Загрузите содержимое этого архива в репозиторий (в архиве уже лежит готовый файл `.github/workflows/build.yml`).
3. Перейдите во вкладку **Actions** -> запустите workflow **Build Aetheris Mobile JAR** -> скачайте готовый `.jar` из раздела **Artifacts** и закиньте его в `.minecraft/mods/`.
