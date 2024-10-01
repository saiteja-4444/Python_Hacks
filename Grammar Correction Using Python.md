# Grammar correction in Python

``` python
pip install textblob
```
``` python
from textblob import TextBlob

def correct_grammer(text):
    blob=TextBlob*(text)
    corrected_text=str(blob.correct())
    return corrected_text

text=input("Enter your Sentence: ")
corrected_text = correct_grammer(text)
print(f"corrected: {corrected_text}")
```
# output
```
Enter your Sentence: mathemtics
Corrected: mathematics
```

![p](https://github.com/user-attachments/assets/8f300184-45ae-4e23-9861-523a957a8a8d)
