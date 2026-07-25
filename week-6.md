<link rel="stylesheet" href="style.css">

# Week 6 – User-Centered Design and Quick Prototyping  
**Focus:** Experimenting with triggers, sensors, and interfaces  

---

## Sunday  
I received my Week 6 assignment, which focused on making prototypes and testing them with sensors. To start, I researched various prototyping concepts and came up with an idea for an image-matching feature: visitors can take or upload a photo, and the system will display related artworks from the museum. For this, I looked into how different museums handle interactive features and explored concepts on Google Arts and Culture before beginning work on a rough prototype.  

---

## Monday  
I had a meeting with my supervisor, who explained the Raspberry Pi and how we would use sensors for our assignment. My colleague Jillian and I started by experimenting with an ultrasonic sensor. We watched tutorial videos, but it didn’t work as expected. We then switched to working with card IDs using an RFID reader and a Raspberry Pi 4, which we successfully got working.  


<img width="508"  alt="image" src="https://github.com/user-attachments/assets/36f45a73-d780-403a-beb6-d38d8b804eed" />


<img width="797"  alt="image" src="https://github.com/user-attachments/assets/72c0733f-9590-409e-aed5-67350e5dbdd7" />



## Tuesday  
We resumed working with the Raspberry Pi and its sensors. Our task was to code the system so it could detect the cards included in the kit. To begin, we prepared the microSD card by writing the Raspberry Pi OS image onto it. Initially, it did not work, so we investigated possible causes while also setting up the display screen. After some troubleshooting, we managed to get the screen working, but I had to rewrite the microSD card again. Once the keyboard, mouse, and screen were connected, the Raspberry Pi was fully operational.  

We then started coding, but the system was unable to read the card. After troubleshooting, we discovered the issue was incorrect wiring. Once fixed, the setup worked correctly, and we were able to read the card successfully.  


<img width="419"  alt="image" src="https://github.com/user-attachments/assets/6c9ba36f-d7f6-462d-b0cf-80507de463a1" />


<img width="975" alt="image" src="https://github.com/user-attachments/assets/e0af9d58-153e-4301-aa9a-7779668603ac" />



## Wednesday  
We successfully got the system to read the card and tag that came with the Raspberry Pi. We then experimented with other cards, such as a metro card and a Mathaf card, but neither worked due to frequency differences. Eventually, we found two cards that did work: a Megapolis card from one of my colleagues and a supervisor’s card.  

With the card-reading functionality established, we brainstormed prototypes. We considered an interactive timeline and a dominant color scatter plot. After discussion, we agreed on the scatter plot, with the addition of displaying artist information. To support this, we borrowed the book *Sajjil: A Century of Modern Art* from Mathaf and selected artworks related to themes such as nature, family, and city. We then created a dataset from these selections and photographed the artworks to use in our project.  

<img width="414"  alt="image" src="https://github.com/user-attachments/assets/44838f1a-3f0c-49a7-a0dd-2cf67878e436" />


<img width="440"  alt="image" src="https://github.com/user-attachments/assets/f6a4fe9e-dc6c-45ac-88c2-d7a68d21eb07" />



## Thursday  
We began developing our chosen idea. My colleague created a GitHub repository so we could collaborate effectively, starting with a clear file structure. She worked on building the scatter plot, while I focused on preparing the images and extracting dominant colors selected by the user. I also gathered artist information and created a dataset to support the visualization.  

Once we had the basic functions working, we tested the Raspberry Pi sensor to see if it could integrate with the project. We uploaded the website through the terminal using GitHub and successfully ran it on the Raspberry Pi, but the sensor did not function as expected. We brainstormed possible solutions, including using Thonny as a server, but that approach also failed. I then worked on displaying artist information while we continued troubleshooting, but the sensor still did not respond. In the end, we decided to pause and revisit the problem on Sunday.  

<img width="975"  alt="image" src="https://github.com/user-attachments/assets/02858487-ff74-4093-9a21-42f37b494841" />


<img width="875"  alt="image" src="https://github.com/user-attachments/assets/610905e8-3f7c-4984-a0ba-5cda43a797c7" />


<img width="975" alt="image" src="https://github.com/user-attachments/assets/aec5db31-6753-46d6-b7d9-7596cbd87572" />




## Reflection  
This week was a mix of challenges and progress. We learned how to set up the Raspberry Pi, troubleshoot sensors, and successfully read RFID cards after fixing wiring issues. Experimenting with different cards taught us about frequency limitations, and brainstorming project ideas pushed us toward combining technology with art. Collaboration was key—dividing tasks through GitHub and supporting each other during setbacks helped us move forward. Even though the sensor integration didn’t work yet, the process showed us the value of persistence, teamwork, and creative problem-solving.  
