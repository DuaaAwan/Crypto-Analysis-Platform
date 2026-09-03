Crypto Analysis Platform

A web based cryptocurrency analysis platform developed using Flask and MySQL. The system provides user authentication and allows users to view and analyze cryptocurrency market data for Bitcoin and Ethereum.

Features

User signup and login system
MySQL database integration
Bitcoin and Ethereum analysis
Real time cryptocurrency data retrieval
OHLC market data
Trading volume analysis
Circulating supply information
Daily return calculation
Volatility calculation
Momentum calculation
Financial signal generation
Interactive web interface

Technologies Used

Python
Flask
MySQL
HTML
CSS
JavaScript
Pandas
CoinGecko API
CoinPaprika API

Database

The application uses MySQL to store user accounts, cryptocurrency information, market data, data sources, and financial signals.

APIs

CoinGecko is used to retrieve cryptocurrency prices, OHLC data, volume, and circulating supply.

CoinPaprika is used as a fallback source for cryptocurrency information and historical data.

How to Run

Install Python and MySQL.

Install the required Python packages:

pip install flask mysql-connector-python requests pandas

Create the required MySQL database and tables.

Update the database configuration in app.py with your MySQL username, password, and database name.

Run the application:

python app.py

Open the provided localhost address in your web browser.

Project Structure

app.py
templates/
style.css
package.json
users.db
SQL session files

Purpose

The project demonstrates practical implementation of Database Management System concepts through a cryptocurrency analysis application. It combines database operations, authentication, API integration, data processing, and web development into one platform.
