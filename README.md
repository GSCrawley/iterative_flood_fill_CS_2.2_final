# iterative_flood_fill_CS_2.2_final

# For this i'll be using what's known as the flood/fill algorithm. 

# it's what's used in MineCraft to find mines as well as the Paint Bucket tool in Paint Programs.

# Starting from a pixel at (x,y) location, it explores an image pixel by pixel, 
# by visiting the neighbouring pixels of any pixel it previously visited. 

# Given a target color and a replacement color, each pixel matching the target color gets repainted the replacement color. 

# if the target color isn't found, then the algorithm ends. 

# Due to time constraints I won't be including a visual representation, instead I'll demonstrate that its working by having the program display the number of 'islands' of color on a white 'map'.