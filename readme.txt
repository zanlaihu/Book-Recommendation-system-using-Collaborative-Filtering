1. This recommendation system using 'Book-Crossing Dataset' from the website below:
http://www2.informatik.uni-freiburg.de/~cziegler/BX/

2. Python surprise package is needed to implement this system. Using the pip command below to install surprise:
pip install surprise

3. Note that the encoding method is necessary in the process of reading dataset. Please follow the codes below to read the dataset:

users = pd.read_csv('book_crossing_dataset/BX-Users.csv', sep=';', encoding='cp1252')
book_ratings = pd.read_csv('book_crossing_dataset/BX-Book-Ratings.csv', sep=';',encoding='cp1252')
books = pd.read_csv('book_crossing_dataset/BX-Books.csv', sep=';',encoding ='iso-8859-1')

The path of file may be different due to different different 
File placement. Please find the correct path in your system to use this system.

