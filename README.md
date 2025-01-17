# About
Calculate the similarity between two pet pictures

Created as a proof of concept tool that might be used to help reunite pets with their humans during the January 2025 Southern California wildfires


## Setup
Ensure you create your `.env` file and add your `OPENAI_API_KEY`. 
Replace the image files with any two images you like.

## Examples

![Screenshot 2025-01-16 at 7 27 17 PM](https://github.com/user-attachments/assets/f9594f24-1ab8-46ab-b940-b7249dac6828)
![Screenshot 2025-01-16 at 7 27 25 PM](https://github.com/user-attachments/assets/1878087a-7326-4ed1-835c-a4cc5d490838)
![Screenshot 2025-01-16 at 7 27 32 PM](https://github.com/user-attachments/assets/e8994337-dd34-40a0-a978-033f98e2e645)

## How it works
1. Passes 2 pet images to OpenAI API for GPT-4o (which includes vision capabilities)
2. Uses the JSON Schema to perform an `analysis` of the images for comparison and output a 0-100 `similarity` score
