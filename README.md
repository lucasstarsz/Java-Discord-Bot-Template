# Discord Bot Template

A super simple discord bot template made using [JDA][1].

This template uses Gradle, and should be very simple to work with.

## Where's the code?

The code can be found in [`src/main/java/org/example/javadiscordbot/`][2].

## Things you need to provide

Nothing! Well, other than a discord bot token.

## Building and Running

- Open up a terminal, such as Bash or Powershell 
- Navigate to the top level folder of this project (`".../Discord Bot Template"`)
- Type `gradle wrapper` to ensure gradle works as intended
  - You only need to run this the first time you download the project.
- Build the program using `./gradlew clean build`.
- Run the build with `./gradlew run --args "your discord bot token here"`.

For more information on how to use JDA, [check out their github repository][1].

[1]: https://github.com/DV8FromTheWorld/JDA "The JDA github repository."
[2]: https://github.com/lucasstarsz/Java-Discord-Bot-Template/tree/main/src/main/java/org/example/javadiscordbot "Main source code of the template."
