## Project setup:
* -------------------------------------------------------
            Coffee-Store-Server 
* --------------------------------------------------------
- cmd>
- 1. mkdir coffee-store-server
- 2. cd coffee-store-server
- 3. npm init -y
- 4. npm i express cors mongodb dotenv 
- 5. create index.js file
- 6. code .
- 7. add on script> 'start': 'nodemon index.js'
- 8. nodemon index.js


* -----------------------------------------------------
            Coffee-Store-Client
* -----------------------------------------------------
- cmd>
- 1. npm create vite@latest coffee-store-client -- --template react
- 2. cd coffee-store-client
- 3. npm install react-router-dom localforage match-sorter sort-by
- 4. Go to the https://tailwindcss.com/docs/guides/vite
- 5. npm install -D tailwindcss postcss autoprefixer
- 6. npx tailwindcss init -p >>> Go to -- tailwind.config.js file and paste "content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],"  then go to --> index.css file and delete all and paste "@tailwind base;
   @tailwind components;
   @tailwind utilities;"
- 7. Go to : https://daisyui.com/docs/install/
- 8. npm i daisyui
- 9. code .
- 10. npm run dev

## CRUD with MongoDB
* -----------------------------------------------------------------------------
            Create a form
* ------------------------------------------------------------------------------
- using daisyUI for creating the form
- then add handle btn to get the data
- write the post method to the server code for passing the data to the server
- then fetch the data to the client code
* -----------------------------------------------------------------------------
            CRUD operation using MongoDB
* ------------------------------------------------------------------------------
- Go to the >> https://www.mongodb.com/docs/drivers/node/current/fundamentals/crud/ >> usage Examples>> Insert Operations>> Insert a Document 
- then write the code (server side) to send data to the db 
- Sometimes it through some error for fetch to data then we have to fixed the issue (go to the mongodb>> database access>> edit user>> select built in role as (read and write to any database))

- for checking data: go to >> database>> browser collection>> (yourDB)

<!-- Others -->
* for sweet alert >> go to >> https://sweetalert2.github.io/
>> npm install sweetalert2
>> import 
>> then use
* for creating img link >>go to imgbb
