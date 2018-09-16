How to setup library_system locally

1. When you are reading this it means you already downloaded the library_system.zip file in Github or in your email.

2. Extract the library_system.zip in any folder you want. But I would recommend to save and extract the file to your Documents folder.

3. Open XAMPP or LAMPP, then start Apache and MySQL

4. For Linux, open the library_system folder then right click on the whitespace and select Open in Terminal. It will open your Terminal with the directory of your library_system folder.

For Windows, open the library_system folder then right click on the whitespace and select Git Bash Here. It will open your Terminal with the directory of your library_system folder.

Another option for Windows, open the library_system folder then below the file menus you will see the long address bar where you can see the directory of yoour folder. Click there then type cmd then press enter. It will open your command line with the directory of your library_system folder.

5. In your Terminal, Git Bash or Command Line, type the code below then press enter:
php artisan serve

Wait for a few seconds then you will see
Laravel development server started: <http://127.0.0.1:8000>

6. Open your browser then type localhost:8000. You will able to access the library system


NOTE:
If you are going to register an account your role will be a normal User. It can borrow or return the book. If you want to access the admin page for more functionality you can change the role in the database or you can use the account I already created set as admin.

Admin
Email: cha@gmail.com
Password: 123456