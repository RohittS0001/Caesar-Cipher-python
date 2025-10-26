 🔒ProjectJulius – Caesar Cipher Encoder & Decoder
 A Python project that encrypts and decrypts messages using the classic Caesar Cipher algorithm.
 Description
ProjectJulius is a beginner‑friendly Python command‑line tool that lets users encode and decode secret messages using the Caesar Cipher, one of the oldest and simplest forms of encryption.

This cipher works by shifting letters in the alphabet by a fixed number of positions — wrapping around when reaching the end. The program includes an interactive user interface, ASCII art logo display, input validation, and continuous run capability so users can easily experiment with encryption and decryption.​

✨ Features
Encode and decode text with any numeric shift value.

Supports all characters: keeps spaces, punctuations, and digits unchanged.

Interactive console experience with looping option for multiple encryptions.

Uses modular arithmetic to rotate shifts over the alphabet.

ASCII art logo using the art module for visual appeal.

🧩 How It Works
User Input: Prompts the user for direction (encode or decode), message text, and shift number.

Logic:

If encode, shifts letters forward in the alphabet by the specified value.

If decode, reverses the shift.

Non‑alphabetic symbols are ignored but preserved.

Output: Displays the encrypted or decrypted message.

Repeat Option: Asks if user wants to run the program again.

⚙️ Installation
Make sure you have Python installed. Then install the art package:

bash
pip install art
Clone this repository and navigate to its folder:

bash
git clone https://github.com/yourusername/ProjectJulius.git
cd ProjectJulius
Run the program:

bash
python caesar_cipher.py
🧾 Example Usage
text
Type 'encode' to encrypt, type 'decode' to decrypt:
encode
Type your message:
hello world
Type the shift number:
5
Here is the encoded result: mjqqt btwqi

do you want to continue : yes or no
no
good bye
🧠 Concepts Demonstrated
Caesar Cipher Algorithm

Lists and indexing

Modular arithmetic (%)

Functions and parameters

While loops and condition control

String handling

🛠️ File Structure
text
ProjectJulius/
│
├── caesar_cipher.py       # Main Python file with caesar() function and loop
├── README.md              # Project documentation
└── requirements.txt       # Optional dependencies (art)
🧑‍💻 Author
Rohit Sasane
BCA AIML Student | Python Developer | Cybersecurity Enthusiast
📍 Pune, India

