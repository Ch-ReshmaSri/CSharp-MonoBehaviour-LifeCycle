# CSharp-MonoBehaviour-LifeCycle

## Overview
Unity's MonoBehaviour class is the backbone of most scripts in Unity, providing key lifecycle methods to manage a GameObject's behavior. This repository demonstrates the sequence of these methods and offers examples of how to effectively use them in your Unity projects.

## Features
1. Complete Lifecycle Coverage: All major MonoBehaviour methods explained and demonstrated.
2. Practical Examples: Usage of lifecycle methods in real-world scenarios.
3. Well-Commented Code: Clear and concise comments to make learning easier.
4. Debug Logging: See the execution order of methods in the Unity Console.

## MonoBehaviour Lifecycle Methods
### Initialization Phase
1. Awake()
- Called when the script instance is being loaded.
- Ideal for initializing variables and references.
2. OnEnable()
- Called each time the object is enabled.
3. Start()
- Called before the first frame update, after Awake.
- Use it for initialization that relies on other objects.
### Runtime Phase
4. Update()
- Called once per frame.
- Best for game logic and frame-dependent tasks.
5. FixedUpdate()
- Called on a fixed time interval.
- Used for physics-related updates.

## How to Use
1. Set Up in Unity:
- Create a new Unity project or use an existing one.
- Attach the AutoDestroyText script to a GameObject that has a TextMeshProUGUI component.
- Adjust the AutoDestroyTime variable to set how long the text remains before being destroyed.
2. Customization:
- Modify the AutoDestroyTime to control how long the object stays in the scene.
- You can attach this script to any GameObject with a TextMeshProUGUI component to automatically display and destroy text after the specified time.

## Conclusion
This script provides an example of how Unity's MonoBehaviour lifecycle methods can be used to manage timers, update UI elements, and destroy GameObjects. It demonstrates a basic, useful pattern for managing timed objects in Unity.
