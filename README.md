# arduinoBLE
This project send signal to the ports D2, D3, D4 and D5 of your arduino Bluno Beetle. I might work on another BLEs but I it is not tested.

## Usage
Upload the .ino file into your arduino.

Add something to the ports and the GRD (ground) to be sure that you can see what it is doing.

Keep your arduino powered(**of course**) lol

Open the serial monitor and the following words will be recognized by the program and turn on or off leds or whatever you want into these pins:


Pin(s) | On (HIGH) | Off (LOW)
--- | --- | ---
`D2` | "turn on" | "turn off"
`D3` | "window on" | "window off"
`D4` | "door on" | "door off"
`D2, D3, D4 and D5` | "all on" | "all off"


## Download Arduino Software
The software to upload the .ino file into your Arduino can be download at [Arduino Website](https://www.arduino.cc/en/Main/Software)

# What is next?
I will change this application to fit my usage and post as much as I can.

Feel free to modify this sample program to support your requirements.

# Window on?
I know I know "window on", "door on" Marcos? Ya ya I know I mean turn the pin for the "window" on(HIGH). Turn the pin for the "door" off(LOW).

Remember that this is not secure so you need to use some combination of characters and numbers and probably with the combination of your UUID to represent something that means nothing and it will set D2 to HIGH or LOW for example:

```
send "KJASHD&^&*SFGDF&" and th app power PIN D2 :)
```

I hope you enjoy


