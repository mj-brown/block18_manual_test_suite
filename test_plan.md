# Puppy Bowl Test Plan

## Project Introduction
The Puppy Bowl is a mini-game that allows users to add and remove cute puppies to a game roster.
### Main Page
- [ ] Expect there to be a formatted list of available players 
- [ ] Expect each player to have two (2) buttons next to the name on the roster 
- [ ] Expect there to be a ***See details*** button 
- [ ] Expect there to be a ***Remove*** button to remove players from the main list
- [ ] Expect there to be the player's name, breed, and assigned team listed when ***See details*** button is clicked
- [ ] Expect there to be the option to assign a team if unassigned is present when ***See details*** button is clicked
- [ ] Expect there to be the option to assign a team if unassigned is present when ***See details*** button is clicked
- [ ] Expect there to be a large image of the player when ***See details*** button is clicked
- [ ] Expect there to be a button that takes that goes back to the main list when ***See details*** button is clicked
- [ ] Expect there to be an editable form to add a new player
- [ ] Expect the roster to show all of the players on the same team as the selectded player.
- [ ] Expect each player to have a dropdown available when selected to change to a different team.
- [ ] Expect the assigned team to immediately change on the roster if a new team is selected.

### Adding Player(s)
- [ ] I would expect the form to have two (2) inputs: Name and Breed, and a ***Submit*** button
- [ ] I would expect the Name input to have a character limit of 15 characters.
- [ ] I would expect the Name input to throw an error if any non-letter was given.
- [ ] I would expect the Name input to throw an error if any name that was currently a player name was given.
- [ ] I would expect the Name input to verify that the name was input correctly.
- [ ] I would expect the Breed input to throw an error if any non-letter was given.
- [ ] I would expect the Breed input to have a maximum allowable character limit of 34 characters.
- [ ] I would expect the Breed input to have a minimum allowable character limit of 3 characters.
- [ ] I would expect the Breed input to have a minimum allowable character limit of 4 characters.
- [ ] I would expect an error to be thrown if the ***Submit*** button is clicked with an empty name or breed field.
- [ ] I would expect the player data to be added to the roster when the ***Submit*** button is clicked.
- [ ] I would expect there to be an input to provide an image URL when adding the player.
- [ ] I would expect an error to be thrown if an unvalid URL is provided.
- [ ] I would expect the provided image to be linked to the player profile on the roster.

### Removing Player(s)
- [ ] I would expect that when the ***Remove*** button is clicked the player is removed from the roster.