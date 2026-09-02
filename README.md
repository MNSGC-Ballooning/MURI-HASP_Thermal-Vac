# Thermal-Vac

This contains the poster and peer-reviewed conference publications, and code of a low-cost thermal-vacuum chamber that I made for both 1) testing high-altitude ballooning payloads before committing time and resources to high-altitude balloon flights, and 2) for calibrating optical particle detectors to stratospheric conditions. 

The poster is attached below to the readme and the full-text paper is available both here and at its official publication link with more detail than the poster is able to go into.

Thermal-Vac Poster:
<img width="999" height="859" alt="Screenshot 2026-09-02 at 4 24 29 PM" src="https://github.com/user-attachments/assets/c4e30733-594d-49f9-8594-7938419a71fd" />

Thermal-Vac Paper Links: 
- Publication Link: https://www.iastatedigitalpress.com/ahac/article/id/243/
- Local Github Link: 

# Old readme as of May 2019 ("note to the summer team") 
Summer People,
Make sure to transfer everything over to the teensy as quickly
as possible for the best form factor and increased performance, 
as well as future compatibility. As soon as everything is on the
Teensy 3.5/3.6 board and working, construct a simple PCB (Printed
Circuit Board) to mount it on for best performance and ease of 
use. Future iterations of the PCB will expand upon these 
capabilities as needed and the board will continue to evolve,
if necessary. More information on other plans for thermal-vac
expansion are going to be given to Dr. Flaten and also posted
on the team drive.

# Update, looking back as of 2026

The Thermal-Vac was eventually later upgraded from the original Arduino Design (which used an arduino microcontroller soldered wires to a breadboard with the sensors on it)  to a Teensy 3.5/3.6 microcontroller with a custom printed circuit board (with no wires and a much more compact form factor) that all of the sensors and the microcontroller integrated with, utilizing very similar avionics as the Teensy avionics in the Venting system. 
