# Adding new files, and overriding fast files:
- Figure out which fast file you want to expand. \
  (For this example, let's use zm_buried.ff)

- Create a folder in 'hPatch' with the exact name of the fast file (without .ff)
<img width="342" height="40" alt="image" src="https://github.com/user-attachments/assets/9e14aae5-3b62-4ab3-acf4-65e84fd07a39" />

- Create a .txt file called 'PatchInGSCs.txt'
<img width="520" height="148" alt="image" src="https://github.com/user-attachments/assets/69e19b95-4a8d-4334-8da7-23e455919555" />

- Copy over the GSC files you want to load. \
  (They can be in folders, but you'll need to add them properly later)
  
<img width="845" height="165" alt="image" src="https://github.com/user-attachments/assets/e71cb475-ae80-4308-aed6-1f6c30bbc4f2" />
<img width="591" height="142" alt="image" src="https://github.com/user-attachments/assets/3ae98fb2-68cd-47ab-b6be-34e43fff7145" />

- Place the GSC files you want to load in the 'PatchInGSCs.txt' file. \
 (It must contain the path, each file in PatchInGSCs must end in a newline)

If the file is in a folder, you'll need to specify that in PatchInGSCs.txt

<img width="501" height="98" alt="image" src="https://github.com/user-attachments/assets/1cdff6ea-92e3-482b-8d45-5fdae2db8c3b" />

### PatchInGSCs.txt file example
```
example.gsc
example2.gsc
Folder\example3.gsc

```

### NOTE: 
 - This is NOT the same as putting in hPatch/maps/mp/gametypes_zm/_clientids.gsc
 - Instead of replacing a GSC, this loads a NEW custom one. 

# Stopping an entire fast file from loading
With Tesseract On Crack, you can stop entire fast files from loading.

- Inside of the folder with the name of the fast file create a file called 'DoNotLoadFile.bin'
<img width="528" height="159" alt="image" src="https://github.com/user-attachments/assets/e69c8d8f-0c9f-45ea-aae7-7d6abbd0f49d" />
