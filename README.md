<h2>Project Description</h2>

As a security professional, as part of my job I may be required to regularly update a file that identifies the employees who can access restricted content. The contents of the file are based on who is working with confidential records. Employees are restricted access based on their IP address. There is an allow list for IP addresses permitted to sign into the restricted subnetwork. There's also a remove list that identifies which employees I must remove from this allow list.
<br/><br/>
My task is to create an algorithm that uses Python code to check whether the allow list contains any IP addresses identified on the remove list. If so, I should remove those IP addresses from the file containing the allow list.

<h3>Steps</h3>

The steps that I need to take to accomplish this task:
1. Open the file that contains the allow list
2. Read the file contents
3. Convert the string into a list
4. Iterate through the remove list
5. Remove IP addresses that are on the remove list
6. Update the file with the revised list of IP addresses
<br/>

<h2> This is an algorithm for file updates in Python</h2>

<h3>Step 1- Open the file that contains the allow list</h3>
<img src="https://i.imgur.com/6poa4EG.png" alt="image"/>

<h3>Step 2- Read the file contents</h3>
<img src="https://i.imgur.com/q1FhMci.png" alt="image"/>

<h3>Step 3- Convert the string into a list</h3>
<img src="https://i.imgur.com/zN832J7.png" alt="image"/>

<h4>Step 4- Iterate through the remove list</h4>
<img src="https://i.imgur.com/KbrKOpd.png" alt="image"/>

<h4>Step 5- Remove IP addresses that are on the remove list</h4>
<img src="https://i.imgur.com/zvdQE6Y.png" alt="image"/>

<h4>Step 6- Update the file with the revised list of IP addresses</h4>
<img src="https://i.imgur.com/jSfNott.png" alt="image"/>

<br/>
In summary, with this code I can create a function that I can pass in a file path of a .txt file containing a list of items that I want to keep, and pass another list of items that I want to remove from the first list. The function will convert the text (string) into a more readable format (list) and manipulate the contents and then convert the list back into a string to be saved as an updated .txt file. 
