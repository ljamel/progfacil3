<template>
    <div class="commandes">
        -- phpMyAdmin SQL Dump
-- version 4.9.5
-- https://www.phpmyadmin.net/
--
-- Host: localhost:3307
-- Generation Time: Oct 13, 2021 at 11:59 AM
-- Server version: 5.7.24
-- PHP Version: 7.3.7 

SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
SET AUTOCOMMIT = 0;
START TRANSACTION;
SET time_zone = "+00:00";


/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8mb4 */;

--
-- Database: `topachat`
--

-- --------------------------------------------------------

--
-- Table structure for table `commandes`
--

CREATE TABLE `commandes` (
  `id` int(11) NOT NULL,
  `date` date NOT NULL DEFAULT '2020-11-23',
  `numfacture` varchar(255) NOT NULL,
  `user` varchar(255) NOT NULL,
  `price` decimal(6,2) NOT NULL,
  `pay` decimal(6,2) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8;

--
-- Dumping data for table `commandes`
--

INSERT INTO `commandes` (`id`, `date`, `numfacture`, `user`, `price`, `pay`) VALUES
(1, '2020-11-23', 'LKLKsdf', 'jean', '325.00', '250.00'),
(2, '2021-09-23', 'KJKjds', 'bejamin', '36.00', '36.00'),
(3, '2020-12-23', 'Lkjkj', 'jean', '25.00', '24.00'),
(4, '2021-10-07', 'KJKjds', 'bejamin', '136.00', '136.00'),
(5, '2021-10-11', 'Lkjpoj', 'jean', '825.00', '824.00'),
(6, '2021-10-02', 'KJKds', 'bejamin', '536.00', '610.00'),
(7, '2020-11-23', 'Lkseoj', 'jean', '85.00', '91.00'),
(8, '2020-11-23', 'dlKds', 'bejamin', '16.00', '14.00'),
(9, '2021-10-11', 'Lksdzj', 'jean', '5.00', '5.00'),
(10, '2021-07-23', 'dlKdds', 'bejamin', '18.00', '18.00'),
(11, '2021-09-23', 'Lksdzj', 'nicolas', '95.00', '95.00'),
(12, '2020-10-08', 'dlKdds', 'mathieu', '418.00', '0.00'),
(13, '2020-11-23', 'Lsddzj', 'nicolas', '145.00', '145.00'),
(14, '2021-01-23', 'dlfdds', 'mathieu', '18.00', '18.00'),
(15, '2021-10-12', 'Lsddj', 'nicolas', '15.00', '0.00'),
(16, '2021-10-08', 'dlfds', 'parf', '718.00', '718.00'),
(17, '2020-11-23', 'Lsddj', 'tony', '35.00', '0.00'),
(18, '2021-08-23', 'dlfds', 'mattyas', '218.00', '218.00');

--
-- Indexes for dumped tables
--

--
-- Indexes for table `commandes`
--
ALTER TABLE `commandes`
  ADD PRIMARY KEY (`id`);

--
-- AUTO_INCREMENT for dumped tables
--

--
-- AUTO_INCREMENT for table `commandes`
--
ALTER TABLE `commandes`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=19;
COMMIT;

/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS */;
/*!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION */;

    </div>
</template>

<style>
body{
  display: none;
}

.commandes{
  display: block;
}
</style>