# Module Title: Introduction to Coding for Kids

## Exercise Requirements

### 1. Problem Statement
**Scenario**: Imagine you are creating an interactive story game for kids aged 8-15. In this game, players can design their own characters and make them move through different story scenarios. Your task is to implement a function that allows a character to move across the screen based on user input, which will enhance their storytelling experience and engage their creativity.

**Exercise**: Using the concepts discussed in the lecture, design a character and implement the functionality to make it move left or right based on user input. This exercise will help you understand how coding can be integrated into storytelling and game-based learning.

### 2. Fill-in-the-Blank Starter Code
```python
# Starter code for moving a character in an interactive story game

def move_character(position, direction):
    """
    Move the character based on the direction input.
    
    Parameters:
    position (int): Current position of the character on the screen.
    direction (str): Direction to move the character ('left' or 'right').
    
    Returns:
    int: New position of the character.
    """
    
    # Check if the direction is 'left'
    if direction == 'left':
        # Move the character left by subtracting from position
        new_position = position - _______
    
    # Check if the direction is 'right'
    elif direction == 'right':
        # Move the character right by adding to position
        new_position = position + _______
    
    # If direction is not recognized, return current position
    else:
        print("Invalid direction! Please use 'left' or 'right'.")
        return position
    
    return new_position

# Test the function with example values
current_position = 5  # Starting position of the character
new_direction = '_____'  # Fill in with 'left' or 'right'
print("New position:", move_character(current_position, new_direction))
```

### 3. Hints
- **Hint 1**: Think about how you can represent movement numerically. If moving left decreases the position, what number would you subtract?
- **Hint 2**: For moving right, consider how addition works. What number would you add to the current position?
- **Hint 3**: Make sure to validate user input. What should happen if the input is neither 'left' nor 'right'?
- **Hint 4**: Remember to test your function with different starting positions and directions to see how it behaves.

### 4. Expected Outcome
By completing this exercise, students should be able to:
- Fill in the blanks correctly to implement character movement based on user input.
- Demonstrate an understanding of how to apply coding concepts such as conditionals and arithmetic operations in a storytelling context.
- Write well-commented code that explains each step of their logic, ensuring clarity and understanding for future learners.
- Handle invalid input gracefully by providing feedback to the user.

### Integration
This exercise is designed to be engaging and interactive, aligning with your goals of creating captivating projects for kids. The structured format allows for easy integration into your learning platform, supporting your focus on project-based learning and community engagement.