# Fingerprint_Vehicle_Starter

**Overview**

This project demonstrates a fingerprint-based vehicle starter system using an Arduino Uno, a fingerprint sensor, and a buzzer. The system provides enhanced security by requiring a fingerprint match before allowing the vehicle to start.

**Components:**

* Arduino Uno
* Fingerprint sensor (e.g., Adafruit Fingerprint Sensor)
* Buzzer
* Relay module (to control the vehicle starter)
* Jumper wires

**How it works:**

1. The Arduino board reads fingerprints from the sensor and stores them in memory.
2. When the user places their finger on the sensor, the system compares the fingerprint with the stored data.
3. If the fingerprint matches, the system activates the relay, turning on the vehicle's starter.
4. If the fingerprint doesn't match, the buzzer sounds an alert.

**Files:**

* `Arduino Code`: Contains the Arduino code for the project.
* `FIngerprint vehicle Poster.pdf`: Project poster or presentation slides.
* `Fingerprint starter report.pdf`: Project report detailing the implementation and results.

**Usage:**

1. Upload the `Arduino Code` file to the Arduino Uno board.
2. Enroll fingerprints of authorized users.
3. Place your finger on the fingerprint sensor to start the vehicle.

**Additional Notes:**

* For security purposes, consider encrypting stored fingerprint data.
* Implement additional features like multiple user support and access levels.
* Explore using a more secure microcontroller for production-level systems.

**Acknowledgements:**
Adafruit Fingerprint Sensor Library for Arduino: (https://www.arduino.cc/reference/en/libraries/adafruit-fingerprint-sensor-library/)
Arduino Official Website: (https://www.arduino.cc/)
