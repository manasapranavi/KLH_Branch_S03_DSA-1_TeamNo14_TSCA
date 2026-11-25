## Project Title: TypeRight: Spell Checker and Autocomplete

**Team No:** KLH/DSA-1/S03/T14

### Team Member Names & ID Numbers:

1. 2620030206 – C.Yasashwini
2. 2620030210 – S.Amulya Reddy
3. 2620030500 – L.Manasa Pranavi

**Supervisor’s Name:** Dr. Madhavi Karumudi

## Abstract:

TypeRight is a Java-based spell checker and autocomplete system designed to help users type words accurately and efficiently. The system maintains a dictionary of words and checks whether an entered word is correctly spelled. It also provides autocomplete suggestions when the user enters the beginning of a word. The project uses data structures and searching techniques to store, retrieve, and process words efficiently. A HashSet is used for storing dictionary words and performing quick word searches, while string operations are used to identify matching prefixes. The system provides a simple menu-driven interface for checking spelling, searching words, displaying dictionary words, and generating autocomplete suggestions. This project demonstrates the practical application of Data Structures and Algorithms in a simple text-processing system.

## Project Structure:

text
TypeRight/
│
├── README.md
│
├── src/
│   └── TypeRight.java
│
├── docs/
│   ├── Abstract.pdf
│   └── Review_PPTs/
│
├── data/
│   └── dictionary.txt
│
├── results/
│   └── output_screenshots/
│
└── reports/
    └── Project_Report.pdf

## Git Commands:

bash
git init
git add .
git commit -m "Initial project setup"
git branch -M main
git remote add origin <repository-link>
git push -u origin main


### Future Enhancements:

- Add better spell-correction suggestions
- Add sorting and binary search
- Implement string-matching algorithms such as KMP
- Expand the dictionary
- Improve autocomplete accuracy
