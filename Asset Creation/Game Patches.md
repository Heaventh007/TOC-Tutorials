# How to create game patches

> The header needs to be the filetime of the executable.
Tesseract on Crack will print out this value to xbWatson. \
Alternatively, you can use xextool. 

<img width="584" height="34" alt="image" src="https://github.com/user-attachments/assets/2d8a9216-d363-4f29-a097-b9a2b7157d86" />
<img width="1203" height="346" alt="image" src="https://github.com/user-attachments/assets/4c730380-2d2a-4e8c-9bd7-f0a6d3eba33f" />


### After the header, it looks like this:
- Address
- Size
- Data
<img width="1245" height="107" alt="image" src="https://github.com/user-attachments/assets/3324c909-6b40-4394-be5b-ff8c014d303d" />

### You can also include multiple patches, like this:
- Header
- Address
- Size
- Data
- Address
- Size
- Data
<img width="1555" height="472" alt="image" src="https://github.com/user-attachments/assets/6f2e1de8-43aa-433e-a7e1-d048c26c5d2b" />


***Patches are applied before the game loads anything.***
