 create database

 create table
 CREATE TABLE `books` (
  `book_id` int(11) NOT NULL,
  `book_isbn` int(11) NOT NULL,
  `book_title` varchar(50) NOT NULL,
  `book_author` varchar(50) NOT NULL,
  `book_category` varchar(50) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

insert demo data

INSERT INTO `books` (`book_id`, `book_isbn`, `book_title`, `book_author`, `book_category`) VALUES
(2, 7893, 'Laravel Tiger', 'Mutafaf', 'Programming'),
(3, 8934, 'Android Programming', 'Farrukh', 'Programming'),
(6, 8902, 'Intro to Psychology', 'Ayesha', 'Psychology'),
(7, 2345, 'Calculus-1', 'John doe', 'Math'),
(8, 8927, 'Chemistry Part-1', 'Aliza Mam', 'Chemistry'),
(9, 6723, 'Math Part-1', 'Sir Sohail Amanat', 'Math'),
(10, 7896, 'Javascript for begginners', 'Shami ', 'Programming'),
(11, 8978, 'iOS App ', 'Ehtesham Mehmood', 'Mobile Programming'),
(12, 8987, 'Physics', 'Sir Waqas', 'Physics'),
(13, 7890, 'HTML for dummies', 'Ehtesham Shami', 'Programming'),
(14, 1234, 'CodeIgniter Framework Introduction', 'Mutafaf', 'Programming');

add model in construct in controller

add all required functions for crud in modal and controller