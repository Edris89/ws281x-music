# ws281x-music
This Github page is for my upcoming ws281x custom music board for pc.

Components that are needed.

# Needed:

My custom plug & play device/board.
A WS281x RGB Ledstrip (you can buy this very cheap from aliexpress, mayby I will have 2 options, 1 with rgb ledstrip and one without)

I have to be clear about this. You need my custom board because the WS281x RGB Ledstrips draw more power if more leds are used.
The WS281x draws 20 mA per led thats 60 mA because this is a rgb led.
That means if someone has 60 rgb leds on the ledstrip it draws 60 mA * 60 = 3600 mA
That's a lot for a USB port.
So to tackle this problem I don't wan't people to buy a 5V power supply.So it would be nice if the board has another USB cable that's connected with something like a phone charger.

This way people could use or buy a phone charger plug the power usb cable into it and plug the data usb cable into their computer.
The board would also have 2 connectors for 2 rgb ws281x ledstrips.

# User Case 1: Windows

Step 1: Connect the power USB Cable into a phone charger.
Step 2: Connect the data USB cable into the PC
Step 3: Connect the WS281x RGB Ledstrip
Step 4: The user installs a program provided by the github page.
Step 5: The user chooses the com port that my custom board is connected to.
Step 6: The user chooses the sound output device.

# User Case 2: Mac (help is needed)
