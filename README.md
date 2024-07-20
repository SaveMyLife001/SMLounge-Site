Discord Document Composer
==========================

* **Command Handler**
	+ Handles incoming messages from Discord
	+ Parses message content to extract command and arguments
	+ Calls corresponding command function
* **Command Functions**
	+ **Ping Command**
		- Responds with a "Pong!" message and latency information
	+ **Sum Command**
		- Calculates the sum of provided numerical arguments
		- Responds with the calculated sum
	+ **...** (additional command functions can be added here)
* **Document Composer**
	+ Generates documents based on command output
	+ Supports various document formats (e.g., PDF, DOCX, TXT)
	+ Can be extended to support additional formats
