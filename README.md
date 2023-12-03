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
- [Middle Junior](#Middle-Junior)
- [Senior](#Senior)
# Intern
Decription: who study in school and work at company at the same time.

**1. Question: There are many game genres. Can you name some games genres?**

<details><summary>Answer</summary>
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

<details><summary>Answer</summary>
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

<details><summary>Answer</summary>
<p>

- FPS index is the acronym for **Frames-per-second** the number of frames displayed per second. Simply put, it measures the number of images that the video card can process per second and display on your screen. The higher the FPS index, the smoother, sharper and less lag the displayed image quality.

</p>
</details>

**4. Question: Describe a game engine.**

<details><summary>Answer</summary>
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

**5. Question: What is 2.5D in Unity.**

<details><summary>Answer</summary>
<p>

- It's basically using 2D physics combinded with 3D graphics.

</p>
</details>

**5. Question: List some popular  games make by Unity?**

<details><summary>Answer</summary>
<p>

- Genshin Impact, Among Us, Pokemon Go, Cup Head, Over Cook, Fall Guys, Heart Stone, ... etc

</p>
</details>

# Fresher
Decription: who graduated and start working at company. Working with Unity less than 1 year. If you have none Unity experience, you should see the questions of intern.

**1. Question: Name some important tab components of Unity 3D.**

<details><summary>Answer</summary>
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

<details><summary>Answer</summary>
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

<details><summary>Answer</summary>
<p>

- Both objects must have a Collider, and one of the objects must also have a Rigidbody.
    
</p>
</details>

**4. Question: What is the order in which OnEnable, Awake, and Start occur during runtime? Which ones are likely to occur repeatedly within the same object cycle?.**

<details><summary>Answer</summary>
<p>

- **Awake** –> **OnEnable** -> **Start**. **OnEnable** can occur repeatedly in the same cycle!
    
</p>
</details>

**5. Question: What difference between stack and queue?**

<details><summary>Answer</summary>
<p>

- **Stacks and queues** are both data structures that organize and manage collections of elements, but they differ in how elements are added and removed.
- **Stack**:
	- **Last In, First Out (LIFO)**: The last element added to the stack is the first one to be removed. Elements are added and removed from the same end, often referred to as the "top" of the stack. Common operations include push (to add an element) and pop (to remove the last-added element).
- **Queue**
	- **First In, First Out (FIFO)**: The first element added to the queue is the first one to be removed. Elements are added at one end (rear or back) and removed from the other end (front). Common operations include enqueue (to add an element) and dequeue (to remove the first-added element).
    
</p>
</details>

**6. Question: Briefly describe the use of prefab.**

<details><summary>Answer</summary>
<p>

- Instantiated when the game is running, prefab is equivalent to a template, making a default configuration for the materials, scripts, and parameters you already have to facilitate future modifications. The content packaged by prefab simplifies the export operation and facilitates team communication.
    
</p>
</details>

**7. Question: What function is used to rotate the object itself ?**

<details><summary>Answer</summary>
<p>

- Transform.Rotate()
    
</p>
</details>

**8. Question: What is a coroutine?**

<details><summary>Answer</summary>
<p>

- While the main thread is running, another piece of logic processing is started at the same time to assist the execution of the current program. In other words, starting a **coroutine** is to start a logic that can be parallel to the program. Can be used to control motion, sequences, and object behavior.
    
</p>
</details>

**9. Question: List some ways to move an object in Unity.**

<details><summary>Answer</summary>
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

<details><summary>Answer</summary>
<p>

- Unity games run on different devices with varying hardware capabilities. If you use fixed values for movement or animations without considering the frame rate, they might appear too fast on a high-performance device and too slow on a low-performance one.
- **Time.deltaTime** represents the time it took to complete the last frame. Multiplying your movement or animation values by **Time.deltaTime** ensures that the speed remains consistent across different frame rates.
- When you use **Time.deltaTime**, your game elements move or animate smoothly regardless of the frame rate. This is crucial for a consistent and enjoyable user experience.
- Unity's physics engine relies on time to simulate realistic interactions between objects. Using **Time.deltaTime** in physics calculations ensures that the behavior of your game's physics remains consistent across various devices.
- For effects that depend on time, such as fading, flashing, or pulsating, using **Time.deltaTime** allows you to control the speed of these effects based on the time elapsed, creating a more dynamic and visually appealing experience.
    
</p>
</details>

**11. Question: What is the difference between material and sharedmaterial in MeshRender?**

<details><summary>Answer</summary>
<p>

- Modifying **sharedMaterial** will change the appearance of all objects using this material, and will also change the material settings stored in the project. Modifying the **material** returned by sharedMaterial is not recommended. If you want to modify the renderer's material, use material instead.

</p>
</details>

**12. Question: Why using pooling object is important? How does it work in Unity?**

<details><summary>Answer</summary>
<p>

- Reusing GameObjects after being destroyed such as artillery shells, fx, etc. costs memory each time they are destroyed and created. Using **Pooling** is understood as just hiding the GameObject, then resetting its position, rotation angle, etc. and displaying it again when used. This helps increase game performance significantly.

</p>
</details>

**13. Question: How to save local data?**

<details><summary>Answer</summary>
<p>

- **PlayerPrefs.**
- **Serialization to Json.**
- **Binary Serialization.**

</p>
</details>

**14. Question: What are layers in unity used for?**

<details><summary>Answer</summary>
<p>

- **Collision Detection**:
  - Layers are often used to control which objects can collide with each other. By assigning GameObjects to specific layers, you can set up collision matrices to define which layers can interact with each other. This allows for fine-grained control over the physics interactions in your game.
- **Raycasting**:
  - When performing raycasts, you can specify which layers the ray should interact with. This is useful for targeting specific types of objects or ignoring others based on their layer assignments.
- **Rendering and Camera Culling**:
  - Layers are used to control which objects are visible to specific cameras. This is essential for optimizing rendering performance. For example, you might have a camera that renders only the UI layer or a specific set of layers for certain visual effects.
- **Audio Occlusion**:
  - Layers can be used to control how audio interacts with different objects. For example, you might want certain objects to block or allow the passage of audio based on their layer assignments.
- **Sorting Order**:
  - In 2D games, layers are used to define the sorting order of sprites. Sprites on higher layers are rendered in front of sprites on lower layers, allowing you to control the visual hierarchy of 2D elements.
- **Organizing the Scene**:
  - Layers help organize the GameObjects in the Unity Editor's Scene view. This makes it easier to select, manipulate, and manage objects within the scene.

</p>
</details>

**15. Question: How to prevent the existing GameObject from being destroyed when change Scene?**

<details><summary>Answer</summary>
<p>

- Add a monobehaviour script to gameobject and use DontDestroyOnLoad function:

```C-Sharp
void Awake()
{
    DontDestroyOnLoad(transform.gameObject);
}
```

</p>
</details>

**16. Question: What is the difference between abstract class and interface?**

<details><summary>Answer</summary>
<p>


- **Abstract classes and interfaces** are both mechanisms in object-oriented programming that allow you to define contracts for classes. However, there are some key differences between them:

- **Method Implementation**:
  - Abstract Class: Can have both abstract (methods without a body) and concrete (methods with a body) methods. Abstract classes can also have fields (variables).
  - Interface: Can only declare abstract methods. In Java, before Java 8, interfaces could not have any method implementations. However, with Java 8, interfaces can have default and static methods with implementations.
- **Multiple Inheritance**:
  - Abstract Class: A class can extend only one abstract class.
  - Interface: A class can implement multiple interfaces. This allows for a form of multiple inheritance in Java and languages with similar features.
- **Constructor**:
  - Abstract Class: Can have a constructor. It is called when an object of the class is instantiated.
  - Interface: Cannot have a constructor. Interfaces do not participate in the instantiation of objects.
- **Access Modifiers**:
  - Abstract Class: Can have access modifiers for its members (public, private, protected, etc.).
  - Interface: All methods in an interface are implicitly public and abstract (before Java 8), and public and abstract (default) or public and static (Java 8 and later).
- **Fields (Variables)**:
  - Abstract Class: Can have instance variables (fields).
  - Interface: Can have only static final variables, which are essentially constants.
- **Usage**:
  - Abstract Class: Used when a common base implementation is needed across multiple classes, and you want to provide a default implementation for some methods.
  - Interface: Used when you want to provide a contract that multiple classes can adhere to, especially when those classes may not share a common base implementation.

</p>
</details>

**17. Question: Explain about enumeration in Unity. Take an example.**

<details><summary>Answer</summary>
<p>

- **Enumeration** commonly referred to as an enum, is a distinct value type that defines a set of named values representing specific states or options. Enums are used to make code more readable and maintainable by providing meaningful names to integral values.
- **For example**: 
```C-Sharp
public enum Direction
{
    North,
    South,
    East,
    West
}
```

</p>
</details>

**18. Question: Name a few Unity packages on the assets store that you know. What is it used for?**

<details><summary>Answer</summary>
<p>

**Some example packages**:
- **TextMesh Pro**:
  - Purpose: It provides advanced text rendering and formatting tools, offering more control and flexibility over Unity's built-in Text component.
- **Cinemachine**:
  - Purpose: Cinemachine is a powerful and customizable camera system for Unity. It simplifies the process of creating dynamic and cinematic camera movements in games.
- **Post Processing Stack**:
  - Purpose: This package enhances the visual quality of your Unity project by adding post-processing effects like ambient occlusion, bloom, color grading, and more.
- **DOTween**:
  - Purpose: DOTween is a fast, efficient, and easy-to-use animation engine for Unity. It allows developers to create smooth and complex animations with a simple syntax.
- **Shader Graph**:
  - Purpose: Shader Graph is a visual tool for creating shaders in Unity without the need for programming. It enables artists and developers to create custom materials and effects through a node-based interface.
- **ProBuilder**:
  - Purpose: ProBuilder is a 3D modeling tool integrated into the Unity editor. It allows developers to create, edit, and prototype 3D models directly within the Unity environment.
- **Rewired**:
  - Purpose: Rewired is a powerful input management system for Unity. It provides a customizable and unified input solution, making it easier to handle various input devices and platforms.
- **Playmaker**:
  - Purpose: Playmaker is a visual scripting tool that allows game designers and developers to create gameplay mechanics and logic without writing code.
- **FinalIK**:
  - Purpose: FinalIK is an inverse kinematics solution for Unity, helping developers implement realistic character animations by simulating the movements of bones in a skeletal hierarchy.
- **EasySave**:
  - Purpose: EasySave is a serialization and data storage solution for Unity. It simplifies the process of saving and loading game data, including player preferences and game progress.

</p>
</details>

**19. Question: What make folder Resources in Unity special?**

<details><summary>Answer</summary>
<p>

- In Unity, folder **Resources** that allows you to load assets at runtime using the Resources.Load method. Assets placed in the "Resources" folder are treated as part of the project's runtime data and can be accessed dynamically.

</p>
</details>

**20. Question: What difference between Update and FixedUpdate?**

<details><summary>Answer</summary>
<p>

- **Update** runs once per frame. **FixedUpdate** can run once, zero, or several times per frame, depending on how many physics frames per second are set in the time settings, and how fast/slow the framerate is.
- It's for this reason that **FixedUpdate** should be used when applying forces, torques, or other physics-related functions - because you know it will be executed exactly in sync with the physics engine itself. Whereas **Update()** can vary out of step with the physics engine, either faster or slower, depending on how much of a load the graphics are putting on the rendering engine at any given time, which - if used for physics - would give correspondingly variant physical effects!

</p>
</details>

# Junior
Decription: who have 1-5 years work with Unity.

**1. Question: There are some special folder names in Unity. What are there?**

<details><summary>Answer</summary>
<p>

- **Assets**:
  - The root folder of your Unity project, containing all assets.
- **Editor**:
  - Scripts placed in this folder are considered Editor scripts and will only be included in the Unity Editor build, not in the final game or application.
- **Resources**:
  - Assets placed in this folder can be loaded at runtime using Resources.Load.
- **Plugins**:
  - Used for native plugins that extend Unity's functionality using native code (e.g., DLLs).
- **Standard Assets**:
  - A folder that Unity recognizes for its Standard Assets packages.
- **StreamingAssets**:
  - Assets placed here are included in the build as-is and can be accessed at runtime.
- **Gizmos**:
  - Contains Gizmo icons that can be used in the scene view for custom visualization.
- **Editor Default Resources**:
  - Stores default resources used by the Unity Editor.

</p>
</details>

**2. Question: Which of the following definitions is incorrect?**
1. If the variable is an **integer**, the default value of the variable is 0.
2. If the variable is a **reference type**, the default value of the variable is null.
3. If the variable is a **string**, the default value of the variable is an empty string.
4. If the variable is a **boolean**, the default value of the variable is false.

<details><summary>Answer</summary>
<p>

- The correct answer to your question is **Statement 3**.
  - Including C# and many others, the default value for a string variable is **null**, not an empty string.

</p>
</details>

**3. Question:Seven: Briefly describe the role of quaternion and the advantages of quaternion over Euler angles?**

<details><summary>Answer</summary>
<p>

- **Quaternions** are used to represent rotations. The advantages of relative **Euler angles**: it can perform incremental rotation, avoid universal lock, and there are two ways of expressing a given orientation, which are mutually negative (Euler angles have countless ways of expression)

</p>
</details>

**4. Question: What is the difference between material and sharedmaterial in MeshRender?**

<details><summary>Answer</summary>
<p>

- Modifying **sharedMaterial** will change the appearance of all objects using this material, and will also change the material settings stored in the project. Modifying the **material** returned by sharedMaterial is not recommended. If you want to modify the renderer's material, use material instead.

</p>
</details>

**5. Question: Unity provides several light sources. What are they?**

<details><summary>Answer</summary>
<p>

- **Directional Light**:
  - Simulates distant light sources such as the sun.
  - Illuminates all objects in the scene with parallel light rays.
- **Point Light**:
  - Emits light in all directions from a specific point in space.
  - Commonly used to simulate light bulbs or other localized light sources.
- **Spotlight**:
  - Emits light in a cone shape from a specific point in space.
  - Can be used to simulate flashlights or focused light sources.
- **Area Light**:
  - Represents a rectangular light source.
  - Useful for simulating large light sources, such as a window or a screen.
- **Light Probe**:
  - Used for dynamic global illumination.
  - Captures and stores lighting information at specific points in the scene.
- **Reflection Probe**:
  - Captures a 360-degree view of the scene's surroundings.
  - Used for calculating reflections and lighting for reflective surfaces.
- **Real-time Global Illumination (GI)**:
  - Unity also provides a real-time global illumination system that allows dynamic lighting changes to affect the scene's lighting in real-time.

</p>
</details>

**6. Question: In which system function are physical updates generally placed?**

<details><summary>Answer</summary>
<p>

- **FixedUpdate** is executed once every fixed frame drawing. Different from Update, FixedUpdate is executed at the rendering frame. If your rendering efficiency is low, the number of FixedUpdate calls will decrease accordingly.
- **FixedUpdate** is more suitable for physics engine calculations because it is related to the rendering of each frame. Update is more suitable for control.

</p>
</details>

**7. Question: What is LOD and what are its advantages and disadvantages?**

<details><summary>Answer</summary>
<p>

- **LOD (Level of detail)** is the most commonly used game optimization technology. It determines the resource allocation of object rendering according to the position and importance of the model, reducing the number of faces and details of non-important objects, thereby achieving highly efficient rendering operations.

</p>
</details>

**8. Question:What is dynamic batch batching? What is the difference from static batching?**

<details><summary>Answer</summary>
<p>

- If dynamic objects share the same material, Unity will automatically batch these objects. **Dynamic batch** processing operations are completed automatically and do not require you to perform additional operations.
- The difference: everything in **dynamic batch** processing is automatic, no operations are required, and objects can be moved, but there are many restrictions. **Static batch** processing: high degree of freedom, few restrictions, disadvantages may occupy more memory, and all objects after static batch processing can no longer be moved.

</p>
</details>

**9. Question: What difference between heap and stack memory in C#?**

<details><summary>Answer</summary>
<p>

- **Stack**:
  - **Purpose**: The stack in C# is used for managing the execution of methods and storing local variables.
  - **Memory Allocation**: Memory for variables on the stack is managed automatically by the compiler during runtime.
  - **Lifetime**: Variables on the stack have a limited lifetime, tied to the scope of a method or function.
  - **Size**: The stack has a limited size, and memory allocation is fast due to a simple pointer adjustment.
  - **Example**: Variables like primitive data types, references, and local variables are stored on the stack.
csharp
```
int localVar = 42; // localVar is on the stack
```
- **Heap**:
  - **Purpose**: The heap in C# is used for dynamic memory allocation, where you manually allocate and deallocate memory for objects.
  - **Memory Allocation**: Memory on the heap is managed explicitly by the programmer in C# using operators like new and delete (or using constructors and destructors in C++).
  - **Lifetime**: Variables on the heap can have a longer lifetime than stack variables. They persist until explicitly deallocated.
  - **Size**: The heap can grow dynamically based on the needs of your C# application.
  - **Example**: Objects like classes, arrays, and large data structures are allocated on the heap.
csharp
```
class MyClass {
    // Class members
}

MyClass myObject = new MyClass(); // myObject is on the heap
```

</p>
</details>

**10. Question: What is the term SOLID in Object-Oriented Programming?**

<details><summary>Answer</summary>
<p>

In the context of **Object-Oriented Programming** (OOP), the term "**solid**" often refers to the SOLID principles. SOLID is an acronym that represents a set of design principles aimed at creating more maintainable, scalable, and flexible software. Each letter in SOLID stands for a specific principle:

- **S - Single Responsibility Principle (SRP)**: A class should have only one reason to change, meaning that it should have only one responsibility or job.
- **O - Open/Closed Principle (OCP)**: Software entities (classes, modules, functions, etc.) should be open for extension but closed for modification. This encourages the use of inheritance and polymorphism to extend behavior without modifying existing code.
- **L - Liskov Substitution Principle (LSP)**: Subtypes must be substitutable for their base types without altering the correctness of the program. In other words, objects of a superclass should be replaceable with objects of a subclass without affecting the functionality of the program.
- **I - Interface Segregation Principle (ISP)**: A class should not be forced to implement interfaces it does not use. This principle promotes creating specific, smaller interfaces rather than a large, general one.
- **D - Dependency Inversion Principle (DIP)**: High-level modules should not depend on low-level modules. Both should depend on abstractions. Additionally, abstractions should not depend on details; details should depend on abstractions. This encourages the use of dependency injection and inversion of control.

</p>
</details>

**11. When should you use array and when should you use list?**

<details><summary>Answer</summary>
<p>

- Use an Array when:
  - **Fixed Size**: If you know the size of your collection won't change, or if it's beneficial to have a fixed-size collection, then an array may be more suitable.
  - **Performance**: Arrays can be more performant in terms of access time, especially for large collections, because elements are stored in contiguous memory.
  - **Memory Efficiency**: If memory efficiency is critical, and you can determine the maximum size of your collection in advance, an array may be more memory-efficient compared to a list.
  - **Static Type**: If you need a collection of elements of a specific type, and that type won't change, arrays are statically typed and might be a better fit.
- Use a List when:
  - **Dynamic Size**: If the size of your collection can change during runtime, or if you need a collection that can grow or shrink dynamically, a list is more appropriate.
  - **Ease of Use**: Lists provide more convenience and flexibility in terms of adding, removing, and manipulating elements. They have built-in methods for various operations.
  - **Unknown Size**: If you don't know the size of your collection in advance or if it can vary, a list allows you to add elements without worrying about preallocating a fixed size.
  - **Dynamic Type**: If your collection needs to store elements of different types or if the type of elements can change, a list (specifically List<T> in C#) is dynamic and can handle this scenario.

</p>
</details>

**12. Question: Talk about what you know about easing in animation. Give some examples in Unity**

<details><summary>Answer</summary>
<p>

- In animation, **easing** is a technique used to control the acceleration or deceleration of an animated property over time, creating more natural and visually pleasing motion. The goal is to make animations appear smoother and more lifelike by adjusting the speed of movement during different phases of the animation.
- Some examples of easing animation: clicking button, moving object, make bounce effect, etc ...

</p>
</details>

**13. Question: What is the return type of ```Predicate<T>()```?**

<details><summary>Answer</summary>
<p>

- **Boolean**

</p>
</details>

**14. Question: Which of the following examples will run faster?**

1. **1000 GameObjects**, each with a MonoBehaviour implementing the Update callback. <br>
2. **One GameObject** with one MonoBehaviour with an **Array of 1000 classes**, each implementing a custom Update() callback?

<details><summary>Answer</summary>
<p>
	
- **Statement 2** is corrected.
  - **The Update callback** is called using a C# **Reflection**, which is significantly slower than calling a function directly. In our example, **1000 GameObjects** each with a MonoBehaviour means **1000 Reflection** calls per frame.
  - Creating **one MonoBehaviour** with one **Update**, and using this single callback to Update a given number of elements, is a lot faster, due to the direct access to the method.
    
</p>
</details>

**15. Question: What is the purpose of using unity' physic materials components?**

<details><summary>Answer</summary>
<p>

- The Unity **Physics Material** component is used to define the physical properties of an object, such as its **friction** and **bounciness**.
- It allows developers to **fine-tune** the interactions between different objects in a scene, such as when they collide with each other or when they interact with otherphysics-based components.
- This allows for more **realistic physics simulation** and better control over the physical behavior of objects in a Unity game.

</p>
</details>

**16. Question: What is the use of collision matrix in Unity?**

<details><summary>Answer</summary>
<p>

- For each new layer, a new column and roware added on the **collision matrix**. This matrix is responsible for defining interactions between layers.

</p>
</details>

**17. Question: Explain why Time.deltatime should be used To make things that depend on time operate correctly?**

<details><summary>Answer</summary>
<p>

- Real time applications, such as games, have a variable FPS. They sometimes run at 60FPS, or when suffering slowdowns, they will run on 40FPS or less.
- If you want to change a value from A to B in 1.0 seconds you can't simply increase A by B-A between two frames because frames can run fast or slow, so one frame can have different durations.
- The way to correct this is to measure the time taken from frame X to X+1 and increment A, leveraging this change with the frame duration deltaTime by doing A += (B-A) * Delta Time.
- When the accumulated DeltaTime reaches 1.0 second, A will have assumed B value.

</p>
</details>

**18. Question: Difference between Update, Fixed Update and Late Update?**

<details><summary>Answer</summary>
<p>

- **Update()** is called on every Frame, regardless of time passed since last frame
  - Good for Movement, InputControl etc. (most of the time you'll use Update)
  - Usually you will use Time.DeltaTime to take passed time into account (e.g. for GameObject Translations)
- **LateUpdate()** is called after all Update() methods are processed
  - So e.g. for the camera that follows your character it's good to Update after it has moved
- **Fixed Update()** is called by the physics engine in fixed intervals (that can beset in the Options)

</p>
</details>

**19. Question: What is the use of Occlusion Culling?**

<details><summary>Answer</summary>
<p>

- **Occlusion culling** is a process which prevents Unity from performing rendering calculations for GameObjects that are completely hidden from view (occluded) by other GameObjects.
- Every frame, **Cameras** perform culling operations that examine the **Renderers** in the Scene and exclude (cull) those that do not need to be drawn. By default, Cameras perform frustum culling, which excludes all Renderers that do not fall within the Camera's view frustum.

</p>
</details>

**20. Question: Explain the LOD mechanism?**

<details><summary>Answer</summary>
<p>

- The **Level of Detail (LOD)** mechanism in computer graphics optimizes rendering performance by dynamically adjusting the complexity of 3D objects based on their distance from the viewer. Objects have multiple detail levels (LODs), and the mechanism switches between them as needed. This process improves rendering efficiency by using higher LODs for closer objects and lower LODs for those farther away, reducing the number of processed vertices. LOD transitions are often implemented smoothly to avoid visual artifacts. The manual or automated creation of LODs allows for adaptive management, enhancing performance in real-time applications like games. Overall, LOD strikes a balance between visual quality and computational efficiency in 3D rendering.

</p>
</details>

**21. Question: How do you understand ragdolls in the game? Let's talk about the principles of setting up a character with a ragdoll.**

<details><summary>Answer</summary>
<p>

- In the context of video games, a **ragdoll** refers to a physics-based simulation of a character's body movement when it is subjected to external forces, such as collisions or explosions. This simulation is used to create more realistic and dynamic character animations, especially in situations where predefined animations might not be appropriate or feasible.
- To set up a **ragdoll**, you need to attach **rigidbodies** and **colliders** to the main parts of the character's body. Afterward, you will use **joints** (character joint, hinge joint, etc.) to create articulations for these parts.

</p>
</details>

**22. Question: **

<details><summary>Answer</summary>
<p>

- 

</p>
</details>

**23. Question: **

<details><summary>Answer</summary>
<p>

- 

</p>
</details>

**24. Question: **

<details><summary>Answer</summary>
<p>

- 

</p>
</details>

**25. Question: **

<details><summary>Answer</summary>
<p>

- 

</p>
</details>

**26. Question: **

<details><summary>Answer</summary>
<p>

- 

</p>
</details>

**27. Question: **

<details><summary>Answer</summary>
<p>

- 

</p>
</details>

**28. Question: **

<details><summary>Answer</summary>
<p>

- 

</p>
</details>

**29. Question: **

<details><summary>Answer</summary>
<p>

- 

</p>
</details>

**30. Question: **

<details><summary>Answer</summary>
<p>

- 

</p>
</details>

# Senior
Decription: practically who have more than 5 years working with Unity and base on knowledge.

**1. Question: How does GPU work?**

<details><summary>Answer</summary>
<p>

- In short, the GPU graphics (processing) pipeline completes the following work: (not necessarily in the following order).
- **Vertex processing**: At this stage, the GPU reads the vertex data describing the appearance of the 3D graphics and determines the shape and positional relationship of the 3D graphics based on the vertex data, establishing the skeleton of the 3D graphics. In GPUs that support the DX8 and DX9 specifications, these tasks are completed by the hardware-implemented Vertex Shader (fixed-point shader).
- **Rasterization calculation**: The image actually displayed on the monitor is composed of pixels. We need to convert the points and lines on the graphics generated above into the corresponding pixels through a certain algorithm. The process of converting a vector graphic into a series of pixels is called rasterization. For example, a mathematical representation of a diagonal line segment is eventually converted into a staircase-like continuous pixel point.
- **Texture mapping**: The polygons generated by the vertex unit only constitute the outline of the 3D object, while texture mapping completes the mapping of multi-deformed surfaces. In layman's terms, it means pasting the corresponding pictures on the polygonal surface, thereby Generate "realistic" graphics. TMU (Texture mapping unit) is used to complete this work.
- **Pixel processing**: In this stage (during the rasterization of each pixel) the GPU completes the calculations and processing of the pixels to determine the final properties of each pixel. In GPUs that support the DX8 and DX9 specifications, these tasks are completed by the hardware-implemented Pixel Shader.
- Final output: **The ROP** (rasterization engine) finally completes the output of pixels. After one frame is rendered, it is sent to the video memory frame buffer.
- Summary: Generally speaking, the work of the GPU is to complete the generation of 3D graphics, map the graphics to the corresponding pixels, calculate each pixel to determine the final color and complete the output.

</p>
</details>

**2. Question: Write down the calculation formula of diffuse in lighting calculation?**

<details><summary>Answer</summary>
<p>

- diffuse = Kd x colorLight x max(N*L,0); Kd is the diffuse reflection coefficient, colorLight is the color of the light, N is the unit normal vector, L is the unit vector pointing from the point to the light source, where N is dot multiplied by L, if If the result is less than or equal to 0, the diffuse reflection is 0.

</p>
</details>

**3. Question: What are the various levels of the TCP/IP protocol stack and their respective functions?**

<details><summary>Answer</summary>
<p>

- **Network interface layer**: This is the lowest layer of the protocol stack, corresponding to the physical layer and data link layer of OSI. It mainly completes the actual sending and receiving of data frames.
- **Network layer**: handles the activities of packets in the network, such as routing and forwarding. This layer mainly includes IP protocol, ARP, ICMP protocol, etc.
- **Transport layer**: The main function is to provide communication between applications. This layer is mainly TCP/UDP protocol.
- **Application layer**: used to handle specific applications, and provides different protocols for different applications, such as the FTP protocol used for file transfer, SMTP used for sending emails, etc.

</p>
</details>

**4. Question: **

<details><summary>Answer</summary>
<p>



</p>
</details>

**5. Question: **

<details><summary>Answer</summary>
<p>



</p>
</details>

**6. Question: **

<details><summary>Answer</summary>
<p>



</p>
</details>

**7. Question: **

<details><summary>Answer</summary>
<p>



</p>
</details>

**8. Question: **

<details><summary>Answer</summary>
<p>



</p>
</details

 **9. Question: **

<details><summary>Answer</summary>
<p>



</p>
</details>

**10. Question: **

<details><summary>Answer</summary>
<p>



</p>
</details>

## LICENSE
Open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).

## You can support me via

<a href="https://www.buymeacoffee.com/HoangVanThu">
  <img src="https://www.the3rdsequence.com/texturedb/images/donate/buymeacoffee.svg" width="200" height="47"/>
</a>
