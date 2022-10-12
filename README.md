# QR-code-Scanner
This project provides a clear concept about the working of QR and Barcode scanners.
It serves as both QR code scanner and Barcode scanner.
A QR code simply consists of a black square and dots (yeah). That, essentially, is what a QR code looks like. The pattern on QR codes can be alphanumeric, numeric or binary.
A barcode is “A machine-readable code in the form of numbers and a pattern of parallel lines of varying widths, printed on and identifying a product.”
The rapid increment of daily usage of scanners made us think about building our own scanner and thus this project.
QR and Barcode are a big commercial tool and people need to know more about it.
Project includes work in the Python programming language completely.
Libraries used in this python project are: PILLOW, OPENCV, PYZBAR.
After the addition of the libraries to the code, it is followed by the decoding function.
The decoding funcntion is to recognize and decode the shown QR/Barcode to the camera, then adding the stored information as a text on the code and then finally sending the information as a text document. 
The main function is the heart of the project. This funtion will open the system camera and call the decoding function to complete the task. 
And done. After executing the funtions properly we will get our desired output as a QR/Barcode scanner. 
