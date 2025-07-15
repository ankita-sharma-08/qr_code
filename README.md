## QR Code Generator

## Overview
This project is a simple UPI (Unified Payments Interface) QR Code generator that allows users to create a QR code for making payments. The generated QR code can be scanned using any UPI-enabled application to facilitate quick and easy transactions.

## Features
- **User  Input**: Prompts the user for their UPI ID, payee name, and amount to be paid.
- **QR Code Generation**: Utilizes the `qrcode` library to generate a QR code based on the provided UPI payment link.
- **Image Saving**: Saves the generated QR code as an image file (`payment_qr.png`).
- **Display QR Code**: Displays the generated QR code within the notebook.

## Requirements
- Python 3.x
- Libraries:
  - `qrcode`
  - `Pillow` (for image handling)

## Installation
To set up the project, follow these steps:

1. **Clone the repository** (if applicable):
   ```bash
   git clone https://github.com/ankita-sharma-08/qr_code.git
   cd qr_code
   ```

2. **Install required packages**:
   ```bash
   pip install qrcode pillow
   ```

## Usage
1. Run the Jupyter Notebook (`qrcode.ipynb`).
2. When prompted, enter the following details:
   - **UPI ID**: Your UPI ID (e.g., `yourname@bank`)
   - **Payee Name**: The name of the payee
   - **Amount**: The amount to be paid
3. The QR code will be generated and saved as `payment_qr.png`.
4. The generated QR code will be displayed in the notebook.

## Output
The output will be a QR code image that can be scanned for making the payment.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- This project uses the `qrcode` library for generating QR codes.
- Thanks to the developers of UPI for providing a seamless payment interface. 

Feel free to contribute to this project or reach out for any questions!
