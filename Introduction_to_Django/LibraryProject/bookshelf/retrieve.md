# Retrieve Operation

### Command used in Django shell:

```python
from bookshelf.models import Book

# Retrieve the book with title "1984"
book = Book.objects.get(title="1984")

book.title
book.author
book.publication_year

