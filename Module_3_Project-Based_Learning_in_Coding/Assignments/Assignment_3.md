### Assignment: Build an Educational Game that Incorporates Math and Storytelling Elements

#### Problem Statement
Create an interactive educational game that teaches math concepts through storytelling. The game will allow players to navigate a story by solving math problems that unlock different parts of the narrative. This project will reinforce the concepts of Project-Based Learning (PBL) and demonstrate how storytelling can enhance the learning experience in coding education.

#### Starter Code
Below is a basic framework for your educational game. This code sets up a simple text-based adventure where players must solve math problems to progress through the story. You will need to expand upon this starter code by adding more story elements and math challenges.

```python
# Starter code for an educational math game

def start_game():
    print("Welcome to the Math Adventure!")
    print("You are a brave knight on a quest to save the kingdom.")
    
    # Step 1: Introduce the first challenge
    first_challenge()

def first_challenge():
    print("\nYou come across a river that you need to cross.")
    print("To build a bridge, you need to solve this math problem:")
    
    # Math problem
    answer = 5 + 3  # Change this to any math problem you prefer
    user_answer = int(input("What is 5 + 3? "))
    
    if user_answer == answer:
        print("Correct! You built the bridge and can now cross the river.")
        second_challenge()
    else:
        print("Incorrect! You cannot cross the river until you solve the problem.")
        first_challenge()  # Repeat the challenge

def second_challenge():
    print("\nAfter crossing the river, you encounter a dragon!")
    print("To defeat the dragon, you need to solve this math problem:")
    
    # Math problem
    answer = 12 - 4  # Change this to any math problem you prefer
    user_answer = int(input("What is 12 - 4? "))
    
    if user_answer == answer:
        print("Correct! You have defeated the dragon and saved the kingdom!")
    else:
        print("Incorrect! The dragon is still blocking your path.")
        second_challenge()  # Repeat the challenge

# Start the game
start_game()
```

#### Detailed Instructions
1. **Expand the Storyline**: Add more chapters to your game. Each chapter should present a new challenge that requires solving a math problem to progress. Think about different settings (e.g., forest, castle, village) and characters (e.g., wizards, villagers) that could be involved in the story.

2. **Create Math Challenges**: For each chapter, create a unique math problem. You can include addition, subtraction, multiplication, division, or even more complex problems based on the age group of your target audience (8-15 years). 

3. **Implement Feedback Mechanism**: After each answer, provide feedback to the player. If they answer correctly, congratulate them and let them know they can move on. If they answer incorrectly, encourage them to try again.

4. **Enhance User Experience**: Consider adding more interactive elements, such as sound effects or visual elements if you're using a platform like Scratch or Pygame. 

5. **Test Your Game**: Once your game is complete, play through it multiple times to ensure that all math problems are solvable and that the story flows well.

#### Criteria for Success and Evaluation
- **Educational Value**: The game should effectively teach math concepts appropriate for kids aged 8-15.
- **Engagement**: The storyline should be captivating and encourage players to continue playing.
- **Functionality**: The code must run without errors, and all math challenges should be solvable.
- **Code Quality**: The code should be cleanly written, well-organized, and include comments explaining each section.
- **User Experience**: The game should provide clear instructions and feedback to players.

By completing this assignment, you will apply key concepts from Project-Based Learning in coding while creating an engaging educational tool that aligns with your career goals in EdTech.