# Java Discord Bot Template
A super simple discord bot template made using [JDA][1] and the Gradle build tool.


## Where's the code?
The code can be found in [`src/main/java/org/botexample`][2].


## What do I need to provide?
Nothing more than a discord bot token.


## Building and Running
- Clone the repository from Github.
  ```bash
  git clone https://github.com/lucasstarsz/Java-Discord-Bot-Template.git
  ```
- Enter the project's directory.
  ```bash
  cd Java-Discord-Bot-Template/
  ```
- Build the project. 
  ```bash
  ./gradlew clean build
  ```
- Run the project, using your discord bot token.
  ```bash
  ./gradlew run --args "your discord bot token here"
  ```

_Having issues using `gradlew`? Read [this][3]._


## What does this template do?
This template does the following:
- Displays a "ready for takeoff" message on the `ready` event.
- Prints out a chatter's message every time they speak in a channel visible to the bot.
- Prints out a chatter's message every time they Direct Message (DM) the bot.

For more information on how to use JDA, [check out their github repository][1].


[1]: https://github.com/DV8FromTheWorld/JDA "The JDA github Repository"
[2]: https://github.com/lucasstarsz/Java-Discord-Bot-Template/tree/main/src/main/java/org/botexample "Template Source Code"
[3]: https://gist.github.com/lucasstarsz/9bbc306f8655b916367d557043e498ad "Terminals Access Files Differently"