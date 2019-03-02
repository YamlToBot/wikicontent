| Value Name  | Type  | Description | Module | Default |
|-------------|---------|--------------------------------------------------------------------------------------------------|---------------|---------------|
| name | String  | The name of the command. The command will be executed by adding your prefix to the beginning of the name. | Core | null |
| enabled | boolean | Whether or not the command is enabled. | Core | true |
| description | String  | The description of what the command does. Will be used in the help command. | Core | Generic Command |
| usage | String | How the command should be used. | Core | The name of the command. |
| message | List | The message that the command will return. | Core | null |
| predefined-function | String | The predefined function to execute with this command. User-defined commands can be placed in the `YamlToBot/cmds` folder. ~~It must start with the ```%int%``` tag if it is internal, e.g. ```%int%HelpCommand```, or the ```%ext%``` tag if it is user-defined, located in the ```YamlToBot/cmds``` folder.~~ As of 3.0.0, `%int%` and `%ext%` are no longer necesary. | Core | null |
| embed | List | The configuration options to send a Discord embed rather than a normal message. For more on how to use embeds, visit the [Guide to Embeds](wiki/discord/Guide-to-Embeds).  | Discord | null |
