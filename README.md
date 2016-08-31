# IV-Trace
DIY Four Probe IV Characterization for Graphene Studies

Eagle and LabView files for DIY four probe mesaurement device for graphene hall effect devices and transistor.

The files in this repository are for graphene device characterization project for Advanced Project Laboratory course that held 
in  Physics Department of Istanbul Technical University, Istanbul with the facilities of Nanoscale Surface Science Laboratory
with the Supervisor of Prof. Oguzhan Gurlu. The project is suported by Tubitak 1003 project with the grant number of 114F036.

In this project an Arduino is used for measuring currents and a Tektronix made oscillator is for reading voltage across a four probe graphene device. The voltage is supplied via Keithley 2400 sourcemeter. The Sourcemeter is controlled via LabView with specific instrument drivers. Oscilloscope and Arduino Data read via Labview with specific instrument driver for 
oscilloscope and LINX drivers for Arduino. In Labview the Current-Voltage graphs plotted for four separate probes.

In order to read the current flowing through the sample and I/V converter is made with precise shunt resistors. After that
the voltage converted flows through a very precise instrumentation amplifier; Analog Devices AD629 amplifier. The signal than
goes through Arduino and via serial port read with LabView.

For further information you can contact with me; haltugyildirim_at_protonmail.com
