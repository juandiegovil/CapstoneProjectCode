This is the program used for our capstone project. It involved a system with multiple energy inputs (solar, battery power, generator, utility power) and a load that needs to be satisfied. Our goal was to have a PLC control which of these energy sources is used, depending on how much load we have, the level of our batteries and the cost of utility power at that time.

Out program takes in these variables (along with others) and determines what state our system should be on. Different states includes things like the batteries being discharging, charging or idle; the generator being ON or OFF: or how much power we want to be provided by utilities.

We succesfully developed this code that will make all these decision automatically and communicate with the inverter on what to do. An HMI screen was also developed to display live the values of every important variable in our system and the overall state of the system.

Schneider Electric Program used. Codesys programming language.