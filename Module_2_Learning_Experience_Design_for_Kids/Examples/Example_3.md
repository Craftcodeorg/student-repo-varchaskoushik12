### Module Title: Learning Experience Design for Kids

### Example 3: Building a Math Adventure Game using Python

#### 1. Introduction
In this example, we will explore the concept of "Building a Math Adventure Game using Python," as discussed in the lecture on integrating game-based learning into coding projects. This project is significant in EdTech because it not only teaches children coding skills but also reinforces mathematical concepts through interactive gameplay. By merging storytelling with educational content, we can create engaging experiences that captivate young learners and enhance their understanding of both coding and math.

#### 2. Code Snippet
Here’s a well-commented Python code snippet that illustrates how to create a simple Math Adventure Game. This game challenges players with math questions as they navigate through different levels.

```python
import random

def ask_question(level):
    """Asks a math question based on the current level."""
    if level == 1:
        # Level 1: Simple addition
        num1 = random.randint(1, 10)
        num2 = random.randint(1, 10)
        correct_answer = num1 + num2
        question = f"What is {num1} + {num2}?"
    elif level == 2:
        # Level 2: Simple subtraction
        num1 = random.randint(1, 20)
        num2 = random.randint(1, 20)
        correct_answer = num1 - num2
        question = f"What is {num1} - {num2}?"
    else:
        # Level 3: Multiplication
        num1 = random.randint(1, 10)
        num2 = random.randint(1, 10)
        correct_answer = num1 * num2
        question = f"What is {num1} * {num2}?"

    return question, correct_answer

def play_game():
    """Main function to play the Math Adventure Game."""
    level = 1
    score = 0

    print("Welcome to the Math Adventure Game!")
    
    while level <= 3:
        question, correct_answer = ask_question(level)
        
        try:
            user_answer = int(input(f"Level {level}: {question} "))
            if user_answer == correct_answer:
                print("Correct! Moving to the next level.")
                score += 1
                level += 1
            else:
                print(f"Incorrect. The correct answer was {correct_answer}. Try again!")
        except ValueError:
            print("Please enter a valid number.")

    print(f"Game Over! Your final score is: {score}/3")

if __name__ == "__main__":
    play_game()
```

#### 3. Explanation
- **Function Definitions**: The code begins by defining two functions: `ask_question` and `play_game`. The `ask_question` function generates a math question based on the player's current level. Each level introduces different types of math operations (addition, subtraction, multiplication).
  
- **Random Number Generation**: The use of `random.randint` allows for dynamic question generation, ensuring that each game session is unique and engaging.

- **Error Handling**: The `try-except` block in the `play_game` function captures invalid inputs (e.g., non-integer values), prompting the player to enter a valid number. This enhances user experience by preventing the game from crashing due to input errors.

- **Game Logic**: The game progresses through three levels, with players answering questions to advance. If they answer correctly, they move to the next level; otherwise, they are prompted to try again. This structure maintains engagement and encourages learning through repetition.

#### 4. Application
This Math Adventure Game serves as an excellent example of how coding can be utilized in educational settings to reinforce math skills. In EdTech, such projects address common challenges like student disengagement and difficulty in grasping mathematical concepts. By gamifying learning, we can create an interactive environment that motivates students to practice math while developing their coding skills.

### Integration
- The content is structured with clear headings and sections for easy parsing and integration into your learning platform.
- Use markdown formatting for clarity and organization throughout your curriculum materials.

By implementing this project into your teaching repertoire, you will not only meet your daily learning goals but also create captivating experiences that foster both coding proficiency and mathematical understanding in kids aged 8-15.