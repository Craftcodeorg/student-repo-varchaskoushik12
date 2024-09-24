### Assignment: Develop a Game that Incorporates Storytelling to Teach a Science Concept

#### Problem Statement
Create an interactive game that teaches children about the water cycle through storytelling. The game should allow players to navigate through different stages of the water cycle (evaporation, condensation, precipitation, and collection) by making choices that affect the storyline. This assignment will help you apply the principles of Learner-Centered Design and Engagement through Interactivity, as discussed in the lecture.

#### Starter Code
Below is a basic framework for the game. You will build upon this code to create an engaging storytelling experience.

```python
# Starter code for Water Cycle Adventure Game

class WaterCycleGame:
    def __init__(self):
        self.stage = "Evaporation"
    
    def start_game(self):
        print("Welcome to the Water Cycle Adventure!")
        print("You are a water droplet on an exciting journey through the water cycle.")
        self.next_stage()

    def next_stage(self):
        if self.stage == "Evaporation":
            self.evaporate()
        elif self.stage == "Condensation":
            self.condense()
        elif self.stage == "Precipitation":
            self.precipitate()
        elif self.stage == "Collection":
            self.collect()

    def evaporate(self):
        print("You are heating up and turning into vapor!")
        choice = input("Do you want to (1) rise into the sky or (2) stay in the puddle? ")
        if choice == "1":
            self.stage = "Condensation"
            self.next_stage()
        else:
            print("You decided to stay in the puddle. Game Over!")
    
    def condense(self):
        print("You have turned into a cloud!")
        choice = input("Do you want to (1) float away or (2) gather with other clouds? ")
        if choice == "1":
            self.stage = "Precipitation"
            self.next_stage()
        else:
            print("You gathered with other clouds and grew heavier. Game Over!")

    def precipitate(self):
        print("It's raining! You are falling back to Earth.")
        choice = input("Do you want to (1) fall into a river or (2) land on a mountain? ")
        if choice == "1":
            self.stage = "Collection"
            self.next_stage()
        else:
            print("You landed on a mountain and melted into a stream. Game Over!")

    def collect(self):
        print("You have returned to a body of water, completing the cycle!")
        print("Congratulations! You've completed the Water Cycle Adventure.")

# Run the game
game = WaterCycleGame()
game.start_game()
```

#### Detailed Instructions
1. **Step 1**: Modify the `evaporate()` method to include a fun fact about evaporation when the player chooses to rise into the sky.
   - Example: `print("Did you know? Evaporation is when water turns into vapor due to heat!")`

2. **Step 2**: Add additional stages for the water cycle, such as more detailed choices in `condense()`, `precipitate()`, and `collect()`. For example, in `precipitate()`, allow players to choose between rain, snow, or hail.

3. **Step 3**: Implement feedback for each choice that reinforces learning. For instance, after each stage, provide a brief explanation of what happens in that part of the water cycle.

4. **Step 4**: Ensure that the game can be played multiple times with different outcomes based on player choices.

5. **Step 5**: Add a scoring system based on how many stages players successfully navigate without hitting a game-over scenario.

#### Criteria for Success and Evaluation
- **Functionality**: The game should run without errors and allow players to navigate through all stages of the water cycle.
- **Educational Value**: The game must effectively teach children about the water cycle through engaging storytelling and factual information.
- **Code Quality**: The code should be clean, well-documented, and follow best practices for readability.
- **User Experience**: The game should be user-friendly, with clear prompts and engaging content that keeps players interested.

By completing this assignment, you will create an interactive educational experience that aligns with your career goals in EdTech and showcases your ability to integrate storytelling into coding education for kids.