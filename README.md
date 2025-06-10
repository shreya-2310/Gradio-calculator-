This project is a web-based calculator built using Gradio that performs basic arithmetic operations — Addition, Subtraction, Multiplication, and Division — via a user-friendly interface.

🔧 Technologies Used

Python

Gradio for GUI

Google Colab / Jupyter environment compatible


🚀 Features

Takes two numeric inputs

Lets users choose one of the four operations

Displays the result instantly

Handles division by zero gracefully

Interactive UI accessible via a public shareable link
🧠 How It Works

Each arithmetic operation is defined as a Python function.

A master function calculator() maps the operation string to the correct function.

The Gradio interface (gr.Interface) links the calculator function with the UI components.
