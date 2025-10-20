## Usage

Установка

```bash
pip install split-pdf-by-page
```

Командная строка

```bash
split-pdf /path/to/document.pdf
```

Если вы запускаете напрямую (без установки):

```bash
python -m split_pdf_by_page.cli /path/to/document.pdf
```

Пример использования в коде (встроенная функция из пакета)

```python
from pathlib import Path
from split_pdf_by_page.cli import split_pdf

split_pdf(Path("input.pdf"))
```

https://pypi.org/project/split-pdf-by-page

