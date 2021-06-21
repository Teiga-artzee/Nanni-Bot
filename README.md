# Nanni-Bot
Java Program worked in NetBeans. Finch Robot Program.
Used as prototype for a robot that could potentially watch children/pets as well as interact with them.

--------------------------------------------------------------------------
The xml file is used in Snap! enviorment to prototype the program before use
in Java

--------------------------------------------------------------------------
main, movemnet, temperature require the full FinchBeans file found
on the Finch Website to be used in NetBeans.

---------------------------------------------------------------------------
The movement class handles the IR sensors and other motion sensors
to detect how the robot should respond to the enviorment. Using
a fixed heirachy system, the robot remains as autonomous as possible
with servo based behavior.
The escape behavior acts as a ballistic behavior to escape from corners.

--------------------------------------------------------------------------
The temperature class checks the temperature of the area as a saftey feature
it sends this information back to main class.

-----------------------------------------------------------------------------
Within the main class, it handles the program functionality. It checks for
the temperature of the area, and if it is deemed unsafe, it will stop all
other functions and alert the user.

-----------------------------------------------------------------------------
