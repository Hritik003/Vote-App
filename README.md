# Decentralized-Voting-System-Using-Ethereum-Blockchain

#### The Decentralized Voting System using Ethereum Blockchain is a secure and transparent solution for conducting elections. Leveraging Ethereum's blockchain technology, this system ensures tamper-proof voting records, enabling users to cast their votes remotely while maintaining anonymity and preventing fraud. Explore this innovative project for trustworthy and decentralized voting processes.

## Features
-  Implements JWT for secure voter authentication and authorization.
-  Utilizes Ethereum blockchain for tamper-proof and transparent voting records.
-  Removes the need for intermediaries, ensuring a trustless voting process.
-  Admin panel to manage candidates, set voting dates, and monitor results.
-  Intuitive UI for voters to cast votes and view candidate information.

## Requirements
- Node.js (version – 18.14.0)
- Metamask
- Python (version – 3.9)
- FastAPI
- MySQL Database (port – 3306)

## Screenshots

![Login Page](https://github.com/Hritik003/Vote-App/blob/main/public/login%20ss.png)

![Admin Page](https://github.com/Hritik003/Vote-App/blob/main/public/admin%20ss.png)

![Voter Page](https://github.com/Hritik003/Vote-App/blob/main/public/index%20ss.png)

## SQL Database Query



1. Open MySQL and create database named <b>voter_db</b>.

           CREATE DATABASE voter_db;
           USE voter_db;

2. In the database created, create new table named <b>voters</b> in the given format and add some values.

           CREATE TABLE voters_table (
                voter_id VARCHAR(60) PRIMARY KEY NOT NULL,
                role ENUM('admin', 'user') NOT NULL,
                password VARCHAR(255) NOT NULL
           );
 

