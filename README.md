![alt text](https://upangsms.phinma.edu.ph/upang/images/des_UIPEN_BG.jpg)
# Aims-PyExcel
<b>Aims PyExcel</b> is a python script capable of transferring grades from the grading portal (Aims) to an Excel File.. The script can show different worksheets containing the admission status, scholastic status, current school year and semester, subjects and sections, instructor, gpa and also the grades and more.. It is currently on work for some improvements and stable functionalities. The user needs to include his/her username, birth date and password for authentication of account, same as how they input their credentials in grading portal or the website where grades can be viewed... <br/>
The script is exclusively for the grading portal of <b>PHINMA-University of Pangasinan</b> only. You can navigate to the main portal (Aims) to view how it looks like to log in with an account. Check <a href="https://upangsms.phinma.edu.ph/upang/students/" target="_blank">Here...</a>
<br/><br/>
<b><u>Running the python script using Windows Powershell with the following command:</u></b><br/>
Command: <i>python upangsms.py -u (student ID) -b (birthdate enclosed with double qoutes) -p (password)</i>
<br/>
![alt text](https://user-images.githubusercontent.com/45601866/71725795-1f9fc280-2e70-11ea-8295-ecb937db4497.png)<br/>
<b>How to properly use the script:</b><br/>
Before staring, you must have a <b>Python</b> application installed in your system. Download it <a href="https://www.python.org/">here</a> and add the path where the python application is installed in the environment variables to further access python through command line.. After that install <i>requests</i> and <i>openpyxl</i> python modules using <i>python -m pip install</i> command using cmd. When all done you can now execute the command mention above. To expand more how to use it, follow this instruction below.<br/><br/>
Type <i>python</i>, space and the <i>python script file</i> in the command line and add the following parameters <b>-u</b>/<b>-U</b>, <b>-b</b>/<b>-B</b>, <b>-p</b>/<b>-P</b>, where -u/-U stands for <b>Username</b>, -b/-B is for <b>Birth Date</b> and -p/-P is for <b>Password</b>.<br/>
<b>Usage:</b>
<ul>
  <li><b>-U 01-1314-01233</b> *this is for the username, or the student id*</li>
  <li><b>-B "01|04|1994</b>" *enclose birth date with double qoutes and separate mm/dd/YY with | sign</li>
  <li><b>-P YourPassword</b> *if your password has space, enclose it with parenthesis*</li>
</ul>
Command: <i>python upangsms.py -U 01-1314-01233 -B "01|04|1994" -P YourPassword</i><br/>
and press enter to execute the script..<br/><br/>
<b><u>Excel File containing the transfered grades</u></b><br/>

![alt text](https://user-images.githubusercontent.com/45601866/71725800-229ab300-2e70-11ea-8a2c-0e9b21e389c4.png)
<br/>

# Converting Grades To Document Format
The script is also capable of converting the grades from the grading portal to a document type format *(.docx)*... You just have to add <b>--download</b> / <b>-d</b> / <b>-D</b> parameter at the end of the command when running the python script. The script will download an <b>HTML</b> file copy of your grades and will convert it into a document type format. Below is the image of a sample converted document format of grades from the grading portal... <br/>

![alt text](https://user-images.githubusercontent.com/45601866/71755812-784e7a00-2ec7-11ea-94be-14fec65aa1ee.png)
