# this updates the selected attribute of the book

update_book = Book.object.get(title = '1984)

# update the book
update_book.title = 'Nineteen Eighty-Four'
update_book.save()