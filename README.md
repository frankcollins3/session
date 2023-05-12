# session
hopefully a C program that interacts with:  pomodoro-session &amp;&amp; user-session 
goal output is:

prompt a user if theyre engaging in a session of some kind and for long how that session will be stored as session_length

create another prompt at session_length end to see if there are key concepts worth storing in a database

The third prompt accesses the system() and, upon user-specified data gathered from fgets() or scanf() input:
user_session does nothing since there is another session restarting, or does nothing in the event that there isn't a session going on but no logout/sleep 
user session sleeps or logs out.
user session shuts down

**bonus:**
create a postgres database table and column to allow for submitted string characters



// the app was only conceptualized through discovering: "// sudo shutdown -h +30" this sudo command & ability to specify time for shuttingdown/loggingout
such a command can be invoked in a C program with the "system()" function
