# minesweeper-llm
ShellHacks Hackathon Challenge
## Inspiration
Our drive came from seamlessly merging AI into gaming, envisioning an engaging NPC responsive to in-game events. We harnessed image processing and OCR, revolutionizing Minesweeper and player interactions.

## What it does
Our solution introduces an AI-powered NPC into a game (Minesweeper) that dynamically responds to game events, enhancing user immersion. By utilizing image processing and OCR, we extract grid information from in-game images, enabling the AI model to interpret and interact with the game grid effectively, providing informative and engaging outputs to the player.

## How we built it
We built the solution by integrating AI into the Minesweeper game, instructing a language model to interpret grid inputs. Image processing, OCR, and OpenCV were employed to extract and denoise grid information from screenshots, allowing the model to generate responsive outputs, effectively bridging visual and auditory cues in gameplay.

## Challenges we ran into
**Dynamic UI Implementation**:
      - Developing a dynamic user interface that effectively interacts with the game while seamlessly 
         integrating multi-threading functionality for smooth execution.
**Optimizing Language Model Prompts**:
      - Crafting an appropriate prompt for the language model to ensure accurate and meaningful 
        responses, involving significant experimentation and research into prompt engineering based on 
        various papers and resources.
**Accurate Text Extraction from Images**:
     - Facing difficulties in precise text extraction from images using the language model directly, 
       prompting the need for denoising images and leveraging OCR techniques to enhance text extraction 
       accuracy from the grid.

## Accomplishments that we're proud of
**Seamless Integration of AI NPC**:
      - Successful integration of an AI-driven NPC into Minesweeper, enabling intuitive interactions with the 
         game world for a richer gaming experience.
**Efficient Grid Information Processing**:
      - Developing an efficient algorithm that accurately extracts grid information from in-game images 
        using OCR and denoising techniques, facilitating precise responses from the language model based 
        on the extracted grid data.

## What we learned
**AI Fusion with Gaming**:
      - We mastered the art of integrating AI seamlessly into games, empowering NPCs to dynamically react 
         to game dynamics revolutionizing player immersion.

**Image Processing Expertise**:
       - Delving into image processing intricacies, particularly denoising and OCR, we honed skills essential 
          for precise data extraction from in-game images, amplifying our understanding of AI's role and 
          potential in gaming landscapes.

## What's next for Minesweeper-LLM
       -  We have used OCR for parsing the image of the minesweeper board, if we can train a LLM to 
          directly read the image and describe it without human intervention the whole process can move 
          more towards the 3D game than the 2D structural games.