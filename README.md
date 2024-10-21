# Collatz Conjecture - Interactive Web Page

Welcome to the **Collatz Conjecture Interactive Web Page**! This project explores one of the most intriguing and unsolved problems in mathematics—**the Collatz Conjecture**—through a dynamic and interactive visualization.

## 📚 What is the Collatz Conjecture?

The **Collatz Conjecture**, also known as the **3n + 1 problem**, is a deceptively simple mathematical conjecture proposed by Lothar Collatz in 1937. Despite its simplicity, this problem remains unsolved and continues to fascinate mathematicians.

### 🧠 The Conjecture:

Given any positive integer `n`, apply the following rules:
1. **If n is even**, divide it by 2:  
   `n → n / 2`
   
2. **If n is odd**, multiply it by 3 and add 1:  
   `n → 3n + 1`

Repeat this process indefinitely, and the conjecture claims that no matter which number you start with, you will eventually reach the number **1**.

### 🌟 Example:
Start with `n = 6`:
- 6 is even → `6 / 2 = 3`
- 3 is odd → `3 * 3 + 1 = 10`
- 10 is even → `10 / 2 = 5`
- 5 is odd → `5 * 3 + 1 = 16`
- 16 is even → `16 / 2 = 8`, `8 / 2 = 4`, `4 / 2 = 2`, `2 / 2 = 1`

Eventually, we reach `1`. The Collatz Conjecture claims this will always happen, no matter the starting value of `n`—but no one has been able to **prove** it for all integers.

---

## 🌐 About This Project

This project provides an **interactive web page** where users can explore the Collatz Conjecture visually. Input a number, and the webpage will dynamically generate the sequence of numbers and showcase the step-by-step transformations as they either grow or shrink according to the Collatz rules. 

### 🚀 Features:
- **User Input**: Enter any integer, and the web page will display the sequence following the Collatz rules.
- **Visual Representation**: Each step in the sequence is visually plotted to make it easy to follow the transformation of numbers.
- **Real-Time Calculations**: Watch the Collatz process unfold instantly.
- **Graphing Feature**: See a graph of the numbers as they climb and fall during the transformation process.

---

## 🛠 How It Works

1. **Input a number**: Users can input any positive integer on the webpage.
2. **Collatz Sequence Generation**: The page calculates the sequence according to the rules of the conjecture.
3. **Visual Display**: The sequence is displayed both as text and as a graph, showing how the numbers evolve over time.

### ⚙️ Technologies Used:
- **HTML/CSS**: For building the structure and styling the web page.
- **JavaScript**: Handles the logic for generating the Collatz sequence and dynamically updating the page.


---

## 📈 Why Is This Important?

The Collatz Conjecture might seem simple, but it holds a mysterious allure because no one has been able to definitively prove it true or false for all integers. This unsolved problem invites anyone to test different numbers, visualize sequences, and delve deeper into the beauty of mathematics.

Through this project, you can explore how simple rules can lead to complex behaviors—a concept that fascinates mathematicians and computer scientists alike.


