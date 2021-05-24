![Cover](https://github.com/karina-anggraeni/Sayur-Mayur-Mini-App/blob/main/Sample%20Image/Sayur%20Mayur%20-%20Cover.png)

This is a small assignment project I did with my amazing friend and partner Mega Alam (you could check out her LinkedIn profile [here](https://id.linkedin.com/in/mega-alam-777448164)) when we were students at Purwadhika.
The purpose of this assignment is to help us apply **CRUD** (Create, Read, Update, Delete) logic to manipulate data stored inside a **list**.

![Code](https://github.com/karina-anggraeni/Sayur-Mayur-Mini-App/blob/main/Sample%20Image/Sayur%20Mayur%20-%20Code.png)

### **Intro**
Mega and I love to eat our vegetables, so we decided that the application is going to be a stock-opname for vegetables. We called it **"The Sayur-Mayur Application"**. There are a few vegetables already listed in the app, which are: 'bayam', 'kangkung', 'bawang', 'kangkung', 'sawi', 'wortel', 'bayam', 'terong', 'wortel', 'kentang', 'terong', and 'selada' (all in consecutive order).

When you first run the application, it will require a password. If you input the right password (in this case, we set the password to "hai"), you will be directed to the main menu interface. Inside the main menu, the user will be able to choose between five alternate menus; to see the available stocks (**read**), to input new stocks (**create**), to make changes to existing stock (**update**), to delete stocks (**delete**), or to exit the application.

The user is given four chances as the limit to input the right password. When the limit is exceeded, the application will automatically close.

### **Read**
When selected, this submenu will return the names of all the vegetables available in stock. If the stock is empty, the user will receive a notification message.

### **Create**
When selected, this submenu will give the user an input prompt. If the user inputs a vegetable name that already existed, they will receive a notification message; to keep the new data (so there will be more than one vegetable with said name) or to discard the data. We did some error handling in this part so the user will only able to input alphabetical data.

### **Update**
When selected, this submenu will also give the user an input prompt. The program will check whether the inputted data exists in the initial stock list or not. If the inputted name exists, the program will make modifications to the vegetable name listed and return a message when the stock is updated. If the inputted name does not exist, the user will also receive a notification message.

### **Delete**
The concept of this submenu is quite similar to the 'update' submenu. The user will need to input an existing vegetable name to be able to delete it from the list.

You can see the full code in the **SayurMayur_CRUD** file.
