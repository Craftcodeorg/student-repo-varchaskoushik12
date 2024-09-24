### Assignment: Design a Simple Math Game for Kids

#### Problem Statement:
Create an interactive game using Scratch that teaches basic math concepts, specifically focusing on addition and subtraction. The game should engage kids aged 8-15 by presenting math problems in a fun and interactive way, allowing players to answer questions and receive immediate feedback on their performance. This project will help you apply the concepts discussed in the lecture on programming languages for kids, particularly the use of Scratch as a tool for game-based learning.

#### Starter Code:
Below is a basic framework for your Scratch project. You will need to expand upon this by adding your own elements, such as sprites, backgrounds, and additional logic for the math problems.

```scratch
when green flag clicked
set [score v] to [0]
set [questionCount v] to [5]
repeat (questionCount)
    ask [What is 5 + 3?] and wait
    if <(answer) = [8]> then
        say [Correct!] for 2 seconds
        change [score v] by (1)
    else
        say [Oops! Try again.] for 2 seconds
    end
end
say (join [Your score is: ] (score)) for 2 seconds
```

#### Detailed Instructions:
1. **Set Up the Game Environment**:
   - Create a new Scratch project and choose a fun background that appeals to kids.
   - Add sprites that can represent the player and the question presenter (e.g., a friendly character).

2. **Add Math Questions**:
   - Modify the `ask` block to include a variety of addition and subtraction questions. For example, you can use random numbers for dynamic questions:
     ```scratch
     set [num1 v] to (pick random (1) to (10))
     set [num2 v] to (pick random (1) to (10))
     ask (join [What is ] (join (num1) (join [ + ] (num2)))) and wait
     ```
   - Repeat this process for subtraction questions as well.

3. **Implement Scoring Logic**:
   - Ensure that the score is displayed at the end of the game. You can use a variable to keep track of correct answers.

4. **Provide Feedback**:
   - Use the `say` block to give immediate feedback for correct or incorrect answers. This encourages learning through instant reinforcement.

5. **Enhance User Experience**:
   - Add sound effects or animations when the player answers correctly or incorrectly to make the game more engaging.
   - Consider implementing a timer for each question to increase the challenge.

6. **Test Your Game**:
   - Play through your game multiple times to ensure all elements work as expected. Make adjustments based on your testing.

#### Criteria for Success and Evaluation:
- **Functionality**: The game should correctly ask math questions and evaluate answers.
- **User Engagement**: The game should be visually appealing and provide feedback that keeps players motivated.
- **Code Quality**: The Scratch code should be organized, using clear variable names and comments where necessary.
- **Educational Value**: The game should effectively teach addition and subtraction concepts, making learning fun and interactive.

### Conclusion:
This assignment not only reinforces your understanding of coding concepts but also aligns with your career goal of teaching coding to kids in an engaging manner. By creating this math game, you will build a project that can be included in your portfolio, showcasing your ability to design educational content in the EdTech industry. Happy coding!