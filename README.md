<i>version control</i>

# Keychain Collection

## Base Requirements
- The project shall be written in Java.
- The project shall have a GUI interface.
- The project shall use JavaFX for the GUI.
- The project shall read from a file.
- The project shall write to a file.
- The project shall update a file.

## Collection Requirements
- The project shall focus mainly on one type of collection (coins, stamps, comic books, …)
- The project shall be able to search for an item in the collection.
- The project shall be able to filter the collection.

## Additional requirements
- User can go back to the welcome screen / switch between list/map view.

## Design
Welcome Page with option to choose to view keychains as a list or map.
List shows keychains by picking a state. The system shows the user a fun fact. Once a state is picked, user can scroll through pictures of keychains. The user can add and remove keychains at the list view. The user can add and remove a fun fact. The fun fact will write to a file.

Map shows the 50 USA states. Once the user chooses a state, all the keychains of that state are displayed. The user can add and remove keychains at the map view.
