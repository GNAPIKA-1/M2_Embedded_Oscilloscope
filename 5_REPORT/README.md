# REPORT
## Abstract:
## Project Name:
Oscilloscope

## Objective:
The main aim of this project is to design and stimulate a **Oscilloscope** using Atmega328P in SimulIDE through **Atmel Studio 7** as Integrated Development Platform.

## Brief Description about Project:
>An oscilloscope  is a type of electronic test instrument that **graphically displays varying electrical voltages as a two-dimensional plot** of one or more signals as a function of time. The main purposes are to display repetitive or single waveforms on the screen that would otherwise occur too briefly to be perceived by the human eye. The displayed waveform can then be analyzed for properties such as **amplitude, frequency, rise time, time interval, distortion,** and others. Originally, calculation of these values required manually measuring the waveform against the scales built into the screen of the instrument.Modern digital instruments may calculate and display these properties directly.
Oscilloscopes are used in the **sciences, medicine, engineering, automotive and the telecommunications industry**. General-purpose instruments are used for maintenance of electronic equipment and laboratory work. Special-purpose oscilloscopes may be used to analyze an automotive ignition system or to display the waveform of the heartbeat as an electrocardiogram, for instance.
Early high-speed visualisations of electrical voltages were made with an **electro-mechanical oscillograph** . These were superseded by the oscilloscope which used a cathode ray tube (CRT) as its display element, often referred to as Cathode Ray Oscilloscopes - CROs. CROs were later largely superseded by the digital storage oscilloscope(DSO) with thin panel displays, fast analog-to-digital converters and digital signal processors. These can have integrated displays, or can be an electronic module, sometimes known as a digitiser, which feeds into general purpose computer to **process, display and record waveforms**.

## Structure:
![This is an image](https://atmega32-avr.com/wp-content/uploads/2012/11/Oscilloscope.jpg)

## Software Used:
**SimulIDE Software**- SimulIDE is a real-time electronic circuit simulator. It is a simple tool intended for advance learning, and it lets you enjoy the experience as well. SimulIDE is designed to be fast and easy to use, and it works wonders for simple electronics.
## Introduction:
It's a handy little gadget that draws charts automatically using signals you feed into it from the probes hooked up to an electronic circuit.They have **the quantity plotted in the vertical direction (known as the y-axis) and the time period plotted in the horizontal direction (the x-axis)**.When you attach a mini digital oscilloscope probe to an electronic circuit the analog-to-digital converter (ADC) of ***Atmega328p microcontroller*** samples the signal at discrete points with some delay(T) in time and converts the signal's voltage at these points to digital values called sample points.
![This is an image](https://1.bp.blogspot.com/-cekPL-A6Mbc/X3iRj0bZEAI/AAAAAAAABfw/hwsLSN-9m5wJ_j5zw2Va73sHZVRdVouggCLcBGAsYHQ/w1200-h630-p-k-no-nu/board_mode.gif)
The horizontal system's sample clock determines how often the ADC takes a sample.The rate at which the clock "ticks" is called the **sample rate** and is measured in samples per second.**The sample points from the ADC are stored in memory of the microcontroller as waveform points**. More than one sample point may make up one waveform point.Together, the waveform points make up one waveform record. The number of waveform points used to make a waveform record is called the record length. When we press Div +ve switch sampling delay(T) increases so the gap between sample points will increase as a result waveform appeared zoomed out and vice versa. The voltage value of the sample point which is having the maximum analog value out of all the sample points stored in the memory is the Peak voltage of the captured waveform. And the **inverse of the sampling rate will be the Frequency of the waveform**.

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
![This is an image](https://cdn.sparkfun.com/assets/3/c/9/4/1/52f3d691ce395fc6198b4567.png)
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

## HIGH LEVEL REQUIREMENTS:
| Requirements  | Description |
| ------------- | ------------- |
| HLR1  | Microcontroller  |
| HLR2  | LCD Display |
| HLR3  | Oscope |
| HLR4  | SimulIDE  |
| HLR5  | Atmel Studio 7  |
| HLR6  | Microchip Studio  |
| HLR7  | Other Softwares to Implement |

## LOW LEVEL REQUIREMENTS:

| Requirements  | Description |
| ------------- | ------------- |
| LLR1  | ATmega328 |
| LLR2  | ADC with PWM  |
| LLR3 | LCD OR LEDS  |
| LLR4 | AVR GCC compiler  |
| LLR5 | Serial monitor  |
| LLR6 | OpAmp  |
| LLR7 | Sample Rate  |
| LLR8 | Frequency Module |
| LLR9 | Resistors  |
| LLR10 | Capacitors  |
| LLR11 | Fixed Voltage |

## COMPONENTS AND THEIR EXPLANATION:
### ATmega328:
![This is an image](https://www.electronicaembajadores.com/datos/fotos/articulos/grandes/lc/lca1/lca1atmega328.jpg)
ATmega328 is an Advanced Virtual RISC (AVR) microcontroller. It supports 8-bit data processing. ATmega-328 has 32KB internal flash memory. ATmega328 has 1KB Electrically Erasable Programmable Read-Only Memory (EEPROM).
### LCD:
A liquid-crystal display is a flat-panel display or other electronically modulated optical device that uses the light-modulating properties of liquid crystals combined with polarizers.
### Oscope:
oscope comes with some new features:
![This is an image](https://3.bp.blogspot.com/-l8vJcq0qB0g/WoZ5FtqwVSI/AAAAAAAAA-s/LxKSMKLWb1w8YKZ-_S_6kwG74x_dklyeACLcBGAs/s400/oscope0.png)

- Frequency detection.
- Amplitude detection.
- Minimum and Maximum values.
- Auto-scale.
- Scale and Position controls for Horizontal and Vertical.
### Op-Amp:
![This is an image](https://www.allaboutcircuits.com/uploads/articles/op-amp-in-schematics.jpg)
An operational amplifier (op amp) is an analog circuit block that takes a differential voltage input and produces a single-ended voltage output. Op amps usually have three terminals: two high-impedance inputs and a low-impedance output port.
### Resistor, Capacitor, Fixed Voltage and Ground Terminal:
![This is an image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQeHaWMpmcuM2DDrtkcSe755xRmSlDG7uzY6w&usqp=CAU)
A resistor is an electrical component that limits or regulates the flow of electrical current in an electronic circuit.A capacitor is a device that stores electrical energy in an electric field.a fixed voltage type is a variable voltage type that integrates the external resistor.Grounding / Earthing Terminal Blocks are used for grounding and earthing wires to protect people and machinery from intrusion such as electrical or magnetic fields. They play a crucial part in control panel wiring.
### SimulIDE:
![This is an image](https://i.servimg.com/u/f36/20/25/05/52/simuhe11.png)
SimulIDE is a real-time electronic circuit simulator. It is a simple tool intended for advance learning, and it lets you enjoy the experience as well. SimulIDE is designed to be fast and easy to use, and it works wonders for simple electronics.
### Atmel Studio 7:
Atmel® Studio 7 is the integrated development platform (IDP) for developing and debugging SMART ARM®-based and AVR® microcontroller (MCU) applications. Studio 7 supports all AVR and SMART MCUs.
# UML DIAGRAMS:
## STRUCTURAL DIAGRAM
> ### - Structural diagram
 ![This is an image](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b0/Lissajous_figures_on_oscilloscope_%2890_degrees_phase_shift%29.gif/300px-Lissajous_figures_on_oscilloscope_%2890_degrees_phase_shift%29.gif)
> ### - Class diagram
 ![This is an image](https://img.brainkart.com/article/article-Storage-oscilloscope-P2U.jpg)

> ### - State diagram
 ![This is an image](https://electricalacademia.com/wp-content/uploads/2017/01/oscilloscope-block-diagram.gif)
> ###  - Block diagram
 ![This is an image](https://ars.els-cdn.com/content/image/3-s2.0-B9780128008843000095-f09-13-9780128008843.jpg)
## BEHAVIOURAL DIAGRAM
> ### - Case diagram
 ![This is an image](https://bhartikathoiya.files.wordpress.com/2015/03/dso3.jpg)
> ### - Sequence diagram
 ![This is an image](https://electronicspost.com/wp-content/uploads/2016/08/16.png)
### - Flow chart
 ![This is an image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSIs5UYQoA6qDL8XY1lz8qrhSR14FbgeybN9BGy0xhRfxFjKqZRxKAyGrhHla1c_jqYagY&usqp=CAU)


