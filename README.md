# Developing a Procedural Tetris Game

![370fa23c6e13d0dc3fa6b6e011fa0b57-0](https://github.com/user-attachments/assets/e0dda513-fa54-4127-8ceb-5885c3f3895e)

---

## Team Information
- **Team Leader:** Huijun Seo
- **Team Members:** Huijun Seo, Jaehyuk Lee, Seokho Jung

## Project Overview
This project aims to develop a robust and scalable Tetris game using data structures. The development will focus on enhancing readability, modularization, and efficient file handling. The main goals include implementing a console-based Tetris game, integrating advanced features, optimizing the ranking system using linked lists or arrays, and using a procedural programming approach.

---

## Objectives
1. **Readability:** Ensuring the code is easy to read and understand.
2. **Modularization:** Dividing the code into manageable modules.
3. **File Handling:** Efficiently managing game data through file operations.
4. **Console Functions:** Utilizing console functions for better game interaction.
5. **Feature Enhancements:** Adding new features to improve the gameplay experience.

---

## Development Plan

### Game Flow
1. **startpage()**  
   Introduce the game.
   
2. **preset()**  
   Initialize variables and set up the board.
   
3. **Game Loop (while(1))**
   - **Block Drop**  
     Continuously drop blocks until the game is over.
     
   - **User Input (5 times)**  
     Allow five user inputs per block drop.
     
   - **check_key()**  
     Move blocks based on user input.
     
   - **draw_board()**  
     Redraw the board after each move.
     
   - **sleep(speed)**  
     Adjust game speed.

4. **drop_block()**  
   Drop the block one space down.
   
5. **check_level_up()**  
   Award points and level up.
   
6. **check_game_over()**  
   Determine if the game should end.
   
7. **create_new_block()**  
   Generate a new block.

---

### Features

#### Ranking System
- **Read ranking file.**
- **Initialize variables**  
  (level, score, lines, speed, flags).
  
- **Clear console**  
  and reset board.
  
- **Display game status**  
  and rankings.
  
- **Generate and draw new blocks.**

#### Block Movement
- **Move blocks**  
  based on user input.
  
- **Collision check**  
  before moving blocks.
  
- **Automatic block drop**  
  if no input.
  
- **Fix blocks**  
  in place upon collision.

#### Additional Features
- **Pause functionality.**
- **Timer notifications**  
  (e.g., remove a line within 50 seconds).
  
- **Speed increase**  
  after timeout.
  
- **Combo bonuses**  
  for removing multiple lines.
  
- **Level up**  
  and speed up features.
  
- **Bomb items**  
  and large block items.
  
- **Ranking system**  
  using linked lists or arrays.

---

### Ranking System Algorithm
- **Initialization:** 
  - At the end of each game, compare the score and insert it into the appropriate position.
  - If there are less than 10 rankings, add the new score to the list.
  - If the list has 10 rankings, compare and insert if the new score is in the top 10, and remove the lowest score.
  
- **Linked List Handling:**
  - Create a linked list if it's the first game.
  - Insert the user's score in the correct position based on the current scores.
  - Save the updated rankings to the file before starting a new game.

---

## screenshots

### procedural flow
![370fa23c6e13d0dc3fa6b6e011fa0b57-2](https://github.com/user-attachments/assets/1286d3e4-ae24-47a9-9078-d75bd58dbbbe)

### file structure
![370fa23c6e13d0dc3fa6b6e011fa0b57-1](https://github.com/user-attachments/assets/cdc35bc2-a646-4c6f-bf1e-be930e6b3e79)

### start
![370fa23c6e13d0dc3fa6b6e011fa0b57-0](https://github.com/user-attachments/assets/ece945fb-e3d9-42fc-9637-8dfc67973386)

![370fa23c6e13d0dc3fa6b6e011fa0b57-3](https://github.com/user-attachments/assets/5e1bc428-cf2d-4459-994b-f54bed258313)

![370fa23c6e13d0dc3fa6b6e011fa0b57-10](https://github.com/user-attachments/assets/14d67479-c69b-4503-8cc1-13e744d9dced)

![370fa23c6e13d0dc3fa6b6e011fa0b57-8](https://github.com/user-attachments/assets/52cdbdb2-7d8d-4c2a-82de-aebfb51b0b67)

![370fa23c6e13d0dc3fa6b6e011fa0b57-10](https://github.com/user-attachments/assets/9a0d3146-f2b4-4cd0-b2ac-cf39b881c25e)

![370fa23c6e13d0dc3fa6b6e011fa0b57-11](https://github.com/user-attachments/assets/3350e784-b047-45a8-9c56-98127239d421)

![370fa23c6e13d0dc3fa6b6e011fa0b57-13](https://github.com/user-attachments/assets/0f26b29a-7efb-43af-bd1f-9e711a88f0c8)

![370fa23c6e13d0dc3fa6b6e011fa0b57-14](https://github.com/user-attachments/assets/011caf97-29ba-4cfc-814f-8f42048b0fb2)

![370fa23c6e13d0dc3fa6b6e011fa0b57-26](https://github.com/user-attachments/assets/3afdfee0-ba00-4afc-927e-015571ee8d02)

![370fa23c6e13d0dc3fa6b6e011fa0b57-18](https://github.com/user-attachments/assets/d0b5ce45-b8bf-4fbb-ba6b-b1accbfc3397)

![370fa23c6e13d0dc3fa6b6e011fa0b57-23](https://github.com/user-attachments/assets/1c646488-de36-46d8-ae32-d737177c73e8)

![370fa23c6e13d0dc3fa6b6e011fa0b57-22](https://github.com/user-attachments/assets/e044eb37-e1d6-4577-8361-73ef28c19e48)

![370fa23c6e13d0dc3fa6b6e011fa0b57-23](https://github.com/user-attachments/assets/4ec956dd-0f8e-491c-9c7f-8381727cff4c)

![370fa23c6e13d0dc3fa6b6e011fa0b57-26](https://github.com/user-attachments/assets/64857953-c5fa-4a9b-aff4-c2e28f16cae7)

![370fa23c6e13d0dc3fa6b6e011fa0b57-27](https://github.com/user-attachments/assets/4177c5d8-8cb4-4e37-8f92-7dcbf9f80de2)

### ranking algorithm
  
![370fa23c6e13d0dc3fa6b6e011fa0b57-31](https://github.com/user-attachments/assets/9a407297-344f-4a8d-99ac-7be01ad87c35)

![370fa23c6e13d0dc3fa6b6e011fa0b57-32](https://github.com/user-attachments/assets/f4f5bc25-85d4-4d21-a3f4-98583c1837e4)
  
![370fa23c6e13d0dc3fa6b6e011fa0b57-33](https://github.com/user-attachments/assets/0ce54b92-4c57-4bb0-9f9a-30c50e86d521)

![370fa23c6e13d0dc3fa6b6e011fa0b57-35](https://github.com/user-attachments/assets/773d0b2c-9d43-43dc-b5e4-9542c14d1f7b)

### end
![370fa23c6e13d0dc3fa6b6e011fa0b57-40](https://github.com/user-attachments/assets/46186560-2990-4a2d-9079-7d0771b1777b)

![370fa23c6e13d0dc3fa6b6e011fa0b57-41](https://github.com/user-attachments/assets/a1734c3b-a25e-4f90-a899-53442d0614de)

![370fa23c6e13d0dc3fa6b6e011fa0b57-42](https://github.com/user-attachments/assets/03bb41f4-3498-4ec4-bc8b-f115555bc06e)


---

## References
- [Joy Stick Implementation](https://velog.io/@jeeseob5761/프로그래머스-조이스틱)
- [Free Strokes Blog](https://freestrokes.tistory.com/84)

---

- [Seperately Created from origin repo -> C_Algo](https://github.com/HeeJohn/C_Algo/tree/main/project/tetris)
