# DIY-Multislope-ADC
This project is a WIP Multislope ADC that is inspired by NNNI's Multislope ADC architecture, in which the ADC constantly runs as long as a clock is present. However, I changed a few things. Instead of using a D flip flop, I'm using amplifiers and logic gates to trigger the run up and down slopes.
To put it simply, when an input voltage is applied for a certain amount of time (Note: while I was writing this i realized I need to make it so that the rundown does not trigger while the runup is on, thanks github for making me write things out), a series of amplifiers each with different gains trigger different runup and down slopes, so no code is required to get a high accuracy.
Sorry if the schematic is not very organized, *this is a WIP*
