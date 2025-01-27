## Lab 01

- Name: Sidra Ali
- Email: ali.179@wright.edu

## Part 1 - GitHub Profile

1. https://github.com/tragity7/SidraA

## Part 2 - Research

| Windows | Linux / Mac | Action |
| ---     | ---         | ---    |
| help    | man         |    Describes Windows PowerShell cmdlets, functions, scripts, and modules, and explains concepts, including the elements of the Windows PowerShell language     |
| Get-Location | pwd    |  Displays the directory you are currently in      |
| Get-ChildItem | ls    |    Displays a list of items (all folders, sub-folders and files) in a specific location    |
| mkdir   | mkdir       |   Creates a directory or subdirectory at a specified path     |
| Set-Location | cd     |   Changes the location of the current directory to a specified location     |
| New-Item | touch      |  Creates a new item and sets its value      |
| Move-Item | mv        |  Moves an item (including all its child items) from one location to another      |
| Copy-Item | cp        |  Copies an item from one location to another location in the same namespace  (it does not delete/cut any copied item)  |
| Remove-Item | rm      |  Deletes one or more items      |
| notepad.exe | vim     |  Opens the Notepad application      |

## Part 3 - Command Line Navigation

My OS is:
- [x] Windows
- [] Linux
- [] Mac

My Command Line Shell is: Windows PowerShell

### Navigating My OS on the Command Line

1. Create a directory named `DirA`: mkdir
New-Item -ItemType Directory -Name DirA

2. Create a directory named `Dir B`: mkdir
New-Item -ItemType Directory -Name DirB

3. Go into `DirA`:
Set-Location -Path DirA

4. Go into `Dir B` from `DirA`:
Set-Location -Path ..\DirB

5. Return to your user's home directory:
Set-Location -Path $HOME

6. Create a file named `test.txt`:
New-Item -ItemType File -Name test.txt

7. Move the file named `test.txt` into `DirA`:
Move-Item -Path test.txt -Destination .\DirA

8. Contents of `test.txt`:
Set-Content -Path .\DirA\test.txt -Value "rdjthjjj"

```
rdjthjjj
```
9. Make a copy of `test.txt` named `copy.txt` in `DirA`:
Copy-Item -Path .\DirA\test.txt -Destination .\DirA\copy.txt

10. View the contents of `DirA`: 
Get-ChildItem -Path .\DirA

11. Make a copy of `test.txt` in `Dir B` named `fodder.txt`:
Copy-Item -Path .\DirA\test.txt -Destination .\DirB\fodder.txt

12. Delete / remove both `fodder.txt` AND `Dir B`:
Remove-Item -Path .\DirB\fodder.txt

## Citations

Site: Learn Microsoft

https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.management/?view=powershell-7.4

Assistance in: I tried the commands on PowerShell and then used this website to verify that my PowerShell was working like it's supposed to (the actions matched the descriptions of the commands on the website)


