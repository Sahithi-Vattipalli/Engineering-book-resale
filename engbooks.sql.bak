-- phpMyAdmin SQL Dump
-- version 3.2.0.1
-- http://www.phpmyadmin.net
--
-- Host: localhost
-- Generation Time: Apr 12, 2014 at 12:55 PM
-- Server version: 5.1.36
-- PHP Version: 5.3.0

SET SQL_MODE="NO_AUTO_VALUE_ON_ZERO";


/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8 */;

--
-- Database: `engbooks`
--

create database engbooks;
use engbooks;

-- --------------------------------------------------------

--
-- Table structure for table `books`
--

CREATE TABLE IF NOT EXISTS `books` (
  `name` varchar(30) DEFAULT NULL,
  `autior` varchar(30) DEFAULT NULL,
  `id` varchar(30) DEFAULT NULL,
  `edition` varchar(30) DEFAULT NULL,
  `yearpublish` varchar(30) DEFAULT NULL,
  `isbn` varchar(30) DEFAULT NULL,
  `price` varchar(30) DEFAULT NULL,
  `description` varchar(100) DEFAULT NULL,
  `stream` varchar(30) DEFAULT NULL,
  `rate` varchar(30) DEFAULT NULL
) ENGINE=MyISAM DEFAULT CHARSET=latin1;

--
-- Dumping data for table `books`
--

INSERT INTO `books` (`name`, `autior`, `id`, `edition`, `yearpublish`, `isbn`, `price`, `description`, `stream`, `rate`) VALUES
('word power', 'norman lewis', '123344', '3', '2323', '3424', '120', 'good book', 'any', '5/5'),
('.,m.ml', 'ml.m', 'lm', 'lkm', 'klmkl', 'mkl', 'ml', 'mkl', 'l', 'mkl'),
('abcd', 'xyz', '12', '1', '2014', '12345678', '120', 'hi how r u?', 'IT', '5');

-- --------------------------------------------------------

--
-- Table structure for table `comments`
--

CREATE TABLE IF NOT EXISTS `comments` (
  `Commentson` varchar(30) DEFAULT NULL,
  `CommentsBy` varchar(30) DEFAULT NULL,
  `CommentsDes` varchar(30) DEFAULT NULL
) ENGINE=MyISAM DEFAULT CHARSET=latin1;

--
-- Dumping data for table `comments`
--

INSERT INTO `comments` (`Commentson`, `CommentsBy`, `CommentsDes`) VALUES
('abcd', 'JNTUH', 'nice');

-- --------------------------------------------------------

--
-- Table structure for table `feedback`
--

CREATE TABLE IF NOT EXISTS `feedback` (
  `FeedBack` varchar(30) DEFAULT NULL,
  `FeedBackDes` varchar(30) DEFAULT NULL,
  `FeedBackBy` varchar(30) DEFAULT NULL
) ENGINE=MyISAM DEFAULT CHARSET=latin1;

--
-- Dumping data for table `feedback`
--


-- --------------------------------------------------------

--
-- Table structure for table `rating`
--

CREATE TABLE IF NOT EXISTS `rating` (
  `t1` varchar(20) NOT NULL,
  `t2` varchar(20) NOT NULL,
  `t3` varchar(20) NOT NULL,
  `t4` varchar(20) NOT NULL
) ENGINE=MyISAM DEFAULT CHARSET=latin1;

--
-- Dumping data for table `rating`
--

INSERT INTO `rating` (`t1`, `t2`, `t3`, `t4`) VALUES
('abcd', 'JNTUH', '4', 'nice');

-- --------------------------------------------------------

--
-- Table structure for table `user`
--

CREATE TABLE IF NOT EXISTS `user` (
  `name` varchar(30) DEFAULT NULL,
  `rollno` varchar(30) DEFAULT NULL,
  `password` varchar(30) NOT NULL,
  `organisation` varchar(30) NOT NULL,
  `address` varchar(30) NOT NULL,
  `age` varchar(30) NOT NULL,
  `gender` varchar(30) NOT NULL,
  `emailid` varchar(30) NOT NULL,
  `mobileno` varchar(30) NOT NULL,
  `status` varchar(30) NOT NULL,
  PRIMARY KEY (`address`,`age`,`emailid`,`gender`,`mobileno`,`organisation`,`password`)
) ENGINE=MyISAM DEFAULT CHARSET=latin1;

--
-- Dumping data for table `user`
--

INSERT INTO `user` (`name`, `rollno`, `password`, `organisation`, `address`, `age`, `gender`, `emailid`, `mobileno`, `status`) VALUES
('moiz', '2007bit031', '12345678', 'JNTUH', 'JNTUH', '23', 'male', 'abdulmoiz@gmail.com', '1234567890', 'yes');
