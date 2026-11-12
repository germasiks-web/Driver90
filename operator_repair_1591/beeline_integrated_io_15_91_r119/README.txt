15.91-io r119 — объединение веток

Основа: r118 из nik236098-dotcom/tess (ветка codex-operator-observer-15.87):
eSIM-номер и ссылка заказа (r107–r113), сжатый свап в памяти (r117),
разбор паспорта в базе (r118).

Добавлено из Driver90 r107–r109:
- REASONING_BACK_1591R107: reasoning_content DeepSeek возвращается в историю агента (нет HTTP 400);
- BTN_PLAIN_1591R108/R109: обычные эмодзи на кнопках, в т.ч. главного меню.

Ставится поверх r106–r109 из Driver90 и поверх r118 из tess.
Обновление: кнопка «⬆️ Обновить бота» или  sudo beeline-update
Проверка без установки: python3 install.py --app /opt/beeline
