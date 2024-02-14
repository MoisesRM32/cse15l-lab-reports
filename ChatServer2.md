![Image](part1)
I set the variable `String tempString` to store the data in the website so it doesn't ruin the strings that I already have on the website. `Messages` store our messages and then `Username` stores the users. I have the same stuff from the number server basing how I got to add messages or `strings`. The fields that are being altered by the `handleRequest` arguments are `s` and `user`. The `port` field is altered from the `ChatServer` arguments.

![Image](part2)
The `url.getQuery().split("=")` splits the queries getting both `strings`. Then set the parameters `[0]` and `[1]` to  `Username` and `Message`. Then I set both of them to `tempString` and returned a line with `\n` with the colons `: `. Then at the end returned the temp array updated with the original array. The fields that are being altered by the `handleRequest` arguments are `s` and `user`. The `port` field is altered from the `ChatServer` arguments.

![Image](part3)
This is the stuff that was originally in the `NumberServer` server start-up with the port number from `Server.java`. 

![Image](output2)
The fields that are being altered by the `handleRequest` arguments are `s` and `user`. The `port` field is altered from the `ChatServer` arguments.


![Image](Output1)
The fields that are being altered by the `handleRequest` arguments are `s` and `user`. The `port` field is altered from the `ChatServer` arguments.

![Image](ls.ssh)

Summing up the week. I learned the `.sh` command is a shell script command and is the same as a regular terminal. `bash` stands out for born again shell which I didn't know before I just thought it was meant for some testing thing in `JUNIT`. `ser -e` command allows you to catch where the error comes from when you code continues.
