# Finance Tracker — канал сборок

Публичный канал бинарных сборок Finance Tracker для macOS 14+ / Apple Silicon и Windows 11 x64.

## Finance Tracker 0.6.0

- [macOS 14+ / Apple Silicon, сборка 16](https://github.com/r4jzj24k5w-sys/finance-tracker-releases/releases/download/v0.6.0/FinanceTracker-0.6.0-macOS.zip) · [SHA-256](https://github.com/r4jzj24k5w-sys/finance-tracker-releases/releases/download/v0.6.0/SHA256SUMS.txt)
- [Windows 11 x64, предварительная сборка](https://github.com/r4jzj24k5w-sys/finance-tracker-releases/releases/download/v0.6.0/FinanceTracker-0.6.0-Windows-x64.zip) · [SHA-256](https://github.com/r4jzj24k5w-sys/finance-tracker-releases/releases/download/v0.6.0/SHA256SUMS-Windows.txt)

Распакуйте архив Windows целиком и запустите `FinanceTracker.exe`. Для переноса базы экспортируйте парольную копию `.ftbackup` на Mac и выберите «Восстановить из копии» в Windows. [Заметки о выпуске](https://github.com/r4jzj24k5w-sys/finance-tracker-releases/releases/tag/v0.6.0)

## Обновления macOS

Сборка содержит обновления из приложения и зашифрованную локальную историю базы/PDF. Для перехода с 0.1.0 один раз замените приложение вручную, сохранив папку Application Support/FinanceTracker и ключ Keychain. Затем используйте «Проверить обновления…».

Предварительная сборка подписана ad-hoc, без Apple Developer ID и нотариализации. Полный цикл установки и перезапуска через Sparkle требует ручной приемки.

`appcast.xml` — подписанная Ed25519 лента Sparkle. Подпись архива проверяется до распаковки. Финансовые данные остаются на устройстве; в этом репозитории нет баз, документов, ключей или приватного исходного кода.

Sparkle скачивает архив из GitHub Release. Контрольные суммы доступны на странице релиза.

Автоматические source archives GitHub относятся только к публичному описанию, ленте и бинарным файлам этого репозитория.
