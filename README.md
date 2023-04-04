# Basic PowerShell

I'm new to PowerShell so decided to create a repo to see how it works.

See `test-script.ps1` for a demo of functionality which, at the time of writing, contains the following:

```ps1

# This is a test script

mkdir "github" # Create a new folder
touch.exe github/test.txt
ls .\github

Move-Item .\github\test.txt .
```

