# Retrieving a book from its location

retrieved_book = Book.object.get(book.id)
print(retrieved_book.title,  retrieved_book.author, retrieved_book.publication_year)

# expected output
# title = 1984
# author = George Orwell
# pulication_year = 1949