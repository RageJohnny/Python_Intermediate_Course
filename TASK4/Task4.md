## Task 4: Family Tree App with GUI and Database

<strong>Requirements:</strong>

<strong>Database Integration:</strong> Use SQLite as your database backend. The database should store and retrieve information about family members and their relationships.

<strong>Class Design:</strong> At a minimum, you should have classes for Person and FamilyTree. The Person class should have attributes like name, job, gender, and any other parameters you find relevant. The FamilyTree class should contain methods to interact with the database - adding a person, searching for a person, etc.

<strong>GUI using tkinter:</strong> Build a simple GUI where users can:

* Add a new person to the database.
* Search for a person and display their details.
* Error Handling: Your GUI should handle cases where a user tries to add a person with the same name (since names in this version of the exercise are considered unique) and provide appropriate feedback.

<em>Optional Features:</em>

Consider adding more functionalities like:

* Displaying the entire family tree in a list or tree view.
* Adding relationships via the GUI.
* Visualizing the relationships.
* Deleting or updating person details.


Your final solution should be a blend of object-oriented principles, database operations, and GUI development. Ensure proper separation of concerns, i.e., database operations should be separate from GUI code for modularity and maintainability.