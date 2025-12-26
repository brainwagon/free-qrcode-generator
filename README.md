# Free QR Code Generator

A lightweight, self-contained, single-file QR code generator that runs entirely in your browser.

![Example Image](example.png)

## Features

- **Single File**: Everything is contained within `index.html`. No complex setup or server-side requirements.
- **Multiple Formats**: Generate and download QR codes in:
  - **PNG**: High-resolution image.
  - **SVG**: Scalable vector graphics.
  - **DXF**: CAD-compatible format for laser cutting or CNC machining.
- **Supported Content Types**:
  - Plain Text & URLs
  - Wi-Fi Network credentials
  - Contact Cards (vCard)
  - Email (with subject and body)
  - Phone Numbers
  - SMS Messages
- **Customizable Styles**: Choose between Square, Rounded, Dots, or Classy styles.
- **Privacy Focused**: No data is sent to any server. All processing happens locally in your browser. No information about the users or the content of the QR codes is gathered.

## Usage

Simply open `index.html` in any modern web browser.

1. Select the **Content Type**.
2. Fill in the required details.
3. Choose a **Style**.
4. Click **Generate QR Code**.
5. Download your QR code in the desired format (PNG, SVG, or DXF).

## Self-Hosting / Run Locally

Since this is a client-side only application, you can easily host it yourself or run it locally.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/brainwagon/free-qrcode-generator.git
   cd free-qrcode-generator
   ```

2. **Start a local server:**
   If you have Python installed, you can use the built-in HTTP server:
   ```bash
   python3 -m http.server
   ```

3. **Access the application:**
   Open your browser and navigate to:
   `http://localhost:8000`

## Credits

This project was developed entirely using **Google's Gemini CLI**.

## Technologies Used

- [qr-code-styling](https://github.com/kozakdenys/qr-code-styling) for UI, preview, and PNG/SVG generation.
- [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator) for raw matrix calculation used in DXF export.
- [Tailwind CSS](https://tailwindcss.com/) for styling.

## License

Open source and free to use.
