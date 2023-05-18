# Getting Started with Arduino Nano 33 BLE Sense

## Introduction
The Arduino Nano 33 BLE Sense is a compact and versatile development board that combines the power of the nRF52840 microcontroller with Bluetooth Low Energy (BLE) capabilities and a wide range of onboard sensors. It is an excellent choice for projects involving IoT, wearables, and sensor-based applications. In this tutorial, we will explore the basics of the Arduino Nano 33 BLE Sense and demonstrate a simple code to blink the onboard LED.

## Prerequisites
To follow along with this tutorial, you will need the following:

1. Arduino Nano 33 BLE Sense board.
2. Arduino IDE (Integrated Development Environment) installed on your computer. You can download it from the official Arduino website: [https://www.arduino.cc/en/software](https://www.arduino.cc/en/software).
3. A USB cable to connect the Arduino board to your computer.

## Step 1: Setting Up the Arduino IDE
Before we start working with the Arduino Nano 33 BLE Sense, let's set up the Arduino IDE:

1. Download and install the Arduino IDE if you haven't already.
2. Launch the Arduino IDE.
3. Go to **Tools > Board** and select "Arduino Nano 33 BLE" from the list of available boards.
4. Go to **Tools > Port** and choose the appropriate port that corresponds to your Arduino Nano 33 BLE Sense board.

## Step 2: Blinking the Onboard LED
Now that we have the Arduino IDE configured, let's write a simple code to blink the onboard LED of the Arduino Nano 33 BLE Sense:

```cpp
// Pin number for the onboard LED
const int ledPin = LED_BUILTIN;

void setup() {
  // Initialize the LED pin as an output
  pinMode(ledPin, OUTPUT);
}

void loop() {
  // Turn on the LED
  digitalWrite(ledPin, HIGH);
  
  // Wait for 1 second
  delay(1000);
  
  // Turn off the LED
  digitalWrite(ledPin, LOW);
  
  // Wait for 1 second
  delay(1000);
}
```

## Step 3: Uploading the Code
Now, let's upload the code to the Arduino Nano 33 BLE Sense:

1. Connect your Arduino Nano 33 BLE Sense board to your computer using the USB cable.
2. In the Arduino IDE, click on the **Upload** button (the right arrow icon) to compile and upload the code to the board.
3. Wait for the upload process to complete. You should see the LED blinking at a 1-second interval.

Congratulations! You have successfully written a simple code to blink the onboard LED of the Arduino Nano 33 BLE Sense.
<img src="https://th.bing.com/th/id/OIP.2abl8jRHP6VxDjOWVsk24gHaFj?pid=ImgDet&rs=1">

## Conclusion
In this tutorial, we covered the basics of the Arduino Nano 33 BLE Sense board and demonstrated how to blink the onboard LED using a simple code. This is just the beginning, and the Arduino Nano 33 BLE Sense offers a wide range of capabilities with its onboard sensors and BLE connectivity. Feel free to explore the official Arduino documentation and libraries to discover more features and possibilities for your projects.

Happy tinkering!
