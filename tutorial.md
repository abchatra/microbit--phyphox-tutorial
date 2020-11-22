# Micro:Bit & Phyphox ☀️⚡

## Introduction @unplugged

Lerne wie man den Micro:Bit mit Phyphox via Bluetooth verknüpft und die Daten einer Photovoltaikzelle analysiert.


![Heart shape in the LEDs](/static/mb/projects/flashing-heart/sim.gif)

## Step 1 @fullscreen

Füge den Block ``||advanced:extension||`` 



## Step 2

Place another ``||basic:show leds||`` block. You can leave it blank and draw what you want.

```blocks
basic.forever(function() {
    basic.showLeds(`
        . # . # .
        # # # # #
        # # # # #
        . # # # .
        . . # . .`);
    basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        . . . . .`);
})
```

## Step 3

Look at the virtual @boardname@, you should see the heart and your drawing blink on the screen.

## Step 4

Wenn du den @boardname@ verbunden hast, klicke auf ``|Download|`` um den Code auf deinen @boardname@ zu übertragen!