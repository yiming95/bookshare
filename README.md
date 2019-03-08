# bookshare
A website that allows user to share their info about books.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.
### Introduction

The breif introduction of the project.

```
 The website would allow users to log their books as an online library, 
 they would then be able to easily search through their own books 
 and others in the area to find books on a particular subject. 
 Users can add books to their library by taking a picture of the cover and then the system finds the book online, 
 or alternatively, we provided a less high tech but more reliable option for the user to simply type in the name of the book. 
 We have connected to Google books to take advantage of their search algorithms and wealth of knowledge, 
 both in terms of the breadth of their library and the detailed information that they have on each book.
 
```

## The architecture: 

* The Major system components are as follows:

1. Server: this processes the various requests from multiple clients, 
including requests for webpages; it also processes and search queries 
that come through and provides a buffer between the client and the database for security purposes.
a. Login System: performs security checks and logs users in the database in order to track activity and usage on the site.

2. Database: designed in tandem with the site in order to efficiently hold both user information and library information, 
such that no unnecessary or duplicate information would be held and bloat the database.

3. Frontend: designed to give a professional feel to the site and acts responsively, 
fulfilling the requirements to make the site work across multiple platforms.
a. Search Feature: allows the users to have full access to books stored 
in Google Books and log them as being part of the user’s personal library.
b. Image Recognition Feature: allows the user to take picture of a book cover, 
or submit a saved image to the site in order to read the text on the cover and perform a search based on that text.
      
      
## Screenshots

<img width="1233" alt="screen shot 2019-03-08 at 4 31 53 pm" src="https://user-images.githubusercontent.com/40975373/54009746-231adc80-41c0-11e9-9c4c-54c1b6afecdd.png">
 
<img width="1190" alt="screen shot 2019-03-08 at 4 31 18 pm" src="https://user-images.githubusercontent.com/40975373/54009754-2910bd80-41c0-11e9-9a72-6172c829dcb2.png">


## Further announcement: 

* The project in this repo is the frontend part that I wrote for the website. As the backend was written by 
another Uk classmate and the website has been offline for a long time, 
there are no source code of this project for the backend or database.

## Authors

* **Yiming Zhang** 

## License

This project is licensed under the MIT License.
