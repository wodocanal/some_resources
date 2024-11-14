блокнот организаторов всоша

https://colab.research.google.com/drive/19YClC3ts2xQM_JhDFb4Ob0AY1XZ_pHok?usp=sharing


гитхабы

https://github.com/Spanchb0tik

https://github.com/dark516/ai_taxi

https://github.com/zalupa52


доки 

https://pypi.org/project/transformers/



кагл такси

https://www.kaggle.com/competitions/new-york-city-taxi-fare-prediction/overview


chatgpt бесплатно

https://chatgptchatapp.com/#google_vignette
https://lmarena.ai/



import easyocr
from PIL import Image

# Инициализация считывателя с поддержкой русского языка
reader = easyocr.Reader(['ru', 'en'])  # Можно добавить несколько языков, например 'ru' и 'en'

# Укажите путь к изображению
image_path = "/Users/andrejboriskin/Downloads/Photos with Text.png"  # Замените на путь к вашему изображению
result = reader.readtext(image_path, detail=0)

# Вывод распознанного текста
print("Распознанный текст:", "\n".join(result))
