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

## W6

### Activity 1
As mentioned in my W6 Pre-learning quiz, we can use Gizmos for a lot of the character interactions debugging. We can use drawwiresphere to debug colliders, and drawrays for interaction distance. 
Profiler can be useful to determine which part of your code can be improved performance-wise. It's crucial for helping with game performance and optimization. A few optimization tips include: 
- Don't put stuff in Update() that doesn't have to run every frame. 
- Don't use GetComponent() too often.

### Activity 2
Ro, Ransom


## W7

### Activity 1
This activity is perfect for our final project! This demo introduces raycast, finite state machine, and gizmos, to create a scenario of a NPC wandering around, and then chases the player when they get too close. The UpdateState() method controls which state to run, and HasLineofSightToPlayer() method determines wether or not the duck can see the player with no obstacles in between, this is done using a raycast pointing directly from the duck to the player. 

### Activity 2
I am sick today, but I coordinated beforehand with my group members and I am working from home.

### Activity 3
![IMG_5468](https://github.com/user-attachments/assets/cdd7c0fa-ec93-49d2-98ed-4bf084d43def)

### Activity 4
[Trello Board](https://trello.com/b/dcBIyEk5/gdim-32-final)

### Activity 5
[Recent Commit](https://github.com/random0624/GDIM32-Final/commit/14691c3c5457ac4697f3472133b1beeb625c8976)

Created Collectables Folder for Collectable.cs (parent class), and Key.cs, Meat.cs for child classes. Also initiated a Scriptable Object Class for storing item info (name, icon (if needed), description, and an int value to differentiate between key and meat).


## W8

### Activity 1: Post Processing Demo
The bloom post-processing effect brightens colors and adds a glowing effect around it. Make sure you install the post-processing module in Unity. Add a post-processing volume to your game (can be anywhere, doesn't matter where). There are a ton of settings you can tune in the post-processing volume component. "Drunk Effect" is also an example of post-process rendering, because it effects the whole screen, and not just a specific game object. 

### Activity 2: Team Attendance
Ro, Evrin, Ransom

### Activity 3: Playtest
Playtesting goal: Everything we did for this week functions (movement, lion chasing, and can click on door to interact with it)

Playtesting Captain: Evrin

Playtesting Notes:
    - Collision with the rocks is not working as intended at the moment
    - Collision with the lion is not working as intended as well
    - Lion trigger distance should be a lot larger
    - Lion might be a little too fast

### Activity 4: Task Check-in
I am getting scriptable objects hooked up to all assets, and hopefully get the inventory system ui working.

## W9

### Activity 1: Demo
Walking close to Duckie will initiate a branching dialogue option. Each option gets a different response from Duckie. The player gets to choose which option to pick. If Duckie is an NPC, the branching dialogue should loop back to a response where the branching is stopped.

### Activity 2: Team Attendance
Ro, Evrin, Ransom

### Activity 3: Playtest

Playtesting Captain: Evrin Lee

Playtesting Goal: Player can move around and experience all currently existing interaction without confusion. This includes being able to pickup items, the lion chases the player when close, and player is able to throw out meat from their inventory.
