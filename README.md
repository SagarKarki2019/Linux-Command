# Linux  Commands

### To List Directory

        ls

### To Print Working Directory

        pwd

### To Change Directory

        cd 


### To Goes One Directory Down

        cd .. 

### To Go Multiple Directory Down
Goes Two Directory Down You Can Even Do It Mutiple Time To Go Down Further

        cd ../.. 

### To Switch Directory From AnyWhere 
In This Second Command It's a Real Example For Switching Directly in Project Directory From AnyWhere
     
        cd /root/Username/Directory # This is just format


        cd /home/ayush/project 

### Switch Directory From AnyWhere ShortCut
If You Don't Want to Use ShortCut For This Use "~" which means “starting from the root directory” So The Updated Command Will be 

        cd -/project 

### To Come to Root Direcrory With One Command Use

        cd 


### To Create a New Root Directory 
Use The absolute path, to make sure that we create the ayush directory inside /root. Without the forward slash at the start will try to search the root in the current directory and if it can't find one it fails
 
        mkdir /root/ayush
    
### To Create Directory

        mdkir ayush

### To Create Multiple Directory

        mkdir dir1 dir2 dir3

### To Create Nested Directory
This created a parent directory inside it a child directory and inside it the grandchild directory 
" The -p stand for parent "
 
    mkdir -p parent/child/grandchild

### To Create Nested Directory With Verbose

This functions similary but given additional output when the directory is successfully created you can use it however you want like the the below three command which all perfor exact same thinf

    
    1- mkdir --parents --verbose parent/child/grandchild
    2- mkdir -p --v parent/child/grandchild
    3- mkdir -pv parent/child/grandchild


### To Create a Directory Name With Space Use THis 

Need to wrap the folder name in "" To create a directory name with space

    mkdir "This is the Folder name with space"

### To List The Current Directory And Store It In a File 

In this case i am using file name as container.txt which contains all the direcrory of the current direcory

    ls > container.txt


### To View The File We just create and added all the Direcrory Name In The Current Direcrory Use
Its Helps to View File

    cat container.txt 

### To Use echo
echo just prints its arguments back out again in this cade it will print the hello ayush 

    echo "hello ayush"


### To echo and append in the file
In this it just add its content the one and two .txt files to view it use cat like above

    echo "This is a test" > one.txt
    echo "This is a second test" > two.txt

### To Append Using enho
  

    echo "This is appended" >> append.txt


### To OutPut/ View Multiple files at once Use
In this case it will output these three files one by one 

        cat one.txt one.txt three.txt

### To Use Less Command
The command less combined.txt opens the file named combined.txt for viewing using the less command, allowing you to scroll through its contents page by page

        less combined.txt


### To Move a Specific File Inside a folder 
In this case ayush.txt is moved into the folder named dir using mv command 

        mv ayush.txt dir

### To Move The Back Into Parent Direcrory Use
This command move ayush.txt back in to the parent directory

        mv ayush.txt ..

### To Move The Multiple File 
In this case one.txt , two.txt , folder1 are moved to the last specified folder named x-folder 

        mv one.txt two.txt folder1 x-folder

### To Move Nested Files 
This command only moves the file name ayush.html which is inside CSS folder which is also inside the parent folder named web folder and the ayush.html is moved the the folder name web_folder which is specified at the last

        mv web/CSS/ayush.html web_folder
    

### To Move Nested Files and Folder 
This command moves the ayush.html file which is inside the parent folder web into the curent working directory

        mv web/ayush.html .

### To Rename Use 
This command renames the folder named one into two

        mv one two 

### To delete a Direcrory

        rm folder_name

### To remove non empty folder 

        rm -r folder_name


### To View Word Count Line Count And Character Count
In this example the this shows the line , word ,and 
character count of file name file.txt 

        wc file.txt  # This shows the line count word count and character count all in one 

        wc -l file.txt #This shows line count only
        wc -c file.txt #This shows character count only 
        wc -w #This shows the word count only 

###  To View Noumber of Files and Folders in Home Direcrtory 
This first code appends all the files and folders of home directory in file.txt and second command is used to show the line count of that same file which contains all the file and folders of the home directory  


        ls ~ > file.txt
        wc -l file.txt
        
ShortCut For This Same Functionaity In this case we dont need to create a tempporary file for viewing number of files and folders in the home directory

        ls ~ | wc -l

### Additional Info
- Instead of allowing long-lived terminal sessions with dangerous powers, require the user to specifically request superuser rights on a per-command basis. The key to this approach is a command called sudo (as in “switch user and do this command”).

### Command To Allows SuperUser Privilege For EveryNext Command After it 

        sudo su 


### To Make a File a Hidden FIle 
This command in this example makes this ayush.txt file a hidden file by renaming it with "." dot infront of it 

        mv ayush.txt .ayush.txt

### To List All The Files And Folders Including The Hidden Ones 

        ls -a

### To Know Who am i Use 

    whoami

### To find Out What a spectid command to do Use man 

    man cat

### To zip Use
THis command zip any specified files and folder into the specfic name in this case ayush.zip

        zip ayush.zip anyfileorfolder

### To Unzip  Use 
In this case it unzip the ayush.zip

        unzip ayush.zip

###  To View IpAddress

        ifconfig

### To View Memory of you device 

        free 



