If you've seen my resume you may notice a "Lua Library Expansion" which isn't on my github. This is because the code contains some technqiues which the community surrounding the game it was originally written for would be able to create some fairly harmful scripts using.
Some examples of this include: 

Player de-networker- The game networks player objects on the client as opposed to the server, because of this you can effectively remove other players from servers without them knowing.
Inventory duplicator- As the game networks players on your client you can effectively read other peoples entire player files and duplicate them.
Many, many types of crash scripts- A simple example of this utilizes a method within the dll allowing for invalid characters to be displayed on other users screens with the in-game chat function. This will, of course, crash all users who display this character.

For these reasons, and more I have decided not to make the source code for this dll public but am open to sharing it at request via email to potential employers or colleagues.
