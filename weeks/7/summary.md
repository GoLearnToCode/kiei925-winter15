# Goals

* Continue with validations and error handling
* Learn about the "flash" - alert and notice
* User authentication and authorization
  * Use a ```sessions_controller``` to manage login and logout
  * Understand the advantages of using cryptographic hash security (BCrypt) over a plain-text password
  * Implement BCrypt in Rails using ```has_secure_password```
  * Learn to maintain statefulness using cookies and the Rails built-in ```session``` hash
  * Understand the purpose of the ```ApplicationController``` and how to implement methods that are available throughout the application
  * Learn to use ```before_action``` and ```skip_before_action``` to manage application flow