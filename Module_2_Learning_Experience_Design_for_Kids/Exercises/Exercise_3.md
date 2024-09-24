### Module Title: Learning Experience Design for Kids

### Exercise Requirements

#### 1. Problem Statement
**Scenario**: You are tasked with creating a fun and engaging coding project for kids aged 8-15 that teaches them the concept of fractions using a character. Design a character named "Fraction Fox" who helps players solve fraction problems throughout the game. The character should provide hints and encouragement as players progress through different levels.

**Challenge**: Develop a simple game-based coding project in Scratch where Fraction Fox guides players through various fraction challenges. Players must use coding blocks to help Fraction Fox collect items that represent different fractions (e.g., 1/2, 1/4, etc.) while avoiding distractions.

#### 2. Fill-in-the-Blank Starter Code
```scratch
# Starter code for implementing lecture concepts
when green flag clicked
set [score v] to [0]
say [Hello! I’m Fraction Fox! Let’s learn about fractions!] for (2) seconds

forever
    if <touching [fraction_item v]?> then
        change [score v] by (1)
        say [Great job! You collected a fraction!] for (2) seconds
        # Here, you can add code to display the fraction value collected
        # Fill in the blank below to show the fraction value on the screen
        say [You collected _______] for (2) seconds
    end
end
```
**Instructions**: Fill in the blanks to complete the functionality of the game. Ensure that the code reflects the concept of fractions and engages players effectively.

#### 3. Hints
- **Hint 1**: Remember that each fraction item should have a specific value associated with it. Think about how you can display this value when a player collects it.
- **Hint 2**: Use the `say` block to communicate with players. This is where Fraction Fox can provide hints about fractions.
- **Hint 3**: Consider using lists or variables to keep track of different fractions collected by players.

#### 4. Expected Outcome
Students should be able to fill in the blanks correctly, demonstrating an understanding of how to implement game-based learning concepts into a coding project. The final solution should include:
- A well-commented code that explains the purpose of each section.
- Error handling to ensure that if a player collects an item that is not a fraction, they receive appropriate feedback.
- An engaging storyline where Fraction Fox interacts with players, providing hints and celebrating their achievements.

### Integration
- This exercise is designed to be interactive and project-based, aligning with your preferred learning format.
- Utilize community feedback to refine your project and incorporate storytelling elements effectively.
- Ensure clarity in each section for easy parsing and integration into your learning platform.