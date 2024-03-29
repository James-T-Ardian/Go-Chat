# Go-Chat
Go-Chat is a websocket chat application which has a frontend written in Typescript using ReactJS (found in Go-Chat-Client directory) and Golang (found in Go-Chat-Server directory).

How to run locally: 
1. Make sure you have the appropriate versions for golang (1.18), npm (^8.3.1), and node (^18.12.1)
2. Clone this repository
3. Open Go-Chat-Server directory as root in an IDE (Preferably VSCode) and run "go run main.go" in the root terminal
4. Open Go-Chat-Client directory as root in a separate IDE (Preferably VSCode) window and run "npm install" then "npm run start" in the root terminal
5. Go to http://localhost:3000/
6. You can test the functionality of Go-Chat by having multiple tabs of http://localhost:3000/ joining the same room and sending messages to one another

Here is a gif that showcases the application: 

![screen-gif](./go-chat-demo.gif)