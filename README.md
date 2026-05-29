 Cybersecurity Awareness Console App

 Overview

This is a C# console-based chatbot designed to educate users about basic cybersecurity concepts. The application interacts with users through a simple menu system and provides information on key topics such as password safety, phishing, and safe browsing.

---

 Features

*  Plays a welcome sound on startup
*  Displays an ASCII chatbot
*  Greets the user personally
*  Interactive menu system
*  Covers essential cybersecurity topics:

  * Password Safety
  * Phishing
  * Safe Browsing
*  Colored console interface for better user experience

---

 Technologies Used

* C# (.NET Console Application)
* `System.Media` (for audio playback)
* `System.Threading` (for typing effect)

---

 How to Run the Program

1. Open the project in **Visual Studio**
2. Build the solution (`Ctrl + Shift + B`)
3. Run the program (`F5` or `Ctrl + F5`)

---

 Project Structure

```
CybersecurityAwareness/
│
├── Program.cs              # Main entry point
├── Menu.cs                 # Handles menu interaction
├── Logo.cs                 # Chatbot UI and behavior
├── Resources/              # Contains audio file (Welcome.wav)
└── README.md               # Project documentation
```

---

 How It Works

1. The program starts and plays a welcome sound.
2. The user is greeted and asked for their name.
3. An ASCII chatbot is displayed.
4. The user selects options from a menu.
5. The app displays information based on the selected topic.
6. The program runs until the user chooses to exit.

---

 Requirements

* .NET Framework or .NET Core installed
* Visual Studio (recommended)
* A `.wav` file added to project resources for sound playback

---

 Future Improvements

* Add quiz functionality to test user knowledge
* Provide personalized cybersecurity tips
* Expand topics (e.g., malware, social engineering)
* Improve chatbot interactivity with smarter responses

---

 Author
Asabongwa Gumede

---

