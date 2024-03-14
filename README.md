# Summary
A web application that protects users from shoulder surfing attacks (unauthorized viewing of device screens) by leveraging face-api.js for face detection and implementing various protection mechanisms:
1.	Alert message: This serves as a visual signal to the user without causing any significant interruption in their workflow. The alert message can be personalized to include instructions and suggestions.
2.	Front camera preview: It is an intuitive way of keeping an eye on the user's surroundings and the suspected attackers. The preview will be displayed when the alert is triggered. If the attacker sees himself on the screen, it could be a subtle deterrent.
3.	Low brightness: This is a subtle way of notifying users without causing disruption. It makes it difficult for the attacker to see.
4.	Sound notification: An audio signal can be utilized to alert users. The alarm can be configured to be loud enough to attract people's attention in the surrounding area.
5.	Vibration: This is a non-disruptive way to alert users. It can be used when audio and visual cues are not appropriate.

# Requirement
* OS: Windows 7 or later, macOS 10.12 or later, Linux (various distribution)
* Node: v20 or later

# How to Run
1. Clone repository or download and extract application zip repository
2. Go to application directory
```
    cd faceapi
```
3. Install dependencies
```
    npm install
```
4. Run the application
```
    npm start
```
5. Open the application by accessint this url
```
    http://localhost:3000/
```



