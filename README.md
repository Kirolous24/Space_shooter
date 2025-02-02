# Space Battle Game (Pygame) 🚀🎮

Description:

This is a simple two-player space battle game built with Pygame, where two players control spaceships and attempt to defeat each other by shooting bullets. The game tracks player health and declares a winner when one player’s health reaches zero.

Features

	- 🕹️ Two-player gameplay (Red vs. Yellow)
	- 🔫 Bullet shooting mechanics with sound effects
	- ❤️ Health system for both players
	- 🎵 Sound effects for firing bullets and taking damage
	- 🎨 Smooth movement and real-time game updates

Controls

Yellow Player (Left side)

	* Move Up: W
	* Move Down: S
	* Move Left: A
	* Move Right: D
	* Shoot: Left Shift

Red Player (Right side)

	* Move Up: Arrow Up
	* Move Down: Arrow Down
	* Move Left: Arrow Left
	* Move Right: Arrow Right
	* Shoot: Period (.)

Game Mechanics

	1.	Each player can move their spaceship using their assigned movement keys.
	2.	Press the shoot key to fire bullets at your opponent.
	3.	If a bullet hits an opponent, their health decreases.
	4.	Once a player’s health reaches zero, the game declares the winner and ends.

Setup & Installation

Prerequisites:

- Ensure you have Python installed. Install Pygame using the following command:

pip install pygame

- Run the Game

Run the Python script to start the game:

python main.py

Game Logic Breakdown

	•	Shooting Bullets:
	•	Players can fire bullets when pressing their assigned shoot key.
	•	A sound effect plays upon firing.
	•	The bullets are stored in lists (yellow_bullets, red_bullets) and handled by handle_bullets().
	•	Collision & Health:
	•	If a bullet hits a player, their health decreases (RED_HIT, YELLOW_HIT).
	•	If a player’s health reaches zero, the game declares the winner and displays the result.
	•	Game Loop:
	•	Handles user input for movement and shooting.
	•	Updates player positions, bullets, and health.
	•	Continuously updates the game window with pygame.display.update().

Future Enhancements (Ideas 💡)

🔹 Add power-ups like shields or speed boosts.
🔹 Introduce different weapons with varying damage.
🔹 Implement a single-player mode with AI enemies.
🔹 Improve graphics & animations.

🎮 Enjoy the game! 🚀

Let me know if you need modifications! 🚀🔥
