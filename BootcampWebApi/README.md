# ErhanAliYukselen-Homework2

## The Web Api application the second homework of Arvato .Net Bootcamp

## Important note : Open terminal by right clicking on bootcamp web api project. 
## Type this command in terminal 'dotnet ef database update'
- This command will update your database and fetch sample data
- 3 sample users and bootcamps have been defined, with id's 1-2-3

<h1>Description</h1>


- There are 2 web api in our project.
- They are divided into admin and bootcamp.
- The actions you can do as an admin; add and delete bootcamp, approve, reject or delete participants.
- The operations you can do in the bootcamp api are; registering as a member, seeing the all bootcamps by listing, registering for the bootcamp.

# WebApi App Screenshots and Use

<h3>Starting</h3>

![image](https://user-images.githubusercontent.com/102170410/175376409-117b5bbb-522c-4837-830c-cb0a8c42ebda.png)

To add bootcamp, we delete the id part and write the bootcamp name we want to add where it says string

![image](https://user-images.githubusercontent.com/102170410/175377095-31ff9f85-bb2e-4c54-aab6-72de04741db9.png)

When we press the execute button, the bootcamp is automatically added with its id. 

![image](https://user-images.githubusercontent.com/102170410/175377397-f313cabc-eca1-4faa-90a8-be0e460407f7.png)

When you execute the operation by typing the id of the bootcamp you want to delete, the bootcamp will deleted.

![image](https://user-images.githubusercontent.com/102170410/175378050-0f5566ff-c81a-4718-9259-155f5da5cfec.png)


You can confirm by typing the id of the user you want to confirm. The status of the people you approve, which was initially false, will appear as true.
In the same way, you can disapprove or delete by entering the user's id.

![image](https://user-images.githubusercontent.com/102170410/175378308-fd21615c-f4ce-4751-9d56-5fa698aed73b.png)


<h3> BootcampApi </h3>

Delete the id part that comes by default and enter your name and you will be registered successfully

![image](https://user-images.githubusercontent.com/102170410/175379212-d922320d-5341-4100-a12c-2e381a591cac.png)


You can view all bootcamps from this section.

![image](https://user-images.githubusercontent.com/102170410/175379341-fa621645-0e56-465c-9b8f-f6a3f8febb47.png)

You can view a single bootcamp you want to see by just typing its id

![image](https://user-images.githubusercontent.com/102170410/175379496-7b0b582c-0ebb-417b-b07b-435b2569ec28.png)

You can register by typing your own id and the id of the bootcamp you want to join.

![image](https://user-images.githubusercontent.com/102170410/175379620-2ba3bb3c-77b0-4e10-beea-02e26c6e91d8.png)



