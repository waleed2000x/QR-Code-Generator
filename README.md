QR-Code-Generator
Overview

QR-Code-Generator is a Node.js backend application designed to swiftly generate QR codes for provided links. It leverages the powerful qr-code library for efficient QR code generation and the intuitive inquirer library for seamless user interaction. For streamlined routing, it integrates the widely-used express framework.
Installation

To install the necessary libraries, execute the following commands:

bash

npm install qr-code inquirer express

    qr-code on npm
    inquirer on npm
    express on npm

Usage

    Clone the repository:

    bash

git clone <repository_url>

Install dependencies:

bash

npm install

Run the application:

bash

    node app.js

    Follow the prompts:
        Upon running the application, you'll be prompted to input the link you wish to convert into a QR code.
        Simply enter the desired link and proceed.

    View the generated QR code:
        The generated QR code will be promptly displayed within your terminal.

Example

bash

$ node app.js
? Enter the link to generate QR code: [Your link here]

Contributing
