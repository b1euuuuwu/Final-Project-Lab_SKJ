# Rock, Paper, Scissors Game Using Python Socket Programming and tkinter GUI

This project is made by (names of group members) to be submitted as the final group project for the Computer Systems and Networking Lab Class taken in the 3rd Semester.



###### Things to consider before running application

1. Make sure both server and client are under the same network connection

2. Change IP address in the code to the current IP address both computers are using in these lines of code (change variable *HOST_ADDR*)
   
   ###### *game_server.py*
   
   ```python
   server = None
   HOST_ADDR = "0.0.0.0" #change depending on the wifi used
   HOST_PORT = 8080
   client_name = " "
   clients = []
   clients_names = []
   player_data = []
   ```
   
   ###### *game_client.py*
   
   ```python
   client = None
   HOST_ADDR = "0.0.0.0"
   HOST_PORT = 8080
   ```

###### These are the steps to running the application

###### *run server*

```bash
python3 game_server.py
```

###### *run client twice on different computers with this command*

```bash
python3 game_client.py
```
