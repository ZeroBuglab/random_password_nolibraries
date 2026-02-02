# Hello! 👋   
⚙ This Custom Password Generator (No Random Libraries)       
Python password generator that uses a custom-built randomness algorithm instead of standard libraries like random or secrets.    
 
This project focuses on learning how randomness works internally, not on real-world cryptographic security.    
____________________________

# ⚠ Security Warning

This project is for educational purposes only.

The generated passwords are NOT cryptographically secure.
For real password security, it is strongly recommended to use Python’s secrets library.

This generator is designed to experiment with custom logic, not to protect real accounts.
_______________________

## ✨ Features 
* Custom randomness algorithm
* No random or secrets libraries
* User selects password length
* Generates passwords using:
   * Uppercase letters  
   * Lowercase letters 
   * Digits  
   * Symbols  
* Fully written using core Python logic  
_______________

## 🧠 How It Works  
1.	The user enters a password length (minimum 8 characters)   
2.	The program validates the input    
3.	A custom function generates a pseudo-random index  
4.	Characters are selected from a character pool  
5.	The password is built character by character  
6.	The final password is displayed  
  
The randomness is based on hash logic and system timing, created to better understand how random-like behavior can be simulated   
_______________________________
### Example Usage   
the Length of your password(not less than 8): 9   
The length is suitable   
Your Password: Ig6Y%Os]c  
_________________  

## 🛠 Tech Stack   
* Python  
* Custom hash-based random logic  
* Loops (for)  
* Conditions (if / else)  
* String operations  
______________
## 🚀 Installation & Run
git clone https://github.com/yourusername/custom-password-generator-no-random   
cd custom-password-generator-no-random   
python main.py   
 


