# CMP-343-Equinox-Project-1
CMP 343 Full Stack Web Development  Project 1 - Something For Myself

[Equinox]
One line: An app used by Kemarion to help with his focus and memorization. 

Author: [Kemarion Guthrie] · Course: CMP 464/343 Product 1


1. About Me (the User)
Who am I in the context of this problem? What roles am I playing (student, employee, parent, athlete, gamer…)?

[I am a student at Lehman. I commute from Poughkeepsie to reach my on-campus classes. I have trouble memorizing formulas and concepts, which leads me to overthink my ability to do something.]

The last 3 times this happened: Real, recent moments. For each: when and where, what went wrong, what it cost, what you did.

1. I get confused when it comes to memorizing my formulas for exams
2. Doing assignments becomes an issue when my notes don’t help 
3. Forgetting which specific notes for topics I struggle with

What it costs me: Be specific. How often, how much?

⏱️ Time: I spend nearly 2-3 hours on assignments (mostly computer-focused), and it can take away time from what I could be doing next due to my scheduling with other needs. 
💸 Money: Money isn’t much of an issue when it comes to studying. However, due to transportation being needed for class, it can be quite a lot to pay off. 
🔋 Energy: I grow fatigued whenever I need to keep track of what I have to do
🙂 Joy: My joy is low whenever I have to remember something and only get blank results


2. Problem Statement
Gut check:

I need [an application to help me memorize the concepts I’m lost on] because [it’ll help my memory and understanding ].

Five Whys:

It’ll help with my academics
It’ll hold the notes I may need for potential classes/work
I can keep up with my resources
Reminders can be sent to maintain what is important
I can use these with easy access during complications in assignments

Problem statement:

When [I have to do my assignments for classes], I struggle to [to maintain focus and memorize the necessary formulas and materials], which costs me [a lot of time, very little enjoyment in doing it, and zero energy to try other resources]. This happens because [I struggle to manage my thoughts and emotions under pressure]. Right now I [put my phone to the side and tried to do an assignment], but [I found myself confused despite the notes I had and needed help with AI or other resource notes].

I'll know this is solved when: I keep monitoring my time and consistently reviewing notes and a little use of AI to aid my assignments.

Check: none of these words appear: app, website, platform, dashboard, tool, AI, track, automate, notify, feature.


3. Existing Solutions
What I use or tried
What it does well
Why it falls short for me
Ai Assitance
Gives a step-by-step response to the issues I might be dealing with
Can lead to overdependence or have errors that may lead to an incorrect answer. 
Music
Creates a comfortable environment that helps with focusing on the task.  
Music can be a hindrance or unavailable at certain moments. 
Notes
The notes written down are usually from the classwork or lectures 
The notes can help with a certain formula, but they can get tricky when other formulas or the note layout don’t match the assignment. 


The gap: In one sentence, what's still missing for me?

[I believe what is missing is using the solutions in a specific, responsible way, without creating a high level of dependency.]


4. Features & Benefits
Every feature should move me toward my "solved when" line.

Feature (what it does)
Benefit (how my life gets better)
MVP or Later?
Comfortable User Interface
The user interface would be the main way to navigate. To keep it simple but comfortable to use, it needs to avoid complexity. 
Having clear navigation between the screens after the user makes a selection 
Note Taking 
Having the ability to keep saved text, photos, or whatever documents in some form will help me.
The user can put whatever thoughts or information they need down on the code
AI Assistance
If having AI usage is possible, it will be used and focused on school needs and reviews. 
Later
Reminder Feature
The reminder will allow the user to schedule important information to keep track of events and tasks
Use timers and alerts to ping the app and keep the user up to date.

MVP (2–3 features): The skateboard: the smallest version I'd actually use.
Later:
Not doing: Things I'm deliberately leaving out.

5. Tech Stack
Front end
Surface: Cross-platform 
Tools: Java / JavaScript
Why: How does this fit where and when I have the problem?
Back end
Piece
Choice
Why
Server / API
Flask
Easy for the control to prepare the application for the project
Data storage
Supabase 
Provides a clean dashboard which is useful to navigate between stored folders and accounts
Outside services (optional)




Hosting/deploy
Google Cloud
Allows containers focused on the back end to scale with traffic

Architecture sketch
flowchart LR

 flowchart LR
  U["Me (User)"] --> FE["Front end: Webiste (HTML / CSS)"]
  FE --> API["Back end / API: Node.jss (HTML)"]
  API --> DB[("Data Storage: localStorage (JSON)")]
  API --> DEPL["Hosting: Static (Github)"]



6. Open Questions
What am I still unsure about? What do I need to figure out or test first?
I'm unsure how consistently the code may work if I keep adding or adjusting the HTMLs. I want to see the HTMLs work together instead of crashing. 

My Code Screenshots:
<img width="613" height="374" alt="image" src="https://github.com/user-attachments/assets/8efe2420-f342-4fba-ac53-b8b6c656bd3b" />

<img width="826" height="429" alt="image" src="https://github.com/user-attachments/assets/b5005431-8cf7-4dbd-94a4-cec3f944262f" />

NotePad:
<img width="334" height="434" alt="image" src="https://github.com/user-attachments/assets/48d8ec6c-25a8-42c4-9464-01d35bf51fe4" />

<img width="227" height="401" alt="image" src="https://github.com/user-attachments/assets/31bf6058-f54b-445c-a139-dbf5fac5a042" />

<img width="602" height="394" alt="image" src="https://github.com/user-attachments/assets/72e027aa-a7c5-41f5-bab7-aafe7e2411fc" />

<img width="400" height="418" alt="image" src="https://github.com/user-attachments/assets/98d29341-6fd9-4d65-8c06-b27bf9170073" />

<img width="495" height="407" alt="image" src="https://github.com/user-attachments/assets/cf559cf4-b242-4b5b-b6df-380651185b13" />

<img width="332" height="160" alt="image" src="https://github.com/user-attachments/assets/043f3434-53cb-47fe-9062-9fa9f57a65b7" />






