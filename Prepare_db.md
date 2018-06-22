CREATE DATABASE ecom;
USE ecom;

//Products table
CREATE TABLE IF NOT EXISTS item (
        id INTEGER AUTO_INCREMENT PRIMARY KEY,
        title VARCHAR(50) NOT NULL,
        description VARCHAR(1000) NOT NULL,
        price INTEGER NOT NULL,
        img VARCHAR(10000) NOT NULL
    )

//Cart table
CREATE TABLE IF NOT EXISTS cart (
        id INTEGER AUTO_INCREMENT PRIMARY KEY,
        title VARCHAR(50) NOT NULL,
        description VARCHAR(1000) NOT NULL,
        price INTEGER NOT NULL,
        img VARCHAR(10000) NOT NULL,
        quantity INTEGER NOT NULL
    )
