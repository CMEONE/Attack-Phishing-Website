# Attack Phishing Website
Use this program to attack a phishing website and flood it with fake credentials

## Instructions
The program runs on node.js with the axios dependency for sending POST requests.
To install node.js and npm, please visit this website: https://docs.npmjs.com/downloading-and-installing-node-js-and-npm/

To install axios with npm, please run the following command in your terminal (command prompt on windows):

`npm install axios`

Then, to set the POST url to send the login credentials, download and open the `main.js` file. Scroll down to the part that looks like this:

`var url = "";`

Enter the url within the quotes:

`var url = "http://example.com/check.php";`

To find the POST url of a phishing website, scroll down to the section in this document titled "Finding the POST URL"

You may also need to edit the POST fields. If so, scroll down to the section in this document titled "Finding the POST URL"

After you put the URL, save the file. Then, open your terminal and use the `cd foldername` command to navigate to the file. The terminal will likely start in your home/user directory. To see the folders/files in the directory, you can use the `ls` command (macOS, Linux) or the `dir` command (Windows). For example, if I downloaded the file into my Downloads folder, I would run the following command:

`cd Downloads`

Finally, to run the program, run the following command:

`node main.js`

You will know that it is running when it tells you the usernames and passwords it is using. If the program can successfully send the usernames and passwords to the phishing site, it will also write "success" to the console. Otherwise, it will write "error" to the console.

## Finding the POST URL

## Editing the POST Fields
