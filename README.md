# Super Hot Potato

## There are potatoes...

Potatoes shoots each other with laser's gun.
Time is depending on movement of each potato, when potato doesn't move time slows down some part.

Each potato has roast level, which raises when laser hits it or when it doesn't move too long. When roast reaches max level potato roast to death. 

Lasers might bounce of the wall or some obstacles.

Game is 2D with top view.

## Synchronization of our potates

Every player has own instance of client application that connects with server.

Client app is responsible for rendering and predicting position of objects based on latest state of object, as well as updating state of objects received from server.

Server receives events from clients, processes it and sends back information about new state of objects.

