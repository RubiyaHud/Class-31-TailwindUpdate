## Class-31-TailwindUpdate (Version 4)
###  Installing Tailwind CSS with the Tailwind CLI tool
1. Check the updated version of **Node.js** from the link: https://nodejs.org/en/download
   ![image](https://github.com/user-attachments/assets/570ec84c-8a01-41c7-b4d9-4276dca521ba)



2.  Check the version of **Node.js** which is installed in the system (PC) and Update it (if required):
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

9.   <ins> Start the Tailwind CLI build process </ins> >> Type "npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch" in the terminal which creates "output.css" file in the src folder.
    ![image](https://github.com/user-attachments/assets/97b39e17-91db-4722-b0af-9344768ad70a)



 
