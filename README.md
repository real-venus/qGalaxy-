# QGalaxy Star Defender Game- Proposal

**Game Overview**
- **Platform :** Web-based (Qubic Blockchain, integrated with QBAY NFT Marketplace)
- **Genre :** Strategy / War / NFT Game
- **Target Audience :** Crypto gamers, strategy fans, NFT collectors

## 1. Abstract
Qubic Galaxy Star Defender is an NFT battle game built on the Qubic Blockchain that connects directly with Qbay, the first NFT marketplace on the network. 
The game adds real value to NFTs by allowing players to use them in exciting battles, encouraging the creation of new NFTs. 
It combines fun gameplay with strategic teamwork, offering a unique experience for both gamers and NFT collectors. 
As the first entertainment project of its kind on Qubic, it brings together play, collection, and community in one engaging platform.

## 2. Introduction and Motivation
With the growing demand for meaningful NFT utility, Qubic Blockchain needs a flagship entertainment product that showcases its ecosystem’s capabilities. 
QGalaxy Game serves this need by linking NFT ownership with interactive gameplay, increasing engagement on Qubic and driving traffic and transactions on QBAY.
By playing this game, users can enhance the value and variety of their NFTs while actively supporting the growth of QBAY.

## 3. Functional Features
- Wallet connection and NFT minting
- Interactive 2D starfield UI with real-time metadata
- One-on-one star battles and galaxy-wide tournaments
- Dynamic NFT ownership transfer based on battle outcomes
- On-chain/off-chain hybrid stats and battle verification
- Leaderboards, win history, and metadata display

## 4. Technical Overview & Architecture
1.  **Core Gameplay Loop**
-    Users connect their wallets to the game.
-    Users select a star in a galaxy(Each star corresponds to a unique NFT).
     If there is no NFT corresponding to the star, the user can mint a new NFT there. 
     The NFT to be minted can be selected from the list of game NFTs and minted.
-    Users can view ownership, metadata, and stats of NFTs linked to stars.
-    Players can initiate battles to conquer other players’ stars.
-    If a player wins a battle, the NFT ownership is transferred to the winner.
-    If all the stars in the galaxy have NFTs minted, the game operator will create a new galaxy. (Here, the number of stars in the galaxy is limited.)
-    Galaxies can battle each other in tournaments, and the result of the battle will have a significant impact on the leaderboard rankings of teams within that galaxy.

2.   **Battle Logic**
   - Individual Battles
     - Candy Crush or Tetris style quick matches
   - Galaxy vs. Galaxy Tournaments
     - Galaxy captains vote on match type (e.g., time trial, survival, 1v1 ladder).
     - Results based on:

        - Total stars won/lost

        - Number of destroyed stars

        - Total damage dealt

        Rewards:

        - Galaxy-wide team ranking boost

        - Reputation ranking on a leaderboard

3. **Core Components:**

-  **backend**
    - NFT Mint Logic in the Galaxy,
    - 1v1 Daily Battle Logic
    - Tournament Battle Logic
    - Leaderboard Management Logic
    - Reward Logic
    - wallet connect, integration with Qbay SC

-  **Art and UI Design, Front-End:**
    - Galaxy Dashboard Page
    - 1v1 Battle Page
    - Tournament Battle Page
    - eaderboard Page
    - NFT and Gear Purchase Page
- **API integration**
    - API integration and bug fixing between frontend and backend using RESTful API

## 5. Detailed Scope and Timeline

The project is estimated to take 10 weeks with a dedicated team comprising one Full-Stack Engineer and one UI/UX Designer.

- **Total Estimated Budget:** $30,000
- **Implementation Timeline:** 10 weeks

### Phase 1 (Weeks 1–3):
- Finalize game mechanics, leaderboard management system, integration with Qbay SC
- Implement battle logic, ownership transfer
### Phase 2 (Weeks 4–8):
- Game Dashboard Page,
- 1v1, Tournament Battle Page,
- Leaderboard Management Page,
- Game Admin Page
- NFT list page

### Phase 3 (Week 9-10):
- Integrate tournaments and reputation system
- Load test, bug fixes
- Launch Beta version, user feedback, and final adjustments

## 6. Milestones and Deliverables

- ✅ Week 3: Star battles + NFT transfer backend logic 
- ✅ Week 8: Wallet integration, Tournament system and full gameplay loop (frontend)
- ✅ Week 10: Beta Launch and feedback integration

## 7. Payment Terms

**Fixed milestone-based payments:**
-  **Milestone 1 – Backend(Core Game Engine) – $7,500 (25%)**
    - NFT Mint Logic in the Galaxy,
    - 1v1 Daily Battle Logic
    - Tournament Battle Logic
    - Leaderboard Management Logic
    - Reward Logic
    - wallet connect, integration with Qbay SC
-  **Milestone 2 – frontend(Game UI) – $9,000 (30%)**
    - Galaxy Dashboard Page
    - 1v1 Battle Page
    - Tournament Battle Page
    - eaderboard Page
    - NFT and Gear Purchase Page
-  **Milestone 3 – API integration and Beta version – $13,500 (45%)**

## 8. Future Features

This project will be delivered in full beta to the Qubic core team and will not be involved in any further development.
That is, this project will be handed over to the Qubic core team.
After that, if there is better feedback from users, development can proceed according to the core team's request.

## 9. Tech Stack

- **Frontend:** React.js with WebGL, Three.js
- **Backend:** Node.js
- **Wallet:** MM Snap and wallet connect
- **Data Storage:** PostgreSQL

## 10. Team

- **Venus: Full-Stack Engineer**: Engineer with 7 years of full stack experience 
- **Fabino: UI/UX Designer:** 



