# GitHub_QR_Code

GitHub Profile QR Code Generator

This Python script generates a QR code for a GitHub profile. Here's a breakdown of what each part of the code does:

1.Importing Libraries: The script starts by importing the necessary libraries. `qrcode` is used to generate the QR code, 
and `PIL` (Python Imaging Library) is used to work with images.

2.Setting up QR Code Parameters: The `qrcode.QRCode()` function is called to create a QR code object. Parameters like version, 
error correction level, box size, and border are set. In this case, version 1 is used with high error correction, a box size of 20 pixels, and a border of 4 modules.

3.Adding Data to the QR Code: The `.add_data()` method is used to add the GitHub profile URL (`"https://github.com/Ranadheerrrr"`) to the QR code.

4.Generating the QR Code Image: The `.make()` method is called to generate the QR code image. The `fit=True` parameter ensures 
that the QR code adjusts its size according to the data.

5.Customizing the QR Code: The `.make_image()` method is used to create an image of the QR code with custom fill and background colors. 
In this case, the QR code is filled with blue color (`fill_color="blue"`) and has a white background (`back_color="white"`).

6.Saving the QR Code Image: Finally, the `.save()` method is used to save the generated QR code image as "Github_QR.png" in the current directory.

Overall, this script automates the process of generating a QR code for a GitHub profile URL and allows for customization of the QR code's appearance. 
It can be useful for sharing GitHub profiles in a visually appealing and convenient way.
