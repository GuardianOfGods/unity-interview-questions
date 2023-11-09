<div align="center">
	<img width="800" src="https://github.com/GuardianOfGods/unity-interview-questions/assets/52252046/c658bd6c-58be-4d01-94fa-12cda489935b"> 
</div>

---
# Unity Interview Questions
👋 **Hi there, I'm HoangVanThu.** These are questions I interviewed and also collected on websites. I hope it helps you a lots. <br>
Let's answer the questions and achieve your goals !!

**Question by level:**
- [Intern](#Intern)
- [Fresher](#Fresher)
- [Junior](#Junior)
- [Intern](#Intern)
- [Intern](#Intern)
## Intern
Decription: who study in school and work at company at the same time.

**1. Question: There are many game genres. Can you name some games genres?**

<details><summary><b>Answer</b></summary>
<p>

- **Action** games are a broad genre that typically involves player-controlled characters engaging in various challenges, missions, or activities that require quick reflexes, hand-eye coordination, and a focus on physical challenges. These games often feature a combination of combat, exploration, and puzzle-solving. Action games can further be categorized into sub-genres like platformers, beat 'em ups, and more. Example:  "Super Mario Bros", "Devil May Cry" and "Uncharted."
- **Platformer** games, also known as platform games, are a genre where the main gameplay revolves around controlling a character to navigate through a series of platforms and levels. The player must jump, run, and sometimes solve puzzles to progress through the game. The term "platformer" comes from the platforms, or surfaces, that the character moves across. Example: "Super Mario Bros.," "Sonic the Hedgehog," and "Donkey Kong."
- **RPG** stands for Role-Playing Game. In RPG games, players take on the roles of characters within a fictional world. These games often involve a rich narrative, character development, and decision-making that can impact the game's storyline. Players typically have the freedom to customize their characters, choosing their abilities, appearance, and sometimes even moral alignment. Examples include "The Legend of Zelda" series and the "Dark Souls" series.
- **FPS** stands for First-Person Shooter, which is a sub-genre of action games. In FPS games, players experience the game from a first-person perspective, meaning the game's viewpoint is through the eyes of the player character. The primary focus of FPS games is on combat, and players typically use firearms or other ranged weapons to engage enemies. Example: "Call of duty", "Counter Strike"
- **Simulation** games are a genre that aims to replicate real-world activities or systems in a virtual environment. These games often prioritize realism and accuracy in depicting various aspects of life, ranging from economic and social simulations to more specific activities like farming, flight, or driving. Simulation games can be educational or purely entertaining. Example: "Microsoft Flight Simulator", "SimCity", "Stardew Valley".
- Etc.

</p>
</details>

**2. What platforms are supported by Unity?**

<details><summary><b>Answer</b></summary>
<p>

- **Desktop**:
  - Windows (PC)
  - Mac
  - Universal Windows Platform (UWP)
  - Linux Standalone
- **Mobile**:
  - iOS
  - Android
- **Extended Reality (XR)**:
  - ARKit
  - ARCore
  - Microsoft HoloLens
  - Windows Mixed Reality
  - Magic Leap (Lumin)
  - Oculus
  - PlayStation VR
- **Consoles**:
  - PS5
  - PS4
  - Xbox One
  - Xbox X|S
  - Nintendo Switch
  - Google Stadia
  - WebGL
- **Embedded**:
  - Embedded Linux
  - QNX

</p>
</details>

**3. Question: What is FPS? How does FPS affect to the game?**

<details><summary><b>Answer</b></summary>
<p>

- FPS index is the acronym for **Frames-per-second** the number of frames displayed per second. Simply put, it measures the number of images that the video card can process per second and display on your screen. The higher the FPS index, the smoother, sharper and less lag the displayed image quality.

</p>
</details>

**4. Question: Describe a game engine.**

<details><summary><b>Answer</b></summary>
<p>

- **A game engine** is a software framework designed to facilitate the creation and development of video games. It provides developers with a set of tools, libraries, and features that streamline the game development process, allowing them to focus on creating game content rather than dealing with low-level programming tasks.

- **Key components** of a game engine include:
  - **Rendering Engine**: Manages graphics, rendering 2D or 3D visuals, and handling aspects like lighting, shadows, and special effects.
  - **Physics Engine**: Simulates real-world physics, determining how objects interact with each other, respond to gravity, collisions, etc.
  - **Audio Engine**: Handles sound effects, music, and overall audio output within the game.
  - **Scripting Engine**: Allows developers to write scripts or code to control game logic, events, and behavior. This often uses programming languages like C++, Python, or a proprietary scripting language.
  - **Asset Pipeline**: Manages the import, processing, and integration of game assets such as 3D models, textures, sound files, etc.
  - **Networking**: Provides tools for multiplayer functionality, enabling communication between players and managing online features.
  - **Input Handling**: Manages user input from devices like keyboards, mice, controllers, and touchscreens.
  - **Scene Graph**: Represents the hierarchical structure of the game world, defining how objects are arranged and interact.

Popular game engines include **Unity**, **Unreal Engine**, and **CryEngine**. Game developers leverage these engines to accelerate development, reduce repetitive tasks, and achieve a level of consistency in game design and performance.

</p>
</details>

## Fresher
Decription: who graduated and start working at company.

**1. Question: Name some important tab components of Unity 3D.**

<details><summary><b>Answer</b></summary>
<p>

- **Hierarchy**: The hierarchy displays every GameObject in a list.
- **Inspector** displays detailed information about your currently selected GameObject, including all attached Components and their properties. Here, you modify the functionality of GameObjects in your scene.
- **Game view**: The game view option lets developers view the game and make changes to it as they play in real time.
- **Scene view**: The scene view is a 3D preview of the open scene. Here, developers can add and manage GameObjects.
- **Project window**: The project window is ideal for complex games. Game developers can use the project window to find game assets in a directory for all models, scripts, and prefabs.
- **Toolbar**: The toolbar contains various tools for the game and scene windows.

</p>
</details>

**2. Question: What is Object-Oriented Programming (OOP)? List principles of Object-Oriented Programming.**

<details><summary><b>Answer</b></summary>
<p>

- **Object-oriented programming** is a programming paradigm, or classification, that organizes a group of data attributes with functions or methods into a unit, known as an object.

- There are 4 principles of OOP:
  - **Encapsulation** means to enclose data by containing it within an object. In OOP, encapsulation forms a barrier around data to protect it from the rest of the code. You can perform encapsulation by binding the data and its functions into a class. This action conceals the private details of a class and only exposes the functionality essential for interfacing with it. When a class doesn't allow direct access to its private data, it's well-encapsulated.
  - **Abstraction** refers to using simplified classes, rather than complex implementation code, to access objects. Often, it's easier to design a program when you can separate the interface of a class from its implementation. In OOP, you can abstract the implementation details of a class and present a clean, easy-to-use interface through the class member functions. Abstraction helps isolate the impact of changes made to the code so if an error occurs, the change only affects the implementation details of a class and not the outside code.
  - Most object-oriented languages support **Inheritance**, which means a new class automatically inhabits the same properties and functionalities as its parent class. Inheritance allows you to organize classes into hierarchies, where a class might have one or more parent or child classes. If a class has a parent class, it means the class has inherited the properties of the parent. The child class can also modify or extend the behavior of its parent class. Inheritance allows you to reuse code without redefining the functions of a child class.
  - **Polymorphism** refers to creating objects with shared behaviors. In OOP, polymorphism allows for the uniform treatment of classes in a hierarchy. When you write code for objects at the root of the hierarchy, any objects created by a child class within the hierarchy have the same functions. Depending on the type of object, it may execute different behaviors.
    
</p>
</details>

**3. Question: What are the necessary conditions for objects to collider?.**

<details><summary><b>Answer</b></summary>
<p>

- Both objects must have a Collider, and one of the objects must also have a Rigidbody.
    
</p>
</details>

**4. Question: What is the order in which OnEnable, Awake, and Start occur during runtime? Which ones are likely to occur repeatedly within the same object cycle?.**

<details><summary><b>Answer</b></summary>
<p>

- **Awake** –> **OnEnable** -> **Start**. **OnEnable** can occur repeatedly in the same cycle!
    
</p>
</details>

**5. Question: What difference between stack and queue?**

<details><summary><b>Answer</b></summary>
<p>

- **Stacks and queues** are both data structures that organize and manage collections of elements, but they differ in how elements are added and removed.

- **Stack**:
	- **Last In, First Out (LIFO)**: The last element added to the stack is the first one to be removed. Elements are added and removed from the same end, often referred to as the "top" of the stack. Common operations include push (to add an element) and pop (to remove the last-added element).

- **Queue**
	- **First In, First Out (FIFO)**: The first element added to the queue is the first one to be removed. Elements are added at one end (rear or back) and removed from the other end (front). Common operations include enqueue (to add an element) and dequeue (to remove the first-added element).
    
</p>
</details>

**6. Question: Briefly describe the use of prefab.**

<details><summary><b>Answer</b></summary>
<p>

- Instantiated when the game is running, prefab is equivalent to a template, making a default configuration for the materials, scripts, and parameters you already have to facilitate future modifications. The content packaged by prefab simplifies the export operation and facilitates team communication.
    
</p>
</details>

**7. Question: What function is used to rotate the object itself ?**

<details><summary><b>Answer</b></summary>
<p>

- Transform.Rotate()
    
</p>
</details>

**8. Question: What is a coroutine?**

<details><summary><b>Answer</b></summary>
<p>

- Answer: While the main thread is running, another piece of logic processing is started at the same time to assist the execution of the current program. In other words, starting a coroutine is to start a logic that can be parallel to the program. Can be used to control motion, sequences, and object behavior.
    
</p>
</details>

**9. Question: List some ways to move an object in Unity.**

<details><summary><b>Answer</b></summary>
<p>

- There are several ways to move an object. Here are some common methods:
  - **Transform Translate**
  - **Rigidbody Velocity**
  - **Rigidbody AddForce**
  - **Transform Position**
  - **Lerp Position**
</p>
</details>

**10. Question: Explain why "Time.deltaTime" should be used to make things that depend on time operate correctly.**

<details><summary><b>Answer</b></summary>
<p>

- Unity games run on different devices with varying hardware capabilities. If you use fixed values for movement or animations without considering the frame rate, they might appear too fast on a high-performance device and too slow on a low-performance one.
- **Time.deltaTime** represents the time it took to complete the last frame. Multiplying your movement or animation values by **Time.deltaTime** ensures that the speed remains consistent across different frame rates.
- When you use **Time.deltaTime**, your game elements move or animate smoothly regardless of the frame rate. This is crucial for a consistent and enjoyable user experience.
- Unity's physics engine relies on time to simulate realistic interactions between objects. Using **Time.deltaTime** in physics calculations ensures that the behavior of your game's physics remains consistent across various devices.
- For effects that depend on time, such as fading, flashing, or pulsating, using **Time.deltaTime** allows you to control the speed of these effects based on the time elapsed, creating a more dynamic and visually appealing experience.
    
</p>
</details>

## Junior
Decription: who have 1-3 years work with Unity.

## Middle Junior
Decription: who have more than 3 years work with Unity.

## Senior
Decription: practically who have more than 5 years work with Unity and base on knowledge.
