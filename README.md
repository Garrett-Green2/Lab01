# Lab01

## Lab 01

- Name: Garrett Green
- Email: green.467@wright.edu

Instructions for this lab: https://pattonsgirl.github.io/CEG2350/Labs/Lab01/Instructions.html

## Part 1 - GitHub Profile

1. [garrett-green2's GitHub Profile](https://github.com/garrett-green2)

## Part 2 - Research

| Windows | Linux / Mac | Action |
| ---     | ---         | ---    |
| help    | man         |    displays a list of commands to use    |
| Get-Location | pwd    |    displays directory that user is currently in    |
| Get-ChildItem | ls    |    retrieves a list of files and directories from a particular location    |
| mkdir   | mkdir       |      creates a new directory  |
| Set-Location | cd     |    moves the current directory to a user-specified path    |
| New-Item | touch      |    creates a new item    |
| Move-Item | mv        |    moves items from one location to another    |
| Copy-Item | cp        |    copies items from one location to another    |
| Remove-Item | rm      |    deletes items    |
| notepad.exe | vim     |    opens notepad    |

## Part 3 - Command Line Navigation

My OS is:
- [x] Windows
- [] Linux
- [] Mac

My Command Line Shell is: 

### Navigating My OS on the Command Line

1. Full / absolute path to your user's home directory: PS C:\Users\Garrett> Get-Location
2. Create a directory named `DirA`: PS C:\Users\Garrett> mkdir DirA
3. Create a directory named `Dir B`: mkdir "dir B"
4. Go into `DirA`: cd dirA
5. Go into `Dir B` from `DirA`: cd C:\Users\Garrett\DirA\dir B
6. Return to your user's home directory: 
7. Create a file named `test.txt`: New-Item test.txt
8. Move the file named `test.txt` into `DirA`: Move-Item test.txt dirA
9. Contents of `test.txt`: 
```
hgieruhopudfghiofdfg
```
10. Make a copy of `test.txt` named `copy.txt` in `DirA`: Copy-Item test.txt copy.txt
11. View the contents of `DirA`: Get-ChildItem
12. Make a copy of `test.txt` in `Dir B` named `fodder.txt`: Copy-Item test.txt C:\Users\Garrett\DirA\Dir B\fodder.txt
13. Delete / remove both `fodder.txt` AND `Dir B`: Remove-Item "C:\Users\Garrett\DirA\Dir B\fodder.txt", "C:\Users\Garrett\DirA\Dir B"

## Citations

To add citations, provide the site and a summary of what it assisted you with.  If generative AI was used, include which generative AI system was used and what prompt(s) you fed it.



