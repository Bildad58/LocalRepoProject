# delete book that was previously created

delete_book = Book.object.get(title= 'Nineteen Eighty-Four', author = 'George Orwell' publication_year = '1949')
delete_book.delete()

# expected output
# []