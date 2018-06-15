# oo-many-practice-author-publisher

# AUTHORS, PUBLISHERS, BOOKS

 - A publisher has many authors through books
 - An author has many publishers through books
 - A book belongs to a publisher and an author

* Each Publisher has a name and genre
* Publisher#books
* Publisher#authors
* Publisher#new_book_title (makes new book for author)
* Publisher.least_popular
* Publisher.sorted_by_popularity (highest to lowest)
* Publisher.find_by_genre

===================================

* Each Author has a name
* Author#books
* Author#publishers
* Author#write_book (makes new book for publisher)
* Author.most_active_author => returns the author who has most books for publisher

===================================

* Each book has an author and a publisher
* Book#Author
* Book#Publisher
