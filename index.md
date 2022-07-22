# Face Recognition Door Lock
A camera connected to a Raspberypi captures the user's face. It uploads the image to an API (Amazon Rekognition) which uses facial recognition to determine whether to open the lock. If the open response is sent back the arduino toggles a motor which opens the lock.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Caden | Junipero Serra Highschool | Mechanical Engineering | Incoming Sophmore

[![milestone3](https://user-images.githubusercontent.com/86168345/180489093-7b29940c-cd36-4a6b-9c48-71a261431532.jpg)](https://www.youtube.com/watch?v=hZv6VcnZmms&ab_channel=BlueStampEng)

  
# Final Milestone
My final milestone was the improve the user interface with my project. At first I just added a button which would allow someone from inside to open the lock, since there was no function for leaving (and thus violating many fire safety regulations). This was straight forward, I just assigned another button using the RPi GPIO module and then copied the open function directly, skipping the face id part of the opening process. I then decide to build an entire model door for my lock. I used pieces of scrap wood from other projects to build a frame and door. I had to learn fusion 360 to create some custom 3D mounts for my raspi as well as a blocker for the bolt.

[![milestone2](https://user-images.githubusercontent.com/86168345/180486909-497ad9bc-947a-477a-96bc-8ce7a927906d.jpg)](https://www.youtube.com/watch?v=sduC3FaY9u0&ab_channel=BlueStampEng)
![block1_ioWGCtJDGN](https://user-images.githubusercontent.com/86168345/180491421-d20d10cb-7ce7-4a95-aacc-39eae6ca416c.jpg)

# Second Milestone
My second milestone was finishing the functionality of my lock. I first SSH my Raspberry Pi's terminal to my laptop's command prompt. I could then use the nano text editor to write python code onto the raspi. On my laptop I set up AWS, or amazon web services. I create a s3 bucket, or a storage file on the cloud aswell as a dynamodb table. I then sent photos of my face to the table. On the Raspi, I connected a button the GPIO. I then programmed it so that when I pressed the button it would execute button_callback(), a function. Under this function are a series of more functions which take a photo with the camera module and sends the image to the s3 bucket. Amazon's Rekognition API would compare the image and send a response. If the face matches a "open" string is sent to the arduino. If not, an email is sent to me with an imagine attached of the unknown face.

[![Thumbnail2](https://user-images.githubusercontent.com/86168345/178777770-80836957-bef0-45f8-8927-e1482bdc6598.jpg)](https://www.youtube.com/watch?v=VKctLer_IKs&ab_channel=BlueStampEng)
  
![image](https://user-images.githubusercontent.com/86168345/175608678-4d140eff-fca2-440a-9540-0eb22442cb78.png)

My first milestone was to complete the mechanical assembly of the lock and enable the arduino to open and close it. I first had to put together the lock. Then I downloaded the Arduino IDE on my laptop. I then connected the servo motor female jumper cable to a male - male jumper cable. I connected the motor to the 5 volt, ground, and pin 9 digital IO. I then programmed the arduino in C++ to rotate the servo motor upon receiving a string.

[![Thumbnail1](https://user-images.githubusercontent.com/86168345/174659342-bbe59611-2fd2-44f0-a97b-827f0d77fddb.jpg)
](https://www.youtube.com/watch?v=KoR6Z2y8akA&ab_channel=BlueStampEng)

# Starter Project

My starter project the useless machine was elegantly simple. It doesn't use any computing chips or controllers just logic from a simple circuit. The useless machine is a box with a conspicuous switch. When the switch is toggled an arm emerges from a door and closes the switch. The arm then returns. I first soldered the switch, terminals, lights, resisters, and a small pressure switch to a printed circuit board. I hooked the PCB to the motor and a battery pack. Then I constructed the box surrounding the internal components. When I first started I assumed there would need to a seperate mechanism to open the door but the arm itself pushes it open.

