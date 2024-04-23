# Super-Tic-Tac-Toe-web-application


**Project Description:**
This project is a web-based adaptation of the classic game Tic Tac Toe, enhanced with the complexity of Super Tic Tac Toe, which involves multiple boards and advanced game mechanics. Developed as a collaborative effort by a group of five students, this application provides a platform for users to register, log in, and play against each other in a real-time gaming environment. The project aims to implement robust back-end logic with a user-friendly front-end interface, utilizing a variety of programming technologies and tools.

**My Role and Contributions:**
Initially, I was responsible for developing the complete application logic in the `app_logic` module. This involved crafting the core game functionalities such as game state management, player actions, and win conditions. The logic was designed to handle multiple game scenarios dynamically, ensuring robust performance across various game states.

Post-development, my role expanded to include participation in code reviews and team meetings, where I acted as a scrum master and note-taker. This ensured that our project adhered to agile methodologies, promoting iterative development and frequent evaluation. Additionally, I contributed to debugging and enhancing features, suggesting several key implementations that significantly improved user experience.

#### Technologies Used:
- **Python:** Primary programming language for server logic.
- **Bottle:** Lightweight web framework for handling web requests and serving dynamic content.
- **SQLite:** Database management system used for storing user and game data.
- **HTML/CSS:** Used for crafting the front-end presentation of the application.
- **JavaScript:** Enhances interactivity on the client side, handling dynamic content updates without reloading the page.

#### Features:
- **User Registration and Login:** Secure authentication system for user management.
- **Game Lobby:** Users can create new games or join existing ones.
- **Live Game Updates:** Real-time gameplay without page refreshes.
- **Game Statistics:** Tracks wins, losses, and total games played for each user.

#### Getting Started:

**Prerequisites:**
- Ensure you have Python installed on your machine (Python 3.8+ recommended).
- Install necessary Python packages:
  ```bash
  pip install bottle sqlite3
  ```

**Running the Application:**
1. Clone the repository or download the source code:
   ```bash
   git clone https://github.com/sahamid12/Super-Tic-Tac-Toe-web-application
   ```
2. Navigate to the project directory:
   
   
3. Run the server script:
   ```bash
   python BottleServer.py
   ```
4. Open a web browser and visit `http://localhost:5000` to start playing.

#### File Structure:
- **BottleServer.py:** Main server file containing routing and game logic.
- **store.py:** Handles database interactions for user and game management.
- **HTMLprovider.py:** Manages HTML templates for rendering views.
- **user.py:** Defines user operations like registration and login.
- **utils.py:** Includes utility functions like template formatting.
- **assets/**: Contains static files such as CSS and JavaScript files.


**Learning Outcomes:**
Through this project, I learned and applied various software development methodologies that are crucial in a real-world development environment. Agile development practices were particularly insightful, allowing our team to adapt to changes quickly and efficiently. The hands-on experience with code reviews and version control using git further solidified my understanding of collaborative development and best coding practices.

#### Contribution:
This project was developed as part of a university course by a team of five students. Each member contributed to both the back-end logic and the front-end development, ensuring a well-rounded understanding of web application components.

*Super Tic Tac Toe Development Team*

- Sara Hamid
- Mohammad Arafat Zaman
- Zayd Loya
- Benjamin Steinhauer
- Ahsan Zahid


#### Acknowledgments:
- Thanks to our course instructors for their guidance.
- Appreciation to all team members for their dedication and teamwork.

---

