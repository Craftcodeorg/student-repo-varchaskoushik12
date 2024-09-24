# Module Title: Learning Experience Design for Kids

## Exercise Requirements

### 1. Problem Statement
Create an interactive quiz based on a story that involves a young coder helping a robot navigate through a digital maze. The quiz should consist of multiple-choice questions that challenge students to apply coding concepts discussed in the lecture, such as decision-making with `if` statements and understanding the elements of storytelling.

### 2. Fill-in-the-Blank Starter Code
```python
# Starter code for creating an interactive quiz based on a story
def quiz_question(question, options, correct_answer):
    print(question)
    for i, option in enumerate(options):
        print(f"{i + 1}. {option}")
    
    user_answer = input("Choose the correct option (1-4): ")
    
    # Check if the user's answer is correct
    if _______ == correct_answer:
        print("Correct! Great job!")
    else:
        print("Oops! That's not correct. Try again!")

# Example usage of the quiz function
quiz_question(
    "What should the robot do when it reaches a wall?",
    ["Turn left", "Turn right", "Go back", "Jump over"],
    _______  # Fill this with the correct answer option number
)
```

### 3. Hints
- **Hint 1**: Remember to use the index of the options list to determine which option corresponds to the correct answer.
- **Hint 2**: The `input()` function will return a string, so you may need to convert it to an integer to compare it with `correct_answer`.
- **Hint 3**: Think about how you can structure your question and options to reflect the elements of storytelling discussed in the lecture.

### 4. Expected Outcome
Students should be able to fill in the blanks correctly, demonstrating an understanding of how to create an interactive quiz based on storytelling elements. The final solution should include:
- A correctly implemented comparison of the user's answer with the correct answer.
- Proper error handling if the user inputs an invalid option.
- Well-commented code explaining each step, reinforcing their learning from the lecture.

## Integration
This exercise is structured to be easily integrated into a learning platform. Each section is clearly defined with headings for easy navigation. The use of markdown formatting ensures clarity and enhances readability for students. 

Encourage students to think creatively about how they can further develop this quiz by adding more questions or incorporating additional coding concepts they have learned. This aligns with their goal of creating captivating and educational projects for kids aged 8-15.