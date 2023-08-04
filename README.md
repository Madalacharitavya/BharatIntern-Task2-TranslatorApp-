# Translator AI using the "translate" Package

This Python script implements a Translator AI using the "translate" package. The AI can translate text between different languages using online translation APIs.

## Requirements

- Python 3.x
- `translate` package

## Installation

Install the required `translate` package using pip:

```
pip install translate
```

## Usage

1. Import the necessary functions from the `translate` package and the script:

```python
from translate import Translator
from translator_ai import translate_text
```

2. Prepare your input text and specify the source and target languages:

```python
input_text = "Hello, Deepu!! How are u??"
source_language = 'en'  # English
target_language = 'bn'  # Bengali
```

3. Use the `translate_text` function to translate the text:

```python
translated_text_bn = translate_text(input_text, source_language, target_language)
```

4. Print the original and translated texts:

```python
print(f"Input Text ({source_language}): {input_text}")
print(f"Translated Text ({target_language}): {translated_text_bn}")
```

5. You can add more target languages by changing the `target_language` variable:

```python
target_language = 'de'  # German
translated_text_de = translate_text(input_text, source_language, target_language)
print(f"Translated Text ({target_language}): {translated_text_de}")
```

## Note

- The "translate" package provides a simple interface for language translation using different online translation APIs. Depending on the chosen API and the specific usage, you might need an API key, and usage may be subject to rate limits and other restrictions imposed by the service.
- Make sure to handle exceptions or errors that might occur during translation, such as network connectivity issues or invalid language codes.

## Author

This Translator AI was created by [Your Name].

## Acknowledgments

- The "translate" package is used to implement the translation functionality in this AI. We acknowledge the developers and contributors of the "translate" package for their work.

  Output(DEMO)
