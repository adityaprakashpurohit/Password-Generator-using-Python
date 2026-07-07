# 🔐 Python Password Generator

A simple and powerful Password Generator built with Python that allows users to create secure passwords using two different modes:

- **Regular Mode** – Generate a password based on desired length.
- **Complex Mode** – Generate a password with custom numbers of uppercase letters, lowercase letters, numbers, and special characters.

## 📌 Features

### Regular Mode
- Generate passwords of any specified length.
- Uses a combination of:
  - Uppercase letters
  - Lowercase letters
  - Numbers
  - Special characters

### Complex Mode
- Fully customizable password generation.
- Choose the number of:
  - Uppercase letters
  - Lowercase letters
  - Numbers
  - Special characters
- Password characters are shuffled for enhanced security.

## 🛠️ Technologies Used

- Python 3
- Random Module

## 📂 Project Structure

```
Password-Generator/
│
├── main.py
├── complex.py
├── regular.py
└── README.md
```

## 🚀 Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/password-generator.git
```

2. Navigate to the project directory:

```bash
cd password-generator
```

3. Run the program:

```bash
python main.py
```

## 💻 Usage

When you run the program, you will see:

```text
1. Generate Password Regular Mode (By Length)
2. Generate Password Complex Mode (By Characters)
```

### Option 1: Regular Mode

Enter the desired password length.

Example:

```text
Enter length of Password you want to Generate :- 12
```

Output:

```text
Generated Password is :- A@9dK#2mLp1$
```

### Option 2: Complex Mode

Specify how many characters of each type you want.

Example:

```text
Uppercase Letters: 3
Lowercase Letters: 4
Special Characters: 2
Numbers: 3
```

Output:

```text
Generated Password is :- a@G8k#P2mQ1d
```

## 🔒 Security Notes

- Passwords are generated randomly using Python's built-in `random` module.
- Complex Mode shuffles characters to improve randomness.
- For highly sensitive applications, consider using Python's `secrets` module instead of `random`.

## 📈 Future Improvements

- GUI Version using Tkinter
- Password Strength Checker
- Copy Password to Clipboard
- Save Password to File
- Dark Mode Interface
- Generate Multiple Passwords at Once

## 👨‍💻 Author

**Aditya Prakash Purohit**

📧 Email: adityaprakashpurohit@gmail.com

## ⭐ Support

If you found this project useful:

- Star the repository ⭐
- Fork the project 🍴
- Share it with others 🚀

---

Made with ❤️ using Python
