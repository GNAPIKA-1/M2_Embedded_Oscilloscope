# OSCILLOSCOPE

## Introduction:
It's a handy little gadget that draws charts automatically using signals you feed into it from the probes hooked up to an electronic circuit.They have the quantity plotted in the vertical direction (known as the y-axis) and the time period plotted in the horizontal direction (the x-axis).
When you attach a mini digital oscilloscope probe to an electronic circuit the analog-to-digital converter (ADC) of Atmega328p microcontroller samples the signal at discrete points with some delay(T) in time and converts the signal's voltage at these points to digital values called sample points.
The horizontal system's sample clock determines how often the ADC takes a sample.The rate at which the clock "ticks" is called the sample rate and is measured in samples per second.The sample points from the ADC are stored in memory of the microcontroller as waveform points. More than one sample point may make up one waveform point.Together, the waveform points make up one waveform record. The number of waveform points used to make a waveform record is called the record length. When we press Div +ve switch sampling delay(T) increases so the gap between sample points will increase as a result waveform appeared zoomed out and vice versa. The voltage value of the sample point which is having the maximum analog value out of all the sample points stored in the memory is the Peak voltage of the captured waveform. And the inverse of the sampling rate will be the Frequency of the waveform.

## Objective:
Based on the information that the oscilloscope captures about the signal, modern digital oscilloscopes ofter two other important functions: 

1. The automatic measurement of various parameters of the signal, like its frequency, peak-to-peak voltage, duty cycle and rise time, and
2. For signals that encode information, to decode that information and display it on the screen. For example, if the oscilloscope has captured the waveform that encodes serial UART information, we can set it so that this information is extracted from the waveform and displayed on the screen.

  The basic objectives are as follows;
  - Plot signal waveform
  - Capture a waveform
  - Trigger control
  - Measurements
  - Decoding
