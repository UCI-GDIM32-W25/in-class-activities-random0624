# GDIM32 In Class Activities
## W1

### Activity 1
Advices for acing the class:
- Go to class
- Attend office hours when possible
- Always ask question in class when you don't understand something
- Do the assignments on time, and ask your tablemates when you are stuck

### Activity 2
1. x = 10. 2*5 = 10

2. x = 2. Iterates twice when i=0 and i=1. Stops when i=2.

3. Prints hello world and reprints every second.

4. MonoBehaviour

5. PrintMessage function takes an integer as input and outputs the string x = input. PrintMessage(10) will output x = 10.

6. Explained in Q5.

7. In Update(), you can't just call Transform. You have to call its instance, which is _playerTransform.

8. Explained in Q7.

### Activity 3
[Breakdown Document](https://docs.google.com/document/d/1aIuBE0CrVyJpXfz-9SdCGcqkjD8VZ-L99s91ZUtDOMw/edit?usp=sharing)

#

## W2

### Activity 1
<img width="823" height="629" alt="Screenshot 2026-01-13 at 18 32 53" src="https://github.com/user-attachments/assets/19df260c-9c3a-4d98-92e3-3da91ae90949" />

### Activity 2
[MG2 Commit Link](https://github.com/UCI-GDIM32-W25/mg2-random0624/commit/fd659cfa46e87735e5ec58c46913dc4a916cade9)

#

## W3

### Activity 1-2
Ransom (I did not attend class activities in person)

### Activity 3
<img width="698" height="459" alt="Screenshot 2026-01-20 at 20 01 10" src="https://github.com/user-attachments/assets/859f59c2-1ff9-4b2d-9bab-fb18ce8fad24" />

#

## W4

### Activity 0
Nicole Yang

### Activity 1
Add multiple Locator objects to the Scene. What happens to the Locator objects when you run the game, and why?

When I added multiple Locator GameObjects, the game automatically deletes Locator scripts because there is more than one instance of it. The Locator script makes sure there is only one instance of the Locator GameObject.

### Activity 2
![IMG_5369](https://github.com/user-attachments/assets/ea4a3eff-3604-4afc-8fa5-32868d082e26)

## W5

### Activity 1
For me, this format looks a little bit squished and unorganized. One of the factors is I am not familiar with this design system yet, and the other is that there are more than one class in the same file. I like to keep my classes separate, so if I were to change something, that's what I would change.

### Activity 2
In the second demo, the ItemW5Demo2 and EnemyStats Class is a scriptable object that manages showing the data, or the view. InventoryUI manages modifying and storing the data, which is the model, and the Player Class is the controller.

### Activity 3
#### Scenario 1
Scriptable Objects are really useful in a rhythm game. There are a lot of 'bars' in each level, so it get's very tedious if you make prefabs to store game data. It's a lot easier to store each bar's data in an asset, so it can be modified a lot more effieciently. C# enums are also important. There are different types of 'notes', which can be represented using an enum.

#### Scenario 2
In Valorant, it is useful to have inheritance (pistols rifles awps...) under the parent (Weapons). Each weapon has their distinct stats, animations, skins, and shooting mechanism. The data can be retrieved from scriptable objects, that can store constant_like data like weapon damage, falloff damage, utility duration, cooloff duration etc.

#### Scenario 3
An inheritance can be used in stardew valley to create different actions when the player plants different seeds, or destroy different plants. Polymorphism is what allows different output for different plants and objects from the same input (keypress for example). I've never played stardew valley before, but I assume different plants have different data, like value, time to plant, etc... This can be implemented using Scriptable Objects. State Machine is useful for plant or player. State of plant's growth, or player's action state.

### Activity 4
Attendance: Ro, Ransom, Evrin
[Proposal Document](https://docs.google.com/document/d/1yaFfMOREKQ-uBypP_ClrG3IaEjA-R7tuW3AvkSeLdno/edit?tab=t.0#heading=h.wcm5jag04eng)