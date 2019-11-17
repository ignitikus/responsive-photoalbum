# README 
My goal was to create a website gallery that would look great on different devices.

There are 4 supported resolutions: 
    
    1) Mobile (under 500px); 
    2) Medium Tablet (from 501px to 800px); 
    3) Large Tablet (from 801px to 1100px); 
    4) Default (from 1101px)

There are 3 grids in total. 1 for main layout, 1 for gallery,and 1 for footer.

Challenges: 

Had issue with the footer. It appeared in the middle of the gallery. Solved by adding in 'grid-template-areas' more lines for gallery. 

There is difference in resolution between IPad and IPad Pro. Solved by adding separate @media. 

    - Niko