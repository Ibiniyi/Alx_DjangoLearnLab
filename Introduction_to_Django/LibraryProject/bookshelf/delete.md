# Delete a Book

from bookshelf.models import Book

# Retrieve the book
book = Book.objects.get(id=1)

# Delete the book instance
book.delete()

