🐦 Flappy Bird (Unity)
A simple implementation of the classic Flappy Bird game in Unity. The player controls a bird, aiming to fly between obstacles without colliding. The project is built using modern practices, including Zenject for dependency injection and DOTween for animations.

📁 Project Structure

plaintext
Copy
Edit
Assets

├── Animation/                   # Character and UI animations  
├── Configs/                     # Configuration ScriptableObject files  
├── OtherAssets/

│    ├── Fantasy Wooden GUI       # Fantasy-style user interface  

│    ├── FlappyBirdAssets/

│    │   ├── Sound                # Game sounds  

│    │   └── Sprite               # Bird and obstacle sprites  

│    └── Thaleah_PixelFont/      # Pixel font for the UI  

├── Plugins/

│   ├── Demigiant/DOTween       # Animation library 

│   └── Zenject/                # Dependency Injection (DI)
🛠️ Technologies

Unity (version 202X.X)

DOTween — smooth animations

Zenject — clean architecture and scalability

ScriptableObjects — settings and configuration

Custom GUI — stylized user interface

🚀 How to Run
Clone the repository:
git clone https://github.com/your-username/flappy-bird-unity.git
Open the project folder in Unity.
Make sure DOTween and Zenject are installed (see Plugins/).
Launch the Main or Game scene.

🎮 Controls

Space / Mouse Click — flap

🧪 Testing
The project includes built-in test scenes from Zenject (Plugins/Zenject/OptionalExtras/) that can be used as a reference, but are not required to run the game.

📦 Roadmap

Add a high score leaderboard

Mobile platform support

Hardcore mode

Cloud saves









