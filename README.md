# Ex1
# Authors : 
* Souffir Ilan Meyer : 342615648
* Boritsky Jonatan : 207254194

# Subject
We were asked to write commands for our own shell and then test them.

## How to run the project ?
First of all, you need to write this command when you open the terminal of the folder : 
```
make all
```
and then :
```
./myshell
```

## 1) > and >>
<p align="center">
  <img align="center" width=60% src = "https://github.com/ilan2505/matala1/assets/55143087/d4f3fcfb-fb57-413a-b132-649d06701d14"/>
</p>
<p align="center">
  <img align="center" width=60% src = "https://github.com/ilan2505/matala1/assets/55143087/a947e81d-0535-4ea6-87e0-abe96c11f66f"/>
</p>
<p align="center">
  <img align="center" width=60% src = "https://github.com/ilan2505/matala1/assets/55143087/f93e91ec-7b83-4d30-bcfd-2c6ed68a67ef"/>
</p>
<p align="center">
  <img align="center" width=60% src = "https://github.com/ilan2505/matala1/assets/55143087/c42fcd63-ddb3-4ecf-b4de-9f053860942b"/>
</p>

### an other exemple of >> :
<p align="center">
  <img align="center" width=60% src = "https://github.com/ilan2505/matala1/assets/55143087/c22eef90-4022-4306-8920-078186b01622"/>
</p>
<p align="center">
  <img align="center" width=60% src = "https://github.com/ilan2505/matala1/assets/55143087/de300ee2-e993-4f27-995b-4cb0ec9b2e78"/>
</p>

## 2) Command to change the cursor (prompt)
<p align="center">
  <img align="center" width=70% src = "https://github.com/ilan2505/matala1/assets/55143087/0e8775de-4788-46c6-a0d2-855add3dffc5"/>
</p>
We can see that we change from "myshell" to "hey".

## 3) "echo" : prints the arguments
<p align="center">
  <img align="center" width=50% src = "https://github.com/ilan2505/matala1/assets/55143087/14edd6c3-1b91-4e29-be15-8bd7c383078b"/>
</p>

## 4) "$?" : prints the status of the last command executed
<p align="center">
  <img align="center" width=50% src = "https://github.com/ilan2505/matala1/assets/55143087/7b6b31f6-2412-44f7-8158-6830f4c3d0a4"/>
</p>
In our exemple it writes 0 for the last command executed and 256 for the last command that not works.

## 5) "cd" : changes the shell's current working directory
<p align="center">
  <img align="center" width=50% src = "https://github.com/ilan2505/matala1/assets/55143087/879da7d8-6375-4cdf-8837-d2d338d48600"/>
</p>
With the command "cd .." we are going to the previous directory and then with "cd Desktop" we enter into the Desktop directory and the same for Matala1, and if the directory not exists ("cd Exxx") we have a failed message.

## 6) "!!" : repeats the last command
<p align="center">
  <img align="center" width=50% src = "https://github.com/ilan2505/matala1/assets/55143087/db37df27-348d-4b69-9fd8-87184ca169a7"/>
</p>
if we don't have a last command, it does nothing.

## 7) "quit" : exits from the shell. AND 8) "ctrl+c" : the program will not terminate but will print the message "you typed Ctrl-C"
<p align="center">
  <img align="center" width=50% src = "https://github.com/ilan2505/matala1/assets/55143087/3d705cb9-7e34-48ea-a931-b1bdace1ee67"/>
</p>

## 9) "|" : pipe
<p align="center">
  <img align="center" width=50% src = "https://github.com/ilan2505/matala1/assets/55143087/3417bc0a-04bc-4000-9d2f-b160aadfda89"/>
</p>
counts how many lines there is when i write ls -l :
<p align="center">
  <img align="center" width=50% src = "https://github.com/ilan2505/matala1/assets/55143087/83f99fe8-59d1-4f01-bb81-a2cf9c200421"/>
</p>
counts how many times there is "hey" in file.txt :
<p align="center">
  <img align="center" width=50% src = "https://github.com/ilan2505/matala1/assets/55143087/0f77d19d-1d7e-4178-bacf-74514df91415"/>
</p>
finds all .c files, displays their sizes and sorts them by size :
<p align="center">
  <img align="center" width=50% src = "https://github.com/ilan2505/matala1/assets/55143087/0d9a8aa7-40f2-41b6-8c01-b3fe6affe49e"/>
</p>

## 10) Adding variables to the shell
<p align="center">
  <img align="center" width=50% src = "https://github.com/ilan2505/matala1/assets/55143087/ace8f5dd-23a9-449d-83c8-24de9488a190"/>
</p>

## 11) "read" command
<p align="center">
  <img align="center" width=50% src = "https://github.com/ilan2505/matala1/assets/55143087/49ad82be-07ee-403f-b58e-84e2019b0a03"/>
</p>

## 12) Support flow control :IF/ELSE.
### Exemple num 1 : if a file.txt exist or not
<p align="center">
  <img align="center" width=50% src = "https://github.com/ilan2505/matala1/assets/55143087/162c6878-dfef-4b43-afc3-15a7a82db2aa"/>
</p>

### Exemple num 2 : if the date is Friday or not
<p align="center">
  <img align="center" width=50% src = "https://github.com/ilan2505/matala1/assets/55143087/6ebf52f8-7579-41c3-95ea-d1704f3a80a6"/>
</p>

## Run exemple from the task1.pdf
<p align="center">
  <img align="center" width=50% src = "https://github.com/ilan2505/matala1/assets/55143087/dcaf0a36-da2e-494a-8c79-872e12d37e7e"/>
</p>
<p align="center">
  <img align="center" width=50% src = "https://github.com/ilan2505/matala1/assets/55143087/9df0ad11-30cb-44ca-85c2-299175ff3427"/>
</p>



