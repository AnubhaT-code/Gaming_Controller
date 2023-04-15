
EE381A: Project Topic : Gaming Controller


Section: A										Table No.: 4 

Group Members: Barkha Agrawal - 200263; Anubha Tripathi - 200163; Antara Mandal - 200158



Q1. What problem are you trying to solve and why is it important/interesting ?
 
Making a hardware controller for playing mobile games can solve the problem of limited control options available on mobile devices. Touchscreen controls can be imprecise and difficult to use, especially for games that require quick reflexes and precision.
A hardware controller can provide a more familiar and intuitive gaming experience, similar to using a gamepad or joystick on a console or PC. This can make it easier for gamers to control their characters and interact with the game world, leading to a more enjoyable and immersive gaming experience.
One potential problem that a hardware-controlled mobile game setup could solve is the limited physical interactivity of mobile games. Many mobile games rely solely on touch or tilt controls, which can feel repetitive and lack the tactile feedback that physical buttons and switches can provide. By incorporating hardware controls into mobile gaming, players can have a more immersive and engaging experience that feels more like traditional console gaming.
Moreover, some gamers may prefer using a hardware controller due to physical limitations such as hand or finger dexterity issues, making it a more accessible option for them.
From a business perspective, creating a hardware controller for mobile gaming can also be a way for companies to differentiate their products in a crowded market, and potentially attract more customers by offering a unique and enhanced gaming experience.
Overall, a hardware controller for mobile games can improve gameplay by  offering a more engaging and interactive mobile gaming experience. It can increase accessibility, and provide a competitive edge in the mobile gaming market, making it an important and interesting development in the industry.



Q2. What are the existing solutions. Describe a few of them and list any shortcomings in them. Is your solution approach unique in some way?

There are several existing solutions for hardware controllers for mobile gaming. Here are a few examples:
GameSir F1 Mobile Joystick: This is a small joystick that attaches to the screen of the mobile device and provides a physical joystick-like control for mobile gaming. The joystick is small and portable, making it easy to carry around, but it may not be suitable for all types of games, as it requires a flat surface to attach to and may block part of the screen.
SteelSeries Stratus Duo: This is a wireless gamepad that can be used for mobile gaming as well as PC gaming. It connects to the mobile device via Bluetooth and provides a more traditional gamepad experience, with buttons, triggers, and joysticks. The SteelSeries Stratus Duo is more versatile than a joystick and can be used with a wider range of games, but it is bulkier and less portable.
Razer Kishi: This is a gamepad that attaches to the sides of the mobile device, effectively turning it into a handheld gaming console. The Razer Kishi provides a very immersive gaming experience and allows for precise control, but it is not compatible with all mobile devices and can be expensive.
GameSir X2 Bluetooth Mobile Gaming Controller: This is a physical controller that attaches to the sides of a smartphone and connects via Bluetooth. It features a joystick, buttons, and triggers for a more console-like gaming experience. However, it can only be used with smartphones that are compatible with Bluetooth controllers and its size may make it less portable.
While these solutions offer some benefits for mobile gaming, they also have some shortcomings, such as limited compatibility with certain devices and games, a lack of portability, and a high price point.
We wanted to develop a hardware-controlled mobile game setup that is more customizable or modular, allowing users to choose the specific controls and interfaces that work best for their individual gaming preferences. We also wished to create a solution that incorporates other technologies, such as virtual or augmented reality, to create an even more immersive gaming experience.
Our approach would be to create a controller that is customizable and modular, allowing users to swap out components and customize their controller to suit their specific gaming needs. For example, users could choose different button layouts, joysticks, and triggers, and swap them out as needed. This would make the controller more versatile and adaptable to different types of games and play styles. Additionally, the controller could have a built-in battery pack to extend the battery life of the mobile device while gaming, and it could be designed to be lightweight and portable for on-the-go gaming.


Q3. What resources do you require for completing the project? Give a breakup of tasks that you need to accomplish week by week to complete the project.

Tentative list of the components required:
Arduino Nano v3.0 CH340
Bluetooth Module HC05
 IR LED & Photo diode 
ESP8266MOD Wifi Module
Remote controllers
Breadboard
LED
Capacitors
Resistors

Timeline:
Week1: Idea Discussion, possible modifications on the idea and Collection of Components
Week2: Work on the assembly of all the circuit components and encoding the ICs
Week3: Assembly of all the components to make a final running model 

Programmed Arduino Nano connected with IR sensor along with a remote control


Implementation Details:
In this project, we worked on integrating hardware with software. We made a game having some controls which we made to work using remote control codes. The GUI of the game is made using Python. When a remote is pressed, hex code corresponding to that particular key pressed is made to print on the serial monitor of the arduino IDE. Using a pyserial library , we established a communication between the IR sensor based remote control and the python GUI of the game we made. The hex code is made to pass through a condition check in python code which makes it perform a particular event corresponding to that particular hex code. This way game controls are made to work to play the game.  


Results and Discussions:
We were successful in establishing connections between hardware devices such as IR sensor remote control and software such as python GUI. We understood about NEC protocols of the keys in a particular remote control. This way we have been able to develop a good understanding of how a basic hardware device of day to day application actually works. 

Codes and other details:
https://github.com/AnubhaT-code/Gaming_Controller.git

Video demonstration:
https://drive.google.com/drive/folders/1LvlYksRRqvlwuLfTfY9xGnccLkH5gyMK?usp=sharing

