# Assignment: Create an Animated Greeting Card for a Friend Using Scratch

## Problem Statement
Design and develop an animated greeting card using Scratch that conveys a heartfelt message to a friend. The card should incorporate interactive elements that respond to user inputs, demonstrating the principles of coding and storytelling discussed in the lecture. This assignment will help you understand how coding can be used to create engaging narratives and enhance your skills in creating educational content for kids.

## Starter Code
Below is a basic framework in Scratch that sets up the environment for your animated greeting card. You'll need to build upon this by adding your own creative elements, animations, and interactions.

### Scratch Starter Code Snippet:
```scratch
// When the card is opened
when green flag clicked
go to x: 0 y: 0
say "Welcome to my Greeting Card!" for 2 seconds
wait 1 second
broadcast [show_animation v]

// Animation for the greeting card
when I receive [show_animation v]
repeat 10
    change size by 10
    wait 0.1 seconds
    change size by -10
    wait 0.1 seconds
end
say "Happy Birthday, [Friend's Name]!" for 3 seconds
```

## Detailed Instructions
1. **Customize Your Message**:
   - Replace `[Friend's Name]` in the starter code with the actual name of your friend.
   - Change the greeting message to suit the occasion (e.g., birthday, congratulations, etc.).

2. **Add Interactive Elements**:
   - Create a new sprite (e.g., a character or an object) that will interact with the user.
   - Use the following code snippet to make the sprite respond when clicked:
   ```scratch
   when this sprite clicked
   say "Thank you for being a great friend!" for 2 seconds
   ```

3. **Enhance the Animation**:
   - Modify the `show_animation` broadcast to include additional animations or effects.
   - Consider adding sound effects or background music to make your card more engaging.

4. **Incorporate Visuals**:
   - Add colorful backgrounds and images that reflect the theme of your greeting card.
   - Use Scratch’s drawing tools or upload images to make your card visually appealing.

5. **Testing Your Card**:
   - Click the green flag to test your animated greeting card.
   - Ensure all elements work as intended and that interactions are smooth.

## Criteria for Success and Evaluation
Your animated greeting card will be evaluated based on the following criteria:

- **Creativity and Engagement**: The card should be visually appealing and creatively designed to engage the user.
- **Functionality**: All interactive elements must work correctly, responding as expected when clicked or interacted with.
- **Code Quality**: The code should be well-organized and easy to understand, with comments explaining key sections where necessary.
- **Message Clarity**: The greeting message should be clear and appropriate for the occasion.

### Success Criteria:
- The card successfully displays an animated greeting message.
- Interactive elements provide feedback and respond correctly to user inputs.
- The project demonstrates an understanding of basic coding concepts such as events, broadcasts, and user interactions.

By completing this assignment, you will not only reinforce your understanding of coding principles but also create a fun and educational project that can inspire kids aged 8-15 in their coding journey!