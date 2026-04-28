A purely discrete approach to making an AOA Stall Warning System. This is a 
little project I made for my Electrical course, which constrained us to only 
discrete components and no Programmable ICs or anything. ༼ つ ◕_◕ ༽つ

# Circuit Overview
- Potentiometer → AoA sensor
- RC filter (10kΩ + 10µF) → signal smoothing
- Zener + 2N3904 NPN → threshold switching at specific voltage
- Red LED + piezo buzzer → stall alert
- Green LED → always-on power indicator
