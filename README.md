# 3D Printed Rhex Bot

This was a project to create a rhex bot, like the one created by Boston Dynamics, but with all the parts being 3D printed on a small printer. It is also designed to be modular, so that you can have 3 legs on each side, or repeat the parts and have 10 or more legs on each side.

## Files

The files that can be seen are the original solidworks files, and the STL files. The solidworks files can be manipulated and altered, the STL files are ready for printing. They are designed to not need support material for the print.

## Machine

This was designed to be printed on a Printrbot Simple Metal, so all the parts fit within a 6" x 6" x 6" cube. It is not necessary to use this particular machine to print any of the parts.

## Materials

Other than printing with any plastic you want, the only other material would be the axels and bolts used to hold the whole thing together. The holes are meant to fit 3/6" bolts with hex nuts on the other end. The same bolts can be used on the axels as well, but be sure to not tighten them down or the gears won't be able to spin properly. By not using any glue to hold any of the parts together, the bot can be taken apart and put together and infinite number of times.

## Motor

The motor that I designed this for is a SVM280 from a hobby store in town. It takes a 1.5-3V power supply and outputs 7800 RPM at load when powered by 3V. The gear boxes designed into this bot are a 1:256 reduction, so that the motors would spin at approximately 30RPM.

## Electronics

I intended to use an Arduino to power and control this little robot. Use any type of fastener you want to attach the Arduino to the cross supports of the bot. You can use zip ties, velcro, double sided tape, hot glue, or small screws.

## Process

After printing all the parts, the difficult part will be keeping track of which part goes where and which direction. It is important that the gears are put in the proper way or else they won't all spin the same speed.

When programming the Arduino for this bot, the walking gait is different from what might be expected. When the front and back legs are down, the center leg should be 180 degrees opposite, up. On the opposing side of the robot, the center leg would be down while the outer legs are up in the air.
