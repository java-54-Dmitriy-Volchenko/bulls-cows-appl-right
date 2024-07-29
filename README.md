# bulls-cows-implementations
## Implementation base for Bulls and Cows application core
## Functional Classes
### Move
  DTO class for transferring client sequence from the client to the server
### MoveResult
  DTO class for transferring move's result from the server to the client
### Game
  Data about Game <br>
  Move's processing
### BullsCowsService
  Interface as abstract layer of any BullsCows controlling implementations
### BullsCowsMapImpl
 The interface implementation based on HashMap containing associations of game ID's and game states
## Dependencies
No dependencies