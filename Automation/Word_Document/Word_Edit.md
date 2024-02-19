
# Word_Document(Automation)


## Installation⚙️
use the package manager [pip](https://pypi.org/project/pip/) to install *docxtpl*


## Problem🤔
```python 
docx.opc.exceptions.PackageNotFoundError: Package not found at 'Black Style Professional Sales Cover Letter.docx'(line 5)

jinja2.exceptions.templatesyntaxerror: expected token 'end of print statement', got 'number'(line 8 & line 18)
```


## Solution💡
```python
docx.opc.exceptions.PackageNotFoundError: Package not found at 'Black Style Professional Sales Cover Letter.docx'
(1) *Edit file format based on your project directory path...*

jinja2.exceptions.templatesyntaxerror: expected token 'end of print statement', got 'number'
(2) *Change placeholder on the *extract_context* mutable dataset...*
```

