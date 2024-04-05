# resume_generator
Resume Assistant

This Python script assists in creating a professional resume using the docx library. It prompts the user to input personal information, education details, work experience, and skills, then generates a formatted resume document.

Installation
1. Clone this repository to your local machine.
2. Install the required dependencies using pip:
- pip install python-docx
- pip install openai
3. Replace 'YOUR_API_KEY' in chat_api.py with your OpenAI API key.

Usage
1. Run the resume_builder.ipynb
2. Follow the prompts to enter your information when prompted.
3. Once all information is entered, a resume document will be generated in the current directory.

Functionality
resume_builder.ipynb
1. Prompts the user to input personal information, education details, work experience, and skills.
2. Utilizes OpenAI's GPT-3.5 model to generate bullet points for work experience based on user input.