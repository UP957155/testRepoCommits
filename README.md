# testRepoCommits
test repo


The bot manager gets from the function variable called ``task’’ that includes either an object with information about what the bot manager should do or a boolean value ``false’’ that indicates that the ``message’’ event content is not command for the bot. The bot manager was in this stage set to catch only commands ``play’’ and ``stop’’. If the ``task’’ variable includes command ``play’’ it also includes an id of the quiz game the user wants to start/play. Within this sprint the bot manager only logs the id into the terminal. If the variable includes the command ``stop’’ then it does not have the id value inside. Again the bot only logs to the terminal command ``stop’’ to indicate that the command was checked.