# PRODIGY_CS-02
Pixel Manipulation for image Encryption
# Summary
This code creates a simple image encryption tool using Tkinter, a Python GUI library, and the PIL (Python Imaging Library) module. Here's a summary:
1. **Tkinter Setup**: It sets up a Tkinter window with the title "Image Encryption Tool" and a red background.
2. **Image Selection**: Users can select an image file using a file dialog. Once selected, the image is displayed on a canvas in the window.
3. **Image Encryption**: Users can encrypt the displayed image using a simple XOR encryption algorithm. The encrypted image is then displayed on the canvas.
4. **Image Decryption**: Users can decrypt the encrypted image, reversing the encryption process and displaying the decrypted image.
5. **Image Download**: Users can save the currently displayed (either encrypted or decrypted) image to their file system.
6. **Error Handling**: Error messages are displayed using message boxes to inform the user if any operation fails, such as opening or saving an image.
7. **Resampling**: Images are resized using the Lanczos resampling filter to maintain image quality when displayed on the canvas.
