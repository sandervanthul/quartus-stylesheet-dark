This is a **dark mode** / **dark themed** stylesheet for Quartus Prime Lite. It is based on https://github.com/Alexhuszagh/BreezeStyleSheets.

This stylesheet works with Quartus Prime Lite 23.1.1. I tested 18.1 and 20.1.1 but could not get it to work there.

Note: this stylesheet is far from perfect, if you want to adjust the stylesheet then you can find the documentation here: https://doc.qt.io/qt-6/stylesheet-reference.html

# Setup

To set this up on windows, download the stylesheet and images folder and place them in the same folder somewhere on your drive. Then copy the path to the stylesheet and launch quartus with the following command line argument:

`-stylesheet=/path/to/stylesheet`

As an example, if the path to your stylesheet is: "C:/intelFPGA_lite/stylesheet/quartus_stylesheet_dark.qss", then the command will be:

`-stylesheet="C:/intelFPGA_lite/stylesheet/quartus_stylesheet_dark.qss"`

If you want to launch quartus with a shortcut you can add the command-line argument there too, as shown below:

![quartus_stylesheet_setup](https://github.com/user-attachments/assets/62a569ea-2e34-4ebe-9010-ef76efe02681)
