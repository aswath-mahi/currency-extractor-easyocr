## CURRENCY_EXTRACTOR_EASYOCR

```markdown
# Currency Extractor EasyOCR

Currency Extractor EasyOCR is a Python package that leverages the EasyOCR library to detect currency symbols in images. This package provides a convenient command-line interface for easy integration into your projects.

## Installation

You can install the package using `pip`:

```bash
pip install currency_extractor_easyocr
```

## Usage

### Command-line Interface

```bash
currency_symbol_extract <image_path> [--symbols SYMBOLS [SYMBOLS ...]] [--languages LANGUAGES [LANGUAGES ...]] [--image_rescale IMAGE_RESCALE]
```

#### Parameters:

- `image_path`: Path to the input image.
- `--symbols`: List of currency symbols to detect. Default is `['$', '€', '£', '¥', '₹','د.ك','₣','AED', 'INR','USD','CAD']`.
- `--languages`: List of OCR languages. Default is `['en', 'ar']`.
- `--image_rescale`: Rescale factor for the image size. Default is `50`.

#### Example:

```bash
currency_symbol_extract path/to/your/image.jpg --symbols $ € £ --languages en
```

### Dependencies

- `opencv-python`: OpenCV library for image processing.
- `easyocr`: EasyOCR library for Optical Character Recognition.

## How it Works

The package utilizes EasyOCR to read text from the input image. It then searches for currency symbols in the recognized text and returns the detected symbols.




## Acknowledgments

- [EasyOCR](https://github.com/JaidedAI/EasyOCR): The OCR library used in this project.

## Support

For any questions or issues, please contact [aswath.codes@gmail.com or GitHub repository issues](https://github.com/aswath-mahi/currency-extractor-easyocr/issues).

```

In this example, I've included sections on usage, dependencies, how it works, licensing, contributing, acknowledgments, and support. You may want to customize these sections based on your specific project details and structure.