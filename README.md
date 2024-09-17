# idmaker
dara brooo

CREATE DATABASE school_id_db;

USE school_id_db;

CREATE TABLE students (
    id INT AUTO_INCREMENT PRIMARY KEY,
    first_name VARCHAR(100) NOT NULL,
    last_name VARCHAR(100) NOT NULL,
    student_signature_photo VARCHAR(255),
    id_number VARCHAR(50) NOT NULL UNIQUE,
    address VARCHAR(255) NOT NULL,
    emergency_name VARCHAR(100) NOT NULL,
    tel_no VARCHAR(15) NOT NULL,
    photo VARCHAR(255),
    card_width INT DEFAULT 320,
    card_height INT DEFAULT 448,
    academic_strand VARCHAR(100)
);
