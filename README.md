# Smart-Switch
This is a touchless smart switch to maintain disinfected due to Covid-19 outbreak using arduino Uno

Main idea is to develop Hands free switch that operate home appliances by converting hand gesture into commands using gesture sensor.

## Hardware Components Used

**1. Ardunio Uno R3**\
**2. APDS-9960 Gesture Sensor**\
**3. Relay Module**\
**4. OLED Display Module**\
**5. Wires and Connectors**  

   
## Coding for Gesture Controlled switch
### Code for this project has been attached as a separate file to this repository  

To start with install  [Arduino IDE](https://www.arduino.cc/en/software/)  

Once the Ide has installed, now its time install the APDS9960 sensor as we aree working on this sensor in this project.
 
To install the Library Folllow the steps as indicated by the arrow mark below  
 
Go to Select --> Library Manager --> Search APDS9960 --> Install Adafruit APDS9960 

After installing the library, add it to the code and then define the pin number for light and fan control. Next, create a setup function where you can initialise the sensor and set the pin mode output for light and fan control. 

>You can choose anything as an output in this project i have considered Light and fan as an output

Next step is to Then creating a loop function to update the sensor readings and using hand gestures as input to control the pin. Also,  few if conditions are created for specifying the commands based on the type of hand gestures (up, down, left and right).

**Considered Gesture in this project**

Up: Lights ON  

Down: Lights OFF  

Left: Fans ON  

Right: Fans OFF  



## Hardware Connections 

Now upload the code to Arduino and connect the components as described in the circuit diagram. Then connect the AC wire with the common pin of the relay module to control the lights and fans.

![Circuit_Diagram](



