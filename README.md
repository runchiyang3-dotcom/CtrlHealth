# Healthy Food Game
### *Learning Healthy Habits Through Movement and Play*

---

## GitHub Repository
**Repository URL:** [https://github.com/runchiyang3-dotcom/CtrlHealth)  

---

## Project Overview
**Healthy Food Game** is an interactive, camera-based classroom prototype that teaches children about **healthy eating and physical activity** through **movement-based play**.  
Players move in front of the camera to **catch falling healthy foods**, earning points and learning nutrition tips in a fun, social way.

Developed for a university **interaction design studio**, the project demonstrates how technology can support **human interaction**, **collaboration**, and **learning through movement**.

---

## Repository Structure

| Folder/File | Description |
|--------------|-------------|
| `main.exe` | Main Game Application file — runs the playable prototype (in the release v1.0.0/main). |
| `Releases/v1.0.0` | Contains final prototype source code. |
| `web/` | Stores tradeshow webpage source. |
| `docs/` | Project documentation and artefacts (see below). |
| `wiki/` | Links to GitHub Wiki pages (Design Process & Ethical Considerations). |
| `README.md` | This file — project overview and setup instructions. |

---

## Documentation & Artefacts

The repository contains **all documentation deliverables** required by the *Documentation & Artefacts* section of the assessment.

| Artefact | Description | Link/Location |
|-----------|--------------|---------------|
| **Design Process Overview** | Iterative design documentation including research, testing, and reflection. | [View on Wiki](../../wiki/Design-Process-Overview) |
| **Ethical Considerations** | Ethics reflection using the *Ethics for Interaction Design* framework. | [View on Wiki](../../wiki/Ethical-Considerations) |
| **Storyboard** | Early storyboard showing concept flow and classroom context. | `/docs/storyboard/` |
| **Design Framework** | Framework diagram showing how movement, collaboration, and feedback connect. | `/docs/design-framework/` |
| **Low-Fidelity Prototype Links** | Early prototype builds and screenshots (pre-testing). | [UI Demo](https://www.figma.com/proto/31yXjiqHkNmPVL7ESsCP8E/Game-UI---Lower-Decks-2D-Game--Community-?node-id=168-11&p=f&t=VgJZ5cgmFG53D8m4-0&scaling=contain&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=168%3A11&show-proto-sidebar=1) |
| **Weekly Group Work Logs** | Summaries of in-class progress, decisions, and reflections. | `/docs/stand` |
| **Exhibition Poster** | Final trade-show poster (Canva). | [Poster PDF](https://www.canva.com/design/DAG2PU7ki98/ndU87O2Kt77RrvE8lyQn2A/view?utm_content=DAG2PU7ki98&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h8b8bdf4a83), [Brochure](https://www.canva.com/design/DAG2Ydbs5JY/Hkqw7fQAUhVjWfaQ6RbnXQ/view?utm_content=DAG2Ydbs5JY&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h792bae7300)|
| **Webpage / Trade Show Site** | Public webpage promoting the project and hosting demo materials. | [Visit Webpage](https://github.com/runchiyang3-dotcom/CtrlHealth/blob/main/web/index.html) |

---

## Key Features

- 🎮 **Camera-based gameplay** — players move to catch healthy foods.  
- 🏆 **Leaderboard** — encourages classroom replay and collaboration.  
- 💬 **Educational tips** — short nutrition advice after each round.  
- 🎛️ **Menu & settings** — start game, adjust sound, view leaderboard.  
- 🧍‍♀️ **Collaborative play** — multiple players can interact simultaneously.  

---

## Installation & Deployment

### Requirements
- Python 3.10 or higher  
- [Pygame](https://www.pygame.org/)  
- Computer with a **webcam**

### Setup Instructions
```bash
 1. Clone the repository
git clone https://github.com/runchiyang3-dotcom/CtrlHealth
cd CtrlHealth

 2. Check Release list & Download file
gh release list --repo runchiyang3-dotcom/CtrlHealth
gh release download v1.0 --repo runchiyang3-dotcom/CtrlHealth
gh release download v1.0 --repo runchiyang3-dotcom/CtrlHealth --dir "C:\your folder path\Release"
(if download to a specific directory)

 3. Install dependencies
pip install pygame
pip install yolov8
pip instal...
(check what command line tells you to install)

 4. Run the prototype
python main.py
```

### Simple Run 
- At our github, find 'Releases/Healthy Food Game (Project)'
- Download main.zip
- Extract main.zip and find 'main.exe'
- Open main.exe
(make sure you have turned on your camera and audio settings on your PC)
---

## How to Play

From the Menu, choose:

```
▶️ Start Game

📊 Leaderboard

⚙️ Settings
```

Move in front of the camera to catch healthy foods as they fall.

Gain points for healthy choices and lose points for unhealthy ones.

After each round:

- View Healthy Tips about diet and lifestyle.

- Choose whether to save your score.

- Return to menu (🏠), press L for leaderboard, or ESC to quit.

## Login & Data

- No login required.

- Scores are stored locally in the /data folder.

- Camera input is processed live and not recorded or uploaded.

## Design & Evaluation Summary

The prototype was refined through:

Two rounds of user testing (low-fi and final prototype).

Feedback from teachers and tutors, guiding iterative improvements.

Integration of the Design for Location and Ethics for Interaction Design frameworks.

📄 More detail in the Design Process Overview


## Ethical Statement

Inclusive and age-appropriate content that avoids stigmatizing language.

No user data stored; all camera input handled locally.

Testing conducted with teachers as ethical proxies for children.

🔗 Read more in the Ethical Considerations Wiki Page


## Contributors
Name |	Role
- Runchi Yang | Backend Development & User Testing & Research 
- Jialiang He | Low-Fi/Hi-Fi prototype & Backend Development & Audio design 
- Zhun Li	| Research & User Testing
- Sizhe Li	| UI/UX Design & Frontend Development & Web Page & Audio design
- Liyang Yu	| Documentation & QA Testing/Development & Poster Creation & Presentation

University: The University of Queensland
Course: DECO3500 – Interaction Design Project Studio
Semester: Semester 2, 2025

## License

Released under the MIT License for educational and non-commercial use.
See the LICENSE file for details.







