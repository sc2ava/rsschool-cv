# CV

**First name:**    Alexander  
**Last name:**    Volchek

**Contacts:** 
Country: Belarus
City: Minsk
E-mail: [sc2ava@gmail.com](https://gmail.com)  
GitHub: [GitHub:sc2ava](https://github.com/sc2ava)  

## **About me**  
I want to get good job satisfaction, develop and acquire professional skills, gain new experience and improve my English.  
Material benefits: official salary and bonus, social package, learning opportunity, career growth.  
Strengths: optimism, persistence, love for little things.
Creative, structured, logical, tactical and strategic thinking.
I also have such a character trait as coming up with solutions in an extraordinary or creative way.  

## **Skills:**
**Programming languages:**  
  

|*(Advanced level)* |*(Superficial knowledge)*|
|-------------------|-------------------------|
|Python             |PHP                      |
|JavaScript         |C#                       | 
|HTML               |C++                      |   
|CSS                |Visual Basic             |     
  
**DBMS:** *(Superficial knowledge)*    
MySQL
MSSQL  
**Library** *(Superficial knowledge)*    
Selenium WebDriver  

## **Code** 

*Saving wallpaper Windows Spotlight*

```Python
import os
import random
import shutil

#Copy all files and insert new catalog
scr = r'%LOCALAPPDATA%\Packages\Microsoft.Windows.ContentDeliveryManager_cw5n1h2txyewy\LocalState\Assets'
dst = r'D:\winScreen'
#ignore check information
shutil.copytree(scr,dst,dirs_exist_ok=True)

#rename and type .jpg
os.chdir(r'D:\winScreen')
z = os.listdir('D:\winScreen')
for x in z:
    os.rename(x, str(random.random() * 100) + '.jpg')

#sort for size and delete another files 
from PIL import Image
for x in os.listdir('D:\winScreen'):
    if(Image.open(x).size)!=(1920,1080):
        os.remove(x)
``` 

*Input and output with abbreviated initials*

```Python
def ID_Fnames(msg):
    Caracterslist = "-"
    input_data = input(msg)
    if not input_data.isspace() and 1 < len(input_data) and (input_data.isalpha() or any(c in input_data for c in Caracterslist)):
        return input_data
    return ID_Fnames("Invalid input. Last Name:")

def ID_Names(msg):
    Caracterslist = "-"
    input_data = input(msg)
    if not input_data.isspace() and 1 < len(input_data) and (input_data.isalpha() or any(c in input_data for c in Caracterslist)):
        return input_data
    return ID_Names("Invalid input. First name:")

def ID_Lnames(msg):
    Caracterslist = "-"
    input_data = input(msg)
    if not input_data.isspace() and 1 < len(input_data) and (input_data.isalpha() or any(c in input_data for c in Caracterslist)):
        return input_data
    return ID_Lnames("Invalid input. Middle name:")

def ID_FNL():
    surname = ID_Fnames("Last Name: ")
    name = ID_Names("First name: ")
    middlename = ID_Lnames("Middle name: ")
    return surname.title() + ' ' + name.title()[0] + '.' + middlename.title()[0]+'.'

print(ID_FNL())
```

## **Work experience**  

## **Education**  
Intensive courses - Skillbox, Geekbrains  
Higher special education - profession: programmer  
School
## **Language skills**  
English at level A2. Basic language practice: reading technical documentation and searching for technical information in any available form.