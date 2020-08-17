## Vikas Sharma

The computer science program has been instrumental in laying down the best foundation possible to understand the fundamentals of computer and its computing capabilities. It provided opportunities to analyze complex computing problems and application of computing principles to understand solutions. It also facilitated in effectively communicating with the stakeholder to communicate the requirements. This helped in designing the solution and other aspects of the program. It further allowed to recognize professional responsibilities of an individual working in the field. This understanding grants better professional adherence to the field with respect to the legal and ethical aspect of it. It allowed better understanding regarding the software development process working with team irrespective of their location. The artifact enhanced accompanied better understanding of the skills already learned throughout the program. It was the first time working with the graphical interface, it allowed me to understand the necessary adaptation while transitioning to a specific aspect of a tool (NetBeans). The artifact enhancement project allowed me to get a better understanding and eventually resolving complex computing problem by breaking them down it into small easily resolvable tasks. 

### Zoo_Login_System (Upgrade)

A professional authentication system features robustness and reliability, this is the reason why information provided to get authenticated (Including other functionalities) is obligatory to be checked, compared, and measured to filter out any unauthorized activity (Inception of a Complex algorithm). Data is left ineffective if you cannot retrieve the saved data, thus data tagging allowed us to keep track of our data (Primary key feature was utilized for the purpose, which is unique for every entry). It grant us to retrieve information and saving new data into the table without any issues. The enhancement and the functionalities proposed for the artifact stipulated working with large number of data points, which were saved in different table’s appropriately. These tables along with supporting different functionalities of the artifact were connected with each other with a common columns (Common on the basis of the information they contained). These common columns could be manipulated to cross refer to these tables if needed to retrieve data.Working with these tables and the complex algorithm they supported allowed us to create a software which was functional, complex, reliable and robust for authenticating and also support other features of the artifact. The artifact is never finished as you have new features which you could incorporate into it and also our ever evolving understanding of the topic


```markdown
# Zoo_Login_System 
###(Check it out!!)

**LOGIN**

OLD Authentication System/Console based:

![image](https://user-images.githubusercontent.com/49931875/90374662-b2205b00-e028-11ea-9dcb-c9d7eb9d1ad0.png)

![image](https://user-images.githubusercontent.com/49931875/90374624-a2a11200-e028-11ea-9e6e-d83811818fd8.png)

NEW Updated System:

![image](https://user-images.githubusercontent.com/49931875/90349222-e6c2f100-dfed-11ea-80c1-8717c58da361.png)

- Show password button reveals or hide the password.
- Color gives a visual cue to the user of their location.
- You will get only '3' chances to get authenticated.

Other cases:
  
![image](https://user-images.githubusercontent.com/49931875/90350065-c2b4df00-dff0-11ea-916b-b2e82eb9ff95.png)

![image](https://user-images.githubusercontent.com/49931875/90350108-de1fea00-dff0-11ea-865c-7e75173e5a49.png)

![image](https://user-images.githubusercontent.com/49931875/90350144-04de2080-dff1-11ea-8fff-5558684f29da.png)
 
**ADMIN SPACE**

![image](https://user-images.githubusercontent.com/49931875/90349548-1f16ff00-dfef-11ea-901b-68c2c130bc29.png)

- Top left corner reflects the username and the date.
- Admin would atleast need the "Employee ID" to search their records.
- Once the record is found, selecting the record in the table would populate the respective textfield (For reference).
- To create a new "EMPLOYEE ID" you need to provide all the information mentioned in the form.
- To update personal section of the emplyee you can select the button shown in the specific section of the user information.
- Information would be updated depending on "Admin" selection.

Other cases:

![image](https://user-images.githubusercontent.com/49931875/90350208-36ef8280-dff1-11ea-8173-c4b6f558b814.png)

![image](https://user-images.githubusercontent.com/49931875/90350226-479ff880-dff1-11ea-83f9-bc39b87f4caa.png)

![image](https://user-images.githubusercontent.com/49931875/90350246-5686ab00-dff1-11ea-9722-54409bd2a961.png)


**VETERINARIAN SPACE**

![image](https://user-images.githubusercontent.com/49931875/90349818-f9d6c080-dfef-11ea-8762-39bea20b6149.png)

- Top left corner reflects the username and the date.
- Left hand side (red box) is the primary driver of the tab.
- Right hanf side (green box) is only used in the process of updating an appoitment only.
- Veterinarian would atleast need the "DOCTOR ID" to search all their appointments.
- Specific information should be provided to find specific appointment.
- Once the record is found, selecting the record in the table would populate the respective textfield (For reference).

Other cases:

![image](https://user-images.githubusercontent.com/49931875/90350293-8170ff00-dff1-11ea-8849-7e62fd99183b.png)

![image](https://user-images.githubusercontent.com/49931875/90350316-9ea5cd80-dff1-11ea-9fa3-0801926e59b8.png)


**Database**

- Providing a screenshot of the database and the tables utilized in the project
- Ignore some of the not allowed enteries in the database below as they were used while testing (They would be deleted eventually).

![image](https://user-images.githubusercontent.com/49931875/90350365-d280f300-dff1-11ea-85e7-f2e28720e1a8.png)

![image](https://user-images.githubusercontent.com/49931875/90373441-c400fe80-e026-11ea-8992-d7669b44986e.png)

![image](https://user-images.githubusercontent.com/49931875/90373510-db3fec00-e026-11ea-94ec-85e151e8fdb1.png)

![image](https://user-images.githubusercontent.com/49931875/90373709-34a81b00-e027-11ea-973b-f1d134cf8a84.png)

**Old Artifact Code Reviw**
- Please click the link to review the Code Review video

Video (Copy and paste the link):

https://drive.google.com/file/d/1KQ0BiHGfT3MANbzUPUngADEkGwTLG8Kr/view?usp=sharing

**Code Review**

- Code worked as intended it to be.
- IndexOutofBoundException needs to be rectified, Emplpoyee ID info section. 
- Primary key being wasted as the program runs, and some of the old entries would get deleted. It would result in primary keys released and unable to be reassigned due to their piculiar location. We need to ensure to keep track of which primary key gets released after deletion. The next allocation of the primary key should start with that instead of assigning a new primary key.
- Appointment section, unable to come up with a alternative to having the right hand side box for only updating the appointment. We could use just one box instead, but that seems too careless. 
- Was unable to asign foreign key to the tables, which would allow cross refrence functionality for connected tables.
- Login button and Enter key functionality, makes the code redundant. Would like to reduce it to one instance and refrence it for the other.

Video (Copy and paste the link):

https://drive.google.com/file/d/1wS37Q3H5YKqTh0uvOH5Pjo0jnxdPJxhj/view?usp=sharing

**Improvement Plans**

- Unable to assign the foreign key feature which would have allowed cross references to the tables easier.
- Primary key feature allows us to keep track of the data, but it cerates an issue where deleted primary key entries are rendered useless if they are not towards the end of the data present in the table.
- Had some issues with IndexOutofBound exceptions while working on Employee Id information, This could just be a minor glitch.
- Wanted to incorporate otherr functioonalities, ranging from login time out function.
- Creating a form which has all the information for the patients in one place in a form of a file, created chronologically.


### Support or Contact

Please feel free to contact me for further queries or any question.
Email: vikassharma12025@gmail.com
