# GetUser Method
Define GetUser Method in server application

## Ideas, which type of result we need

Maybe get a list from a List Object, which is defined on the Servers side. A list Object is an array, where Objects are stored.
The list can be filled with a .add command on the server side, with the user informationes. These List can be called by a get 
operation of a function. The better way is to craete a JSON Array, which can be implemented in the generic

This will be an export from the database with a select statement in the backend.

We need an unique userid, to identify the user correctly.

We also need a result for each channel. A count from each Group will be fine.

## examples, which result i think what we need

The result of the UserList can be written in the msg string of the JSON,
so that we don't need to modify the JSON Scheme.

## Result

Delimiter will be | between Usernames, that we can filter each user, which is | seperated , to list the user. A user does 
not contain a | symbol in the username.

method: getUsers #channelxyz to give a list of the channel. If there is no direct channel #  called in the method, all user 
will be listed.
