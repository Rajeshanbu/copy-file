# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
# Step 1:
Get the file name and location from the user.
# Step 2:
Give a new file name to create a copy of a file content.
# Step 3:
Read the file and close the file.
# Step 4:
Now write the content in the new file.
# Step 5:
When done print "File copied successfully".
# Step 6:
End of the program.
# PROGRAM:
```
Program For Copying The Contents:
Developed by: Rajesh A
RegisterNumber: 22008551
```
```
print("Enter the Name of Source File: ")
sFile = input()
print("Enter the Name of Target File: ")
tFile = input()
fileHandle = open(sFile, "r")
texts = fileHandle.readlines()
fileHandle.close()

fileHandle = open(tFile, "w")
for s in texts:
    fileHandle.write(s)
fileHandle.close()

print("\nFile Copied Successfully!")
```
# OUTPUT:

![77d66f00-de23-4d7e-ba53-db6a6acf2368](https://user-images.githubusercontent.com/118924713/214761487-e02f044a-92e4-43da-8918-9cf56ecbb54b.jpg)

![d843b598-9825-41b6-be07-805c19603f68](https://user-images.githubusercontent.com/118924713/214761500-d7a90dee-94d9-4c8a-9f96-c8078b40f8ce.jpg)

![ef445fd0-a08a-4a04-8045-38007345a177](https://user-images.githubusercontent.com/118924713/214761525-2fbff44b-9db2-4b80-aa23-f666bc8c0729.jpg)



# RESULT:
Thus the program is written to copy the contents from one file to another file.
