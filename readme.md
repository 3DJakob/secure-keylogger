# Secure keylogger
This project is a proof of concept of a keylogger server that registers user input and shares it over https. The client can then display and search the logs for relevant information like passwords and website urls. This project was made as part of a network security course.

![Alt text](screenshot.png?raw=true "Screenshot")

## To run the project
1. Download the repository.
2. Start the keylogger server by running `npm install` followed by `npm start` in the server directory.
3. Start the client to view the logs by running `npm install` followed by `npm start` in the client directory.
4. Visit `localhost:3000` to view the logs. Reload the window to fetch new logs.

You can also view the logs from another computer on the local network by running the client on that computer and changing the url in the client code [here](https://github.com/3DJakob/secure-keylogger/blob/06b6d345b91d734ea23f3c7ad048bbe176d4966a/client/src/components/Logs.js#L68) to the server computers local ip address.
