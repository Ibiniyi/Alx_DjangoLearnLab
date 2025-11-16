# Delete a Book

# Retrieve the book
book = Book.objects.get(id=1)

# Delete the book instance
book.delete()

