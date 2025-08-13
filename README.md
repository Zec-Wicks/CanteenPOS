# CanteenPOS 
CanteenPOS is a point of sale (POS) system designed specifically for canteens. This application allows users to efficiently manage sales transactions through barcode scanning.

## Features
- **Barcode Scanning**: Quickly scan product barcodes to add items to the cart.
- **Cart Management**: View and manage selected items in the cart in real-time.
- **ID Scanning**: Complete sales by scanning customer ID barcodes.
- **Sales Recording**: Automatically record sales transactions for tracking and reporting.
- **Email Billing**: Generate and send detailed bills to customers via email at the end of each billing cycle.

## Technologies Used
- **SvelteKit**: A modern framework for building web applications.
- **Node.js**: For backend services and handling sales records.
- **Nodemailer**: For sending emails with bills.
- **SQLite**: for storing product, user, and sales data.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/canteenpos.git
    cd canteenpos
    ```
2. Install dependencies:
    ```bash
    npm install
    ```
3. Start the development server:
    ```bash
    npm run dev
    ```
4. Open your browser and navigate to `http://localhost:3000`.

## Usage
Scan a product's barcode to add it to the cart.
Continue scanning additional products as needed.
Scan the customer ID barcode to complete the sale.
The system will record the sale and send an email with the bill.

## Important Note

This project is not intended to be run on the public internet. It is designed for use in controlled environments, such as canteens or private settings, to ensure data security and privacy. Please take appropriate measures to secure the application and its data if deployed in any environment.


## License
This project is licensed under the GNU GPLv3 License. See the [LICENSE](./LICENSE) file for details.