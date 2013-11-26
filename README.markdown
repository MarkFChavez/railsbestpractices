Rails Best Practices
	== from the Book "Rails AntiPatterns"

General: Create modules/classes to isolate responsibilities for the models

1. Law of Demeter (delegation)
	* use delegation
2. Push all find() calls into finders on the model
	* use scopes or class methods
3. Keep finders on their own model
	* single responsibility principle kind of stuff
4. Delegate Responsibility to New Classes
5. Make Use of Modules
6. Reduce the size of large transaction blocks
	* use callbacks/filters