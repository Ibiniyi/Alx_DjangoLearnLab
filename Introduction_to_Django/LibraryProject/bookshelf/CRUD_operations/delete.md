
---

# ✅ **delete.md**

```md
# Delete Operation

### Command used in Django shell:

```python
from bookshelf.models import Book

b = Book.objects.get(title="Nineteen Eighty-Four")
b.delete()

