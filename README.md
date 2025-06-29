- https://www.youtube.com/watch?v=SJKXJHKTRX8&ab_channel=TomGregory


- Projects can be small or big.
- Project consists of a project directory and a single `settings.gradle` file with the project name.

- With `settings.gradle`, you can interact with the project. 
- If we run `gradle tasks`, it will initialize and list the tasks available in the project. Without `settings.gradle` file, `gradle tasks` will fail. 
- project name can be anything. Not have to be the same as the directory name. it is not even mandatory.


- The gradle build script tells how the application is going to be built.
- There is no `gradle wrapper` as of now since we created the project manually.
- After adding the `gradle.build` file and adding a `println` statement, if we run `gradle` in the terminal, it will print the text.
