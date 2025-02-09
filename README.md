## Class-31-TailwindUpdate (Version 4)
###  Installing Tailwind CSS with the Tailwind CLI tool
1. Check the updated version of **Node.js** from the link: https://nodejs.org/en/download
   ![image](https://github.com/user-attachments/assets/570ec84c-8a01-41c7-b4d9-4276dca521ba)



2.  Check the version of **Node.js** which is installed in the system (PC) and Update it (if required, version is not Up-to-date):
      *  Go to the Command Prompt >> Type "node -v"
     ![image](https://github.com/user-attachments/assets/b48bc2c8-c935-4444-a404-396520efca84)


4.  Create a folder (avoid using "#") and Open in VS Code
5.  Now, Open the terminal (press "Ctrl + ~" or, click on Terminal from the top menu)
6.  Select "gitbash" and remove "powershell"
   ![image](https://github.com/user-attachments/assets/c64cf68c-6e3f-45ee-804a-3561e976f4bf)
7.   Then Type "npm install tailwindcss @tailwindcss/cli" in the terminal which installs Tailwind and creates "node_modules", "package-lock.json" and "package.json"
   ![image](https://github.com/user-attachments/assets/75ac1531-9174-4499-82ee-5c3c95d6b651)
8. <ins> Import Tailwind in your CSS </ins> **>>** Now, Create a folder **"src"** in the root, then create a file **"input.css"** inside the **src** folder. Write the line:
   **@import "tailwindcss";**
   ![image](https://github.com/user-attachments/assets/03a7c728-7f56-4bc8-a155-ab59ec2fa6ce)

9.   <ins> Start the Tailwind CLI build process </ins> >> Type **"npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch"** in the terminal which creates **"output.css"** file in the **src** folder.
    ![image](https://github.com/user-attachments/assets/97b39e17-91db-4722-b0af-9344768ad70a)

10.   Now, create **index.html** file in the root folder:
    ![image](https://github.com/user-attachments/assets/d1f902d6-fd53-42ba-9569-6c9072478313)
11.   Then, link the output.css file with the project:
    ![image](https://github.com/user-attachments/assets/525699bb-61e0-4405-bece-312d2031368a)
12.   Test the connection of Tailwind CSS with the Project:
    ![image](https://github.com/user-attachments/assets/b9aee5f3-627b-4997-96b7-b7fa967cffc7)

> [!IMPORTANT]
> Type the watch command if the project is restarted/ shut down/ stopped.
![image](https://github.com/user-attachments/assets/0846e018-93b2-4309-9544-15576e46c1a0)





 
