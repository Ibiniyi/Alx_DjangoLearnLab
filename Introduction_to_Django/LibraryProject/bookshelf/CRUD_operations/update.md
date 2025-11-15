
---

# ✅ **update.md**

```md
# Update Operation

### Command used in Django shell:

```python
from bookshelf.models import Book

b = Book.objects.get(title="1984")
b.title = "Nineteen Eighty-Four"
b.save()
b

