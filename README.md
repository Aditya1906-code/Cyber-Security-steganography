# Cyber-Security-steganography

## **Overview**
This project demonstrates a simple steganography technique to hide and retrieve secret messages inside an image using OpenCV. The message is embedded pixel by pixel and can only be decrypted using the correct passcode.

## **Features**
✅ Hide a secret message inside an image  
✅ Retrieve the hidden message with a passcode  
✅ Uses OpenCV for image processing  
✅ Secure and simple encryption method  

## **Technology Stack**
- **Programming Language:** Python  
- **Libraries Used:**  
  - OpenCV (`cv2`) – Image processing  
  - OS – File handling  

## **Installation & Setup**
1. **Clone the Repository**  
   ```bash
   git clone https://github.com/yourusername/Image-Steganography.git
   cd Image-Steganography
   ```

2. **Install Dependencies**  
   Ensure you have Python installed, then run:
   ```bash
   pip install opencv-python
   ```

3. **Run the Script**  
   ```bash
   python steganography.py
   ```

## **Usage**
1. The script will ask for a **secret message** and a **passcode**.  
2. It will hide the message inside `mypic.jpg` and save it as `encryptedImage.jpg`.  
3. Open `encryptedImage.jpg` and run the script again to decrypt the message using the correct passcode.  

## **Example**
```plaintext
Enter secret message: Hello, World!
Enter a passcode: 1234
(Encrypted image saved as encryptedImage.jpg)

Enter passcode for Decryption: 1234
Decryption message: Hello, World!
```

## **Screenshots**

![Screenshot 2025-02-22 132530](https://github.com/user-attachments/assets/834a9491-bc42-4d46-8a04-c81413fd38eb)

![Screenshot 2025-02-22 134312](https://github.com/user-attachments/assets/0cf47a79-153b-4ff0-9c48-7c7af1d28ebb)


![Screenshot 2025-02-22 132849](https://github.com/user-attachments/assets/83f749e1-a589-4282-aaf6-c7f9fa850abe)

## **Future Enhancements**
🚀 Improve encryption technique  
🔒 Support for larger messages  
📂 GUI-based application  

## **Contributors**
👤 Aditya Singh Tomar
📧 adityasinghtomar01@gmail.com
