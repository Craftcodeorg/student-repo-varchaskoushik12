### Module Title: Introduction to Coding for Kids

### Exercise Requirements

#### 1. Problem Statement:
Imagine you are creating a simple game for kids aged 8-15 using Scratch, where players control a character that collects stars while avoiding obstacles. The game should include a scoring system that awards points for each star collected and deducts points for hitting an obstacle. Your task is to build this game by applying the concepts learned in the lecture about programming languages suitable for kids.

**Your objectives are:**
- Use Scratch to create the game.
- Implement a scoring system that reflects the player's performance.
- Ensure the game is engaging and visually appealing to kids.

#### 2. Fill-in-the-Blank Starter Code:
Below is a starter code snippet for your Scratch project. Fill in the blanks to complete the functionality of the scoring system:

```scratch
when green flag clicked
set [score v] to 0 // Initialize score to zero

forever
    if <touching [star v]?> then // Check if the character touches a star
        change [score v] by 1 // Increment score by 1
        say [You collected a star!] for 2 seconds // Feedback to player
        go to [random position] // Move star to a new random position
    end
    
    if <touching [obstacle v]?> then // Check if the character touches an obstacle
        change [score v] by -1 // Decrement score by 1
        say [Ouch! You hit an obstacle!] for 2 seconds // Feedback to player
    end
end
```

#### 3. Hints:
- **Hint 1:** Make sure to initialize your score variable at the start of the game so that it begins at zero.
- **Hint 2:** Use the `change` block to modify the score based on interactions with stars and obstacles.
- **Hint 3:** Consider adding visual feedback (like sounds or animations) when players collect stars or hit obstacles to make the game more engaging.
- **Hint 4:** Test your game frequently to ensure that the scoring system works correctly and provides a fun experience.

#### 4. Expected Outcome:
Upon completing this exercise, students should be able to:
- Successfully implement a basic game in Scratch that includes a functional scoring system.
- Demonstrate an understanding of how to use conditional statements and variables in Scratch.
- Create an engaging experience for kids, showing how coding can be both educational and entertaining.

The final solution should adhere to best practices in coding, including clear commenting on each block of code to explain its purpose and functionality. This will reinforce the learning objectives of understanding programming concepts and applying them in real-world scenarios in EdTech. 

### Integration
This exercise is structured with clear headings and sections for easy parsing and integration into your learning platform. Utilize markdown formatting for clarity, and ensure all resources are accessible for students as they work through this engaging coding project.