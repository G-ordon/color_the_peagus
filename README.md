## **Action-Adventure Fantasy Story Game**
An interactive action-adventure fantasy game built with Phaser and JavaScript. Players navigate through an immersive story-driven world, making choices and exploring environments through click events. Perfect for showcasing dynamic storytelling and interactivity in games.

---

**Features**
- **Fantasy-Themed Adventure:** Embark on a thrilling journey through a richly crafted world filled with quests and challenges.
- **Click-Based Interaction:** Explore the world, interact with NPCs, and uncover secrets using intuitive click events.
- **Dynamic Storytelling:** Player choices influence the story’s progression, leading to multiple outcomes.
- **Custom Art and Audio:** Enhance the gameplay experience with unique sprites, backgrounds, and soundtracks.

**Technologies Used**
- **Phaser 3:** A fast and robust HTML5 game framework.
- **JavaScript:** For game logic and interactions.
- **HTML5 Canvas:** For rendering graphics and animations.

**Setup Instructions**

 **Prerequisites**
  - Node.js installed on your computer.
  - A code editor like VS Code.
  - Basic understanding of Phaser and JavaScript.

**Steps**
1. Clone the repository:

```bash 
git clone https://github.com/yourusername/adventure-game.git
cd adventure-game
```
2. Install dependencies (if applicable):

```bash
npm install
```

3. Start a local server to run the game:

```bash
npm start
```
4. Open the game in your browser:
```
http://localhost:8080
```
If you prefer a manual setup, include the Phaser library in an index.html file and open the file in your browser.

---

**How to Play**
1. Start the Game: Begin your adventure with a single click.
2. Explore: Click on various objects or areas to interact with them.
3. Make Decisions: Choose your path through dialogue options and story events.
4. Progress the Story: Your actions will influence the outcome of the adventure.

**Code Structure**
- index.html: The entry point for the game.
- main.js: The core game logic and Phaser scenes.
- assets/: Contains images, audio, and other game resources.
- styles.css (optional): For customizing the UI if needed.

**Example Code Snippet**
Here’s a sample of how to use Phaser click events in your game:

```this.add.text(100, 100, 'Click here to start your journey!', { fontSize: '20px', fill: '#ffffff' })  
    .setInteractive()  
    .on('pointerdown', () => {  
        this.scene.start('GameScene');  
    });

```
---
**Future Enhancements**
- Add more levels and story branches.
- Include character upgrades and inventory management.
- Integrate animations for a more immersive experience.

---

**Credits**
- Game developed by Gordon Ochieng.
- Art and music assets from [codecademy](codecademy).
- Powered by Phaser.

--- 

**License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

