# OpenAI DALL-E 2 Web Application Clone

I created this clone using the following YouTube tutorial by Adrian Hajdin: https://www.youtube.com/watch?v=EyIvuigqDoA&t=7180s.
The assets were downloaded from https://drive.google.com/file/d/12ZCrmvvqrI2KONvpm1fWpf2pKkGlgIpE/view and other required components
of the code from https://gist.github.com/adrianhajdin/b2264e1f443a0003d6947549b9e07ec5.

This clone of OpenAI's DALL-E 2 application will allow you to create stunning pieces of digital art using your imagination.

Users can run the application on a localhost server on their computer by following the instructions below:

# Install
Clone the repository and install the npm package manager:
```powershell
git clone --depth 1 --branch main https://github.com/declanl482/DALL-E-Clone.git your-project-name
cd your-project-name
npm install
```
# Setting up the client-side environment:
Move into the client folder:
```powershell
cd client
```
Execute the Vite build tool and connect to a Vite development server using the following command in the client directory:
```powershell
npm run dev
```

# (For developers) Setting up the server-side environment:
In a separate terminal, move back into your project folder, then into the server folder:
```powershell
cd your-project-name/server
```
Execute the nodemon development tool, which automatically restarts your Node.js servers for you when you make changes to your server-side code,
using the following command in the server directory:
```powershell
npm start
```
# Running the application:
Visit http://localhost:5173/ in your web browser.
