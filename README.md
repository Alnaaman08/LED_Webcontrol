Hier ist ein einfaches **README**-Beispiel für dein GitHub-Projekt:

---

# Raspberry Pi LED Control via Flask Web Interface

This project demonstrates how to control an LED connected to a Raspberry Pi through a web interface using Flask. The project includes Python code for the Flask server, HTML for the web interface, and CSS for styling.

## Features
- Turn the LED on or off via a simple web interface.
- Displays a message showing when the LED was last turned on.

## Requirements

### Hardware:
- Raspberry Pi
- LED
- Resistor
- Jumper wires
- Breadboard

### Software:
- Python 3
- Flask
- RPi.GPIO library

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/raspberry-pi-led-control.git
   cd raspberry-pi-led-control
   ```

2. **Install Required Python Libraries**:
   Make sure Flask and RPi.GPIO are installed:
   ```bash
   pip install Flask RPi.GPIO
   ```

3. **Wiring the LED**:
   - Connect the LED to GPIO pin 5 of the Raspberry Pi (physical pin 29).
   - Don't forget to use a resistor in series with the LED to prevent damage.

4. **Run the Application**:
   ```bash
   python app.py
   ```

5. **Access the Web Interface**:
   Open a web browser and go to `http://<raspberry-pi-ip>:5000`.

## File Descriptions

### Python (`app.py`)
This file contains the Flask server code that:
- Manages the web routes.
- Controls the GPIO pin to turn the LED on or off based on the form data submitted via the web interface.

### HTML (`templates/index.html`)
This is the main web interface with two buttons: one to turn the LED on and another to turn it off.

### CSS (`static/styles.css`)
This file contains the styles for the web interface, including button colors and hover effects.

## Example Usage

Once the application is running, you'll be able to:
- Navigate to the web page and click the "On" button to turn the LED on.
- Click the "Off" button to turn the LED off.
- The web interface will display a message indicating the last time the LED was turned on.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

Das README deckt alle wichtigen Informationen ab: was das Projekt macht, wie man es einrichtet und welche Dateien enthalten sind.
