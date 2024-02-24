this is just a test.  I am trying to use codespaces with swift.


Added tasks.json and launch.json to run swift script with the run button.  see https://stackoverflow.com/questions/43836861/how-to-run-a-command-in-visual-studio-code-with-launch-json


Question:  How can I use my IPadPro to develop software while on mobile.  

Answer:  Using github codespaces I can create a unix vm (container) in codespaces.  While I cannot run the UI, I can run the unit tests for the business logic.  The first success came by running 'swift' from the terminal of the container.  Better still would be to be able to run the tests via F5 or the run button.

Loading "F5 Anything" into vscode and updating the launch.json to include a launch command, I can now run the test from the buttons.
