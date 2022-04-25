# OSCILLOSCOPE

## Introduction:
It's a handy little gadget that draws charts automatically using signals you feed into it from the probes hooked up to an electronic circuit.They have **the quantity plotted in the vertical direction (known as the y-axis) and the time period plotted in the horizontal direction (the x-axis)**.When you attach a mini digital oscilloscope probe to an electronic circuit the analog-to-digital converter (ADC) of ***Atmega328p microcontroller*** samples the signal at discrete points with some delay(T) in time and converts the signal's voltage at these points to digital values called sample points.The horizontal system's sample clock determines how often the ADC takes a sample.The rate at which the clock "ticks" is called the **sample rate** and is measured in samples per second.**The sample points from the ADC are stored in memory of the microcontroller as waveform points**. More than one sample point may make up one waveform point.Together, the waveform points make up one waveform record. The number of waveform points used to make a waveform record is called the record length. When we press Div +ve switch sampling delay(T) increases so the gap between sample points will increase as a result waveform appeared zoomed out and vice versa. The voltage value of the sample point which is having the maximum analog value out of all the sample points stored in the memory is the Peak voltage of the captured waveform. And the **inverse of the sampling rate will be the Frequency of the waveform**.

## Objective:
Based on the information that the oscilloscope captures about the signal, modern digital oscilloscopes ofter two other important functions: 

1. The **automatic measurement of various parameters of the signal**, like its frequency, peak-to-peak voltage, duty cycle and rise time, and
2. For signals that encode information, to decode that information and display it on the screen. For example, if the oscilloscope has captured the waveform that **encodes serial information, we can set it so that this information is extracted** from the waveform and displayed on the screen.

  The basic **objectives** are as follows;
  - Plot signal waveform
  - Capture a waveform
  - Trigger control
  - Measurements
  - Decoding

## Benefits:
- BuildS a system that can measure the **voltage** and give response automatically in **short time**.
- A **control system** that is able to **monitor and manage** all parameters that are being controlled by specified operations efficiently.
- Keep a **track** of their responses.
- It is simple and **user friendly** application.
- The system is **cost effective**.

## 4W's and 1H:
### Who:
- **Engineers** use this oscilloscope to measure electrical phenomena and quickly test, verify, and debug their circuit designs.
- Oscilloscopes are used in the sciences, medicine, engineering, automotive and the telecommunications **industry**.
### What:
- The implementation of this project helps in measuring voltage by sample rate and varying frequency.
- The measuring device that allows to see the changes in the **electrical voltage depending on time** is called an oscilloscope. It is commonly known that a voltmeter is used to make such a measurement under normal conditions.
### Where:
- Used for maintenance of electronic equipment and laboratory work. Special-purpose oscilloscopes may be used to analyze an automotive ignition system or to display the waveform of the heartbeat as an electrocardiogram, for instance.
### When:
-  You can use them to debug the analog outputs of sensors.
-  Catching simple errors by measuring the period of the flashes.
-  Especially proficient at debugging PWM signals'
-  To debug communications busses.
-  When you want to get the exact formula for a trigonometric waveform through collecting data.
### How:
- Set the oscilloscope to display channel 1.
- Set the vertical volts/division scale and position controls to mid–range positions.
- Turn off the variable volts/division.
- Turn off all magnification settings.
- Set the channel 1 input coupling to DC.
- Set the trigger mode to auto.
- Set the trigger source to channel 1.
- Turn trigger holdoff to minimum or off.
- Set the horizontal time/division and position controls to mid-range positions.
- Adjust channel 1 volts/division such that the signal occupies as much of the 10 vertical divisions as possible without clipping or signal distortion.

## SWOT Analysis:
### Strengths:
- Easy adoptable system.
- We can adjust voltage accordingly in a easier way.
- Flexible Approach
- It's a cost-effective and a robust system.
### Weaknesses:
- **Cost** many times more than other types of electronic measuring instruments, such as multimeters, they are also very sophisticated, and tend to be costly to repair if **damaged**. 
### Opportunities:
- Move way beyond the traditional FFT by providing much more elegant and advanced frequency domain analysis with some scopes even providing an integrated spectrum analyze for example the **Mixed Domain Oscilloscope**.
- To make more accurate measurements, especially on low-voltage signals.
- More **miniaturization** and improved performance in modular-based scopes.
### Threats:
- **Inadequate air flow** can cause excessive operating temperatures, which can lead to oscilloscope failure.


















































