SENSg-V3.5
==========
<h4>National Science Experiment: SENsg,  Large-scale Internet of Things Sensor Deployment in SUTD, Singapore</h4>

#Overview
V3.5 of SENSg is developed during my exchange period in SUTD, Singapore. Thanks to Professor Wilhelm Erik's kind guidance.

#Change Log
* Add P-channel MOSFET as the power switch for camera. MOSFET is controlled by MCU pin1, which is also the LDR sensor's I/O pin. 
* With a pull-up resistor, the camera won't on unless the pin1 gives a low voltage. Also the camera's VCC input is changed to MOSFET's source.
* All changes were tested.
