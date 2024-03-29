# Digital-Prototyping-Interactive-Prototype-3


Background information of the projects(Problem space): Most of us have experienced long distance driving, and we know long distance driving can drain your energy easily. The longer you drive, the more fatigue you can feel. Fatigue driving can affect a driver's concentration, which can lead to traffic accidents easily. Fatigue driving is a big issue for everyone, and we need to treat it seriously.To resolve this problem, developing a driver alert system is needed. The driver alert system needs to collect some input data. Afterwards, the system needs to process the input data and provide corresponding feedback to the driver. The system needs to analyze the data precisely, and provide the most suitable feedback that fits the driver’s current condition. The details of the feedback mechanisms are explained within the statement of delivery document. By having the driver alert system, drivers can stay awake and focus on the road when they drive, so that they can keep themself safe.


Introduction of the Interactive prototype projects: The background information above briefly explains the problem we want to solve and the potential solution. In the interactive prototype projects, the goal is not building the actual product and deploying the system to the public. The focus of the interactive prototype projects are treating the problem and the  solution mentioned above as the concept, and I need to explore the challenge/aspect within the concept afterwards. After the challenge/aspect is defined, the interactive prototype project will enter its second stage, which is the prototype development.

The prototype development has two parts, which are the hardware and the software. For the hardware, I used the Adafruit Circuit Playground as the physical component, which is used for the physical interaction between the system and the users. For the software, I used Unity to develop the software prototype. The hardware component will communicate with the software prototype constantly. The digital prototype is specifically designed for the challenge/aspect that we defined in the previous stage. Once the digital prototype development is completed, the testing session will begin.

The final stage is the testing session. In the testing session, I will explain the concept to my testers. Afterwards, they will perform some operations with the digital prototype. I will conduct various evaluations throughout the testing session, for instance observations and interviews. These evaluations can give me useful insights on the challenges/aspects that I defined in the earlier stage, so that I will have a clear direction in my future developments. 

The interactive prototype project has three digital prototypes. Each of these prototypes is corresponding to a specific challenge/aspect on the problem space we mentioned earlier.


The Prototype3_Coding_Files_link.txt contains the Arduino codes and the Unity codes.

The statement of delivery contains the documentation of the digital prototype and the testing session information.

The ReadMe.md provides background information and explains the flows of the interactive prototype. In addition, it will have a detailed explanation on the target challenge/aspect, and its digital prototype.



Prototype 3: In prototype 3, I focus on the “high alert” mode of the driver alert system. When “high alert” mode is active, it will trigger the aggressive sound feedback and the vibration feedback at the same time. The aggressive sound feedback can be presented in different ways. In prototype 3, exploring the aggressive sound feedback in the “high alert mode” is the focus. Sound feedback can be presented in different forms, sound pitch is one of the most common aspects that can differentiate different sound effects. The research focus in prototype 3 is “Does random sound pitch provide better alertness when compared with constant sound pitch effects?” Random sound pitch means the sound pitch can change randomly while the alarm rings. 

Constant sound pitch means the pitch never changes, it will maintain the same pitch all the time.
To test which pitch pattern is better, I created prototype 3. Prototype 3 is like a reaction test. The circuit playground is being programmed, so it has 2 sound pitch patterns. The first pattern is the constant sound pitch pattern, and the second pattern is the random pitch pattern. 

When the construction of the prototype is completed, it will enter the testing session. During the testing session, the testers need to focus on the screen, and press on the corresponding button accordingly. When the button is being pressed successfully, the timer will stop, which is the reaction time. During the reaction test game, each sound pitch pattern will be played in the background. By following this process, we will know how different sound pitch patterns affect testers response time. From the result, we can infer which pattern will produce a  shorter reaction time in the driver alert system concept, so our challenge can be solved.

Observation is one of the evaluation approaches, and it will happen while testers are working with the prototype. When testers completed all the testing rounds with the prototype, interviewing sessions will begin. I will ask some open-ended questions which can help me to understand the challenge/aspect better. 

After the completion of the testing session, I realized most testers believe random sound pitch patterns is a more effective approach, since they think the alert level is higher and stronger. On the other hand, the average reaction time on the random sound pitch pattern is also shorter, which indicates humans will react faster under this pattern of sound feedback. There are various ways to make the current design better, for instance, I can create more sound pitch patterns, as the quantitative and qualitative data shows variance on sound pitch can enhance the system efficiencies. These useful insights help me to find a proper solution for the challenge that I raised earlier, so that I have a clear direction in my future improvements. 


![image(1)](https://github.com/jefjefhui/Digital-Prototyping-Interactive-Prototype-3/assets/73283123/5290de4a-4442-417b-a803-ad60a28004f8)

The image above is the initial Unity game screen.

![image(2)](https://github.com/jefjefhui/Digital-Prototyping-Interactive-Prototype-3/assets/73283123/5b1d1eb6-cd6c-4093-8a83-93fa6d7085a5)

The image above shows one of the rectangles changes to green at a random time.

![image(3)](https://github.com/jefjefhui/Digital-Prototyping-Interactive-Prototype-3/assets/73283123/835ef10c-f5ea-4746-8347-5a4f1d5496b5)

The image above shows if the tester pressed the correct aluminum button, the timer stops and show the reaction time.

![images(4)](https://github.com/jefjefhui/Digital-Prototyping-Interactive-Prototype-3/assets/73283123/efb35288-6691-42dc-ab1e-c9a69ba1d882)

The image above shows if the correct button press is not detected, it would show the screen above.

![images(5)](https://github.com/jefjefhui/Digital-Prototyping-Interactive-Prototype-3/assets/73283123/7e187ef1-7dde-4d36-a8e9-492897b9b3f1)

In the image above, as mentioned before, there are 2 patterns to test. When pattern one is enabled, it will show the text "pattern one is activated".

![image(6)](https://github.com/jefjefhui/Digital-Prototyping-Interactive-Prototype-3/assets/73283123/7442f521-70a6-4ce8-99a5-0b661119ab4f)

The image above shows when pattern 2 is activiated, it will show the text "pattern two is activated".

![image(7)](https://github.com/jefjefhui/Digital-Prototyping-Interactive-Prototype-3/assets/73283123/cbf8dc96-a59b-475b-babe-d56842d6819e)

The image above shows this is the circuit playground. There are 4 self-made aluminum buttons, and they are attached on the capacitive touch-sensitive pads on the circuit playground.

![image(8)](https://github.com/jefjefhui/Digital-Prototyping-Interactive-Prototype-3/assets/73283123/94c48317-7473-428c-afe7-6c50c3d39888)

In the image above, this interaction diagram shows how the prototype works. It explains from the starting point to the ending point.

![image(9)](https://github.com/jefjefhui/Digital-Prototyping-Interactive-Prototype-3/assets/73283123/d57d4ff0-85a0-41d0-a00f-5e7637976176)

The image above shows how pattern one (constant sound pitches) looks like in a graph.

![image(10)](https://github.com/jefjefhui/Digital-Prototyping-Interactive-Prototype-3/assets/73283123/6edbb511-0e3a-47b2-8362-6c57e36387df)

The image above is how pattern two (random sound pitches) looks like in a graph.











Detailed information of prototype 3,background information , testing session, and key takeaways can be found in the statement of delivery. 

The following link shows the prototype 3 video, which demonstrates how the  interactive prototype 3 works. Video Link: https://drive.google.com/file/d/1HteMmmTabVaYpyyC_8UEcBKJ6UJA9-P7/view
