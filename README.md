# Phonebook-GUI
1. The project aims to create a graphical user interface similar to a phonebook, where you can add, delete, or edit contacts. A GUI (Graphical User Interface) is a digital interface where a user interacts with graphical components such as icons, buttons, and menus.


**2. Technologies Used**  

For this project, we used Python as the programming language—a flexible and easy-to-use language that provides developers with numerous free frameworks and tools. Within Python, we utilized the standard Tkinter library, which is very beginner-friendly. Tkinter offers features for building graphical user interfaces with windows, buttons, labels, text boxes, and more, allowing us to fulfill the project requirements.  

**3. Application Description**  

- **Interface**  
The main interface page allows users to view the contact list, where they can access the search bar as well as buttons for adding new contacts, editing existing ones, and deleting contacts.

![image](https://github.com/user-attachments/assets/ed99cd1c-7478-480b-8fe3-e7b2ec0c2b92)

During the registration process, the program will prompt the user to enter the name and phone number of the owner. During the login process, the program will check if both pieces of information have been entered, as a phone number cannot be added without specifying the owner, and vice versa. After validation, the data will be stored in the database and displayed in the contact list.

![image](https://github.com/user-attachments/assets/de783b84-052f-46a6-9106-71392d315b6e)

System Architecture

Library Import 
![image](https://github.com/user-attachments/assets/22c198d0-c279-4632-b31d-b3f1efdb2bef)
  **PhoneBookApp** is a simple phonebook application built using Tkinter, a graphical user interface (GUI) library for Python. Users can add, search, edit, and delete contacts.  

The application includes the following functionalities:  

1. **Graphical User Interface (GUI):**  
   - The application uses Tkinter to create a graphical interface with a main frame.  
   - There are three distinct frames for adding contacts, searching for them, and displaying them in a Treeview (a tree-like list) for viewing and interacting with contacts.  

2. **Adding, Editing, and Deleting Contacts:**  
   - Users can enter a name and phone number in the corresponding fields and click the "Add Contact" button to add a new contact.  
   - Contacts are displayed in the Treeview, where users can select a contact.  
   - Buttons are available for editing and deleting selected contacts.  

3. **Searching and Filtering Contacts:**  
   - A search field allows users to enter a search term, and the contact list will be filtered accordingly.  

4. **Sorting Contacts:**  
   - A method called `sort_contacts` sorts contacts by name, which can be triggered by a button or another GUI action.  

5. **Saving and Loading Contacts from a File:**  
   - Contacts are saved in a file named "contacts.txt" and can be loaded when the application starts.  
   - The file stores name and phone number pairs, separated by a colon (:).  

6. **Feedback and Status:**  
   - A label at the bottom of the window provides feedback to the user about the application's current status (e.g., "Contact added," "Contact deleted," "Contacts loaded," etc.).  

7. **Styling:**  
   - Uses `ttk.Style` to apply a stylized appearance to buttons and the Treeview.  

8. **Modularity:**  
   - The code is structured within a `PhoneBookApp` class, making it easy to understand and extend.  

9. **Main Loop:**  
   - The program starts and runs the main application loop using `root.mainloop()`.  

### **Conclusion:**  
This application allows users to add, edit, delete, and search for contacts while also saving them to a file. It serves as a simple example of a contact management application with a graphical user interface.



