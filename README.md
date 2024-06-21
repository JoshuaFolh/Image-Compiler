# Image-Compiler
combines the 2 input images and saves at the desired file-path.

# Read me:

### Dependencies:
- `Numpy`
- `Skimage.io` 
- `pathlib.Path`

### Inputs:
<p style="color:red; font-weight:bold;">Note: these must be manually typed into the main method before running the code, <i>with the exception of the type of combination</i>. I know that ideally I should use an argparser to pass these file paths, but that's a future improvement, as I don't currently know how to do so.</p>

- 2 input image filepaths (s1 and s2)
- 1 output image filepath (outs)
- type of combination
  - "h" for horizontal otherwise,
  - vertical

### Purpose:
Combines the 2 input images, either vertically or horizontally depending on the user's input of type of combination, and saves at the desired file path. 

- I imagine there are more efficient ways of writing my functions:
   - both in terms of Big O efficiency 
     - (or whether or not the algorithm is efficient) 
   - and in terms of code length:
     - I would not be surprised if there already exists a Pillow function that does this. 

