**Загрузка данных**

Так как файлы большие, то прикреплять сюда я их не буду. В ходе работы я подгружал уже обработанные данные с Google Drive.

Загрузить данные можно напрямую с HuggingFace с помощью команды:

```python
from datasets import load_dataset

data_path = "MonoHime/ru_sentiment_dataset"
dataset = load_dataset(data_path, revision="main")
```

