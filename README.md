# запуск бота 
~~
pip install - r requirements.txt
python bot.py
inline_keyboard = InlineKeyboardMarkup(
    inline_keyboard=[
        [InlineKeyboardButton(text="Перейти на сайт", url="http://example.com")],
        [InlineKeyboardButton(text="Нажми", callback_data="button_click")]
    ]
)
~~
