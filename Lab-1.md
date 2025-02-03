# Lab 1: Knowing Your Instruments

## Authors: Ashlyn Lippert and Seth Daniel

## Date: February 2nd, 2025

## Introduction:
   This lab introduces basic electronic test equipment, including a Digital Multimeter (DMM), an oscilloscope (O-scope), a Function Generator (F.G.), and a Direct Current Power Supply (DCPS). The goal was to understand how each tool works, practice obtaining accurate measurements, and obtain hands-on practice. During the lab, different electronic signals were created and measured using the equipment.
   Additionally, this lab provided instruction on how to use GitHub to write lab reports and the basics for navigating and understanding the GitHub interface.

## Materials:
1. Four different resistors (any value)
2. Four different capacitors (any value, one must be catalytic)
3. 10KΩ Resistor

## Assembly Methods:
1. **Resistor Measurement Setup:**
   
   Identified four different resistors and recorded their color codes to determine expected values, then we used a Fluke 87 V DMM to measure the actual resistance by connecting the alligator clips to each resistor's leads.
   We then compared the measured values with expected values and checked if they were within tolerance. We also measured the resistance of the DMM cables and subtracted it from the resistor measurements to improve our measurement accuracy.

3. **Capacitor Measurement Setup:**
   
   We started by identifing four different capacitors and recorded their expected capacitance values using the Fluke 87 V DMM in capacitance mode to measure each capacitor. For the electrolytic capacitor, we made sure to ensure proper orientation. After identifying and measuring the capacitance of each capacitor, we compared the measured values with expected values and noted any discrepancies.

5. **DC Power Supply Configuration:**
   
   To configure the power source, we first located the DC Power Supply (DCPS) and ensured it was plugged in and powered on. To familiarize ourselves with the equipment, we identified the settings, knobs, and display indicators, then adjusted the voltage output to +1.5V, +7.0V, and +12.0V.
   Using the DMM, we measured each voltage output and compared the readings with the DCPS display. Additionally, we measured the fixed 3.3V, 5.0V, and 12V outputs to verify their accuracy.

7. **Function Generator and Oscilloscope Setup:**
   
   We began by connecting a 10KΩ resistor to the output of the Function Generator (FG), then set the FG to produce a 2kHz sine wave at maximum amplitude. Using the oscilloscope, we observed the waveform and measured amplitude and frequency using four different methods:
     1. Counting squares on the oscilloscope screen.
     2. Using the moveable cursors on the oscilloscope.
     3. Using the measurement features of the oscilloscope.
     4. Measuring with the Fluke DMM.
   
   Additionally, we adjusted frequency and amplitude of the generated wave and observed changes on both the oscilloscope and DMM and recorded our findings.

## Test Equipment:
1. Fluke 87 V DMM
2. Oscilloscope Tektronix TS2012
3. Function Generator
4. DC Power Supply
5. Computer with internet access
   
## Test Procedures:

1. **Resistor Measurement**
   - Measured resistance using the DMM and compared with expected values.
   - Recorded results in a table.

2. **Capacitor Measurement**
   - Measured capacitance using the DMM.
   - Observed if polarity affected electrolytic capacitor readings.

3. **Power Supply Check**
   - Set different voltage levels and measured them with the DMM.
   - Compared results with expected values.

4. **Function Generator Output**
   - Measured output using different oscilloscope methods and the DMM.
   - Compared values to Function Generator settings.
   - Changed frequency and amplitude to observe oscilloscope and DMM responses.

## Test Results:
| Resistance of DMM Cables (Ohms) |
|---------------------------------|
|          1.2 Ohms               |

**Resistor Values:**

| Resistor # | Band 1 | Band 2 | Band 3 | Band 4 | Expected Resistance (Ohms) | Tolerance | Max Value (Ohms) | Min Value (Ohms) | Measured Resistance (Ohms) | Measured Resistance - Resistance of Cables (Ohms) |
|------------|--------|--------|--------|--------|--------------------------|-----------|----------------|----------------|----------------------|---------------------------------|
| 1          | Yellow | Purple | Green  | Gold   | 4700000                  | 5%        | 4935000        | 4465000        | 4720000              | 4719998.8                         |
| 2          | Brown  | Green  | Black  | Gold   | 15                        | 5%        | 15.75          | 14.25          | 15.7                  | 14.5                               |
| 3          | Brown  | Gray   | Brown  | Gold   | 180                       | 5%        | 189            | 171            | 187                   | 185.8                              |
| 4          | Gray   | Red    | Red    | Gold   | 8200                      | 5%        | 8610           | 7790           | 8230                  | 8228.8                             |

**Capacitor Values:

# Laboratory Report for Lab 1 of BAE305 Spring 2024

## Lab 1 – Well-Equipped

### Summary
The goal of this lab is to learn how to use several electronic test equipment and to use GitHub to submit our reports. We measured several resistors, capacitors, and operated the DMM, Oscilloscope, and Function Generator. Finally, we created a repository in GitHub to store the lab reports. This report is stored in this repository as a wiki.

## Materials
- 4 Resistors
- 4 Capacitors

## Assembly Procedures
1. **Resistor Measurement Setup:**
   - Identified four different resistors and recorded their color codes to determine expected values.
   - Used a Fluke 87 V DMM to measure the actual resistance by connecting the alligator clips to each resistor's leads.
   - Compared the measured values with expected values and checked if they were within tolerance.
   - Measured the resistance of the DMM cables and subtracted it from the resistor measurements to improve accuracy.

2. **Capacitor Measurement Setup:**
   - Identified four different capacitors and recorded their expected capacitance values.
   - Used the Fluke 87 V DMM in capacitance mode to measure each capacitor.
   - Ensured proper orientation for electrolytic capacitors and observed any polarity effects.
   - Compared measured values with expected values and noted any discrepancies.

3. **DC Power Supply Configuration:**
   - Located the DC Power Supply (DCPS) and ensured it was plugged in and powered on.
   - Identified the settings, knobs, and display indicators.
   - Adjusted the voltage output to +1.5V, +7.0V, and +12.0V.
   - Used the DMM to measure each voltage output and compared the readings with the DCPS display.
   - Also measured the fixed 3.3V, 5.0V, and 12V outputs to verify their accuracy.

4. **Function Generator and Oscilloscope Setup:**
   - Connected a 10KΩ resistor to the output of the Function Generator (FG).
   - Set the FG to produce a 2kHz sine wave at maximum amplitude.
   - Used an oscilloscope to observe the waveform.
   - Measured amplitude and frequency using four different methods:
     1. Counting squares on the oscilloscope screen.
     2. Using the moveable cursors on the oscilloscope.
     3. Using the measurement features of the oscilloscope.
     4. Measuring with the Fluke DMM.
   - Adjusted frequency and amplitude of the generated wave and observed changes on both the oscilloscope and DMM.

## Test Equipment
- **Fluke 87 V DMM**
- **Oscilloscope Tektronix TS2012**
- **Function Generator**
- **DC Power Supply**

## Test Procedures
1. **Resistor Measurement**
   - Measured resistance using the DMM and compared with expected values.
   - Recorded results in a table.

2. **Capacitor Measurement**
   - Measured capacitance using the DMM.
   - Observed if polarity affected electrolytic capacitor readings.

3. **Power Supply Check**
   - Set different voltage levels and measured them with the DMM.
   - Compared results with expected values.

4. **Function Generator Output**
   - Measured output using different oscilloscope methods and the DMM.
   - Compared values to Function Generator settings.
   - Changed frequency and amplitude to observe oscilloscope and DMM responses.

## Test Results
### Resistor Values Table
| Resistor # | Band 1 | Band 2 | Band 3 | Band 4 | Expected Resistance (Ohms) | Tolerance | Max Value (Ohms) | Min Value (Ohms) | Measured Resistance (Ohms) | Measured - Resistance of Cables (Ohms) |
|------------|--------|--------|--------|--------|--------------------------|-----------|----------------|----------------|----------------------|---------------------------------|
| 1          | Yellow | Purple | Green  | Gold   | 4700000                  | 5%        | 4935000        | 4465000        | 4720000              | 4719998.8                         |
| 2          | Brown  | Green  | Black  | Gold   | 15                        | 5%        | 15.75          | 14.25          | 15.7                  | 14.5                               |
| 3          | Brown  | Gray   | Brown  | Gold   | 180                       | 5%        | 189            | 171            | 187                   | 185.8                              |
| 4          | Gray   | Red    | Red    | Gold   | 8200                      | 5%        | 8610           | 7790           | 8230                  | 8228.8                             |

### Capacitor Values Table
| Capacitor # | Capacitor Type | Expected Capacitance (F) | Tolerance | Max Expected Capacitance (F) | Min Expected Capacitance (F) | Measured Capacitance (F) |
|-------------|----------------|--------------------------|-----------|------------------------------|-------------------------------|---------------------------|
| 1           | Electrolytic   | 0.00047                  | 20%       | 0.000564                        | 0.000376                     | 0.00053                  |
| 2           | Ceramic        | 0.000001                 | 5%        | 0.00000105                      | 0.00000095                    | 0.00000114               |
| 3           | Ceramic        | 2.2E-11                  | 5%        | 2.31E-11                        | 2.09E-11                      | 3E-10                    |
| 4           | Ceramic        | 0.000000001              | 10%       | 1.1E-09                         | 9E-10                         | 1.34E-09                 |


**Polarity of Electrolytic Capacitor:**
| Polarity |
|----------|
| 528      |

**Power Supply Voltage Verification:**
| Current from 


## Results:


## Discussion:


## Conclusion:
