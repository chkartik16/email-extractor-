# 📧 Email Extractor

A simple Python automation script that extracts all email addresses from a text file and saves them into a separate file. This project demonstrates the use of Regular Expressions (Regex) and file handling in Python.

## 📌 Features

* Reads data from a `.txt` file.
* Extracts all valid email addresses using Regular Expressions (`re`).
* Saves the extracted emails into a new text file.
* Fast, lightweight, and beginner-friendly.

## 🛠️ Technologies Used

* Python 3
* Regular Expressions (`re`)
* File Handling

## 📚 Concepts Used

* File Reading (`open()`)
* File Writing
* Regular Expressions (`re.findall()`)
* Loops
* String Processing

## 📂 Project Structure

```text
email-extractor/
│── email_extractor.py
│── input.txt
│── emails.txt
└── README.md
```

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/email-extractor.git
   ```

2. Navigate to the project folder:

   ```bash
   cd email-extractor
   ```

3. Add the text containing email addresses to `input.txt`.

4. Run the script:

   ```bash
   python email_extractor.py
   ```

5. The extracted email addresses will be saved in `emails.txt`.

## 📄 Example Input (`input.txt`)

```text
Hello Team,

Please contact us at support@gmail.com for support.
You can also reach admin@yahoo.com or info@company.org.

Thank you!
```

## 📄 Example Output (`emails.txt`)

```text
support@gmail.com
admin@yahoo.com
info@company.org
```

## 🎯 Learning Outcomes

After completing this project, you will understand:

* How to read and write text files in Python.
* How to use Regular Expressions to find patterns in text.
* How to automate repetitive tasks using Python.
* How to process and store extracted data.

## 🔮 Future Improvements

* Remove duplicate email addresses.
* Validate email formats before saving.
* Allow users to choose the input file.
* Export extracted emails to a CSV file.
* Build a simple graphical user interface (GUI).

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository, improve the project, and submit a pull request.

## 📄 License

This project is licensed under the MIT License.
