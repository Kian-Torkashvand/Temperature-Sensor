# Temperature-Sensor
In this project I designed a transistor-based temperature sensor and made a reference chart for it.


We used a BJT transistor, a diode, some resistors, a potentiometer and an LED, which will show us the temperature by the intensity of the LED light. By checking "Chart.Png" file in "Image" directory you will be able to realize the ambient temperature that is related to the LED's Current.
The function of the circuit : with the increase in the transistor's temperature, which is used as a temperature receiver, its base-emitter voltage increases and causes the transistor to turn on. The higher the temperature, the higher the current of the collector of the transistor and the intensity of the LED light. We use a diode and a potentiometer to create a reference voltage for the transistor.
This sensor can be used in ON/OFF circuits and actually you can disconnect or connect a part of the circuit by it (using elements such as Schmidt-trigger). For example, if the temperature increases, this circuit acts like a switch for the fan and turns it on to reduce the ambient temperature; As the temperature drops, the switch opens and the fan turns off again (application : cooling electronic circuits).
