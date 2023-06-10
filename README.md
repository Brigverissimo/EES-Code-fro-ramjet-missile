# EES-Code-for-ramjet-missile
Numeric solver to predict missile flight performance for EES.

## About
The available files include a *.ees code and table that predicts the flight profile of a missile. However, it does not include the necessary drag, lift, and atmospheric model subroutines.

**Input variables**:
* Diameter (mm)
* Weight (Kg) -- (propellant + dry mass)
* Length (meters)
* Thrust (N)
* Gamma (radians)
* Drag (at cruise level)

**Output**:
* Range (meters)
* Altitude (meters)
* Drag (N)
* Lift (N)
* Alpha (radians)
* Mach 

## Contents
* ./src contains the program sources.

## How to run?
1. Import to EES
2. Add the input variables
3. Run calculate
4. Check output table

Remark - It is not included the drag, lift and atmosphere model libraries.
