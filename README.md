# LVGL-tiny-screen

### Idea

Convert the LVGL Touchscreen project code to a tiny LilyGO TTGO T-Display V1.1 ESP32 - with 1.14 inch TFT Display

This board started off as the first display in my first bluetooth clock project. Since upgrading to the bigger displays this one has been sitting in the drawer doing nothing.
Time to see if it can handle LVGL without having any PSRAM!

## Parts Used

LilyGO TTGO T-Display V1.1 ESP32 - with 1.14 inch TFT Display
A 3D printed custom enclosure I designed for it.

## Features
It needs to tell the time and be able to dim the display so it does not bother me in bed, everything else is an extra.


## Planning
The hardest thing about this project will be making the enclosure. I was lucky to find an enclosure already on Thingyverse so I could grab the dimensions from that.
The board itself has two push buttons and I want to use them to turn the bedroom lights scene on and off and also a spare button for maybe using deep sleep later on.
So I had to modify the model, I printed one out first then worked out what I needed to change and got into Fusion and made the buttons and a better backplate that allows access to the GPIO pins. I plan to power it off the pins not via the USB C on the side.

## Converting the code

I had to make two pages for this screen in the end, the homepage that shows the time and in two bars at the top and the bottom the temperature sensors from around the house and then a page that swapped out those sensors for the weather condition and outside temperature.

## Ideas for the future
I have a spare button on the device and want to add that to be able to turn off the backlight with a press.

## Conclusion
This screen sits right next to my bed and is stuck to the wardrobe, I use it all the time to see the time but also toggle the lights off and on.
The huge big industrial button has been moved to the workshop and reused there.
Very happy with the result of this project, especially because it only cost me the price of two prints which was around 30g of filament.