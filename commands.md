# Commands  
Here's the list of Hypertonic's Commands

#### Contents of the table  
**Name**: The name of the command  
**Description**: A brief explanation of the purpose of the command  
**Usage**: How to use the Command
[] = Mandatory Arguments
() = Optional Arguments


### General (18 commands)

| Name              | Description                                                 | Usage                          |
| ----------------- | ----------------------------------------------------------- | ------------------------------ |
| **botinfo**       | Displays Information about Hypertonic                       | botinfo                        |
| **serverinfo**    | Displays Information about the Guild                        | serverinfo                     |
| **userinfo**      | Displays Information about the Mentioned User/Youself       | userinfo (ID/@)                |
| **help**          | Help Command if you need Assistance                         | help                           |
| **support**       | Sends link to Hypertonic Support Server                     | support                        |
| **invite**        | Shows link to Invite Bot to your own guild                  | invite                         |
| **comingsoon**    | List of New Things to be added to Hypertonic                | comingsoon                     |
| **count**         | Shows Current Guild/User Count for Hypertonic               | count                          |
| **poll**          | Starts a Poll in that channel                               | poll (QUESTION)                |
| **checkstrikes**  | Checks a Users Strikes in that Guild                        | checkstrikes (ID/@)            |
| **checkcommends** | Checks a Users Commends in that Guild                       | checkcommends (ID/@)           |
| **startstream**   | Sends a Message in a #streams Channel that you are live     | startstream (Stream URL)       |
| **reminder**      | Start a Reminder for yourself                               | reminder [TIME][M-S-H]         |
| **avatar**        | Displays a Users Avatar or yours                            | avatar (ID/@)                  |
| **stopwatch**     | Starts a Stopwatch                                          | stopwatch [start/stop]         |
| **partners**      | Shows all Hypertonic Partners                               | partners                       |
| **!prefix**       | Shows Guilds Prefix                                         | !prefix (HARD CODED TO !)      |
| **logs**          | Shows where Moderation Logs are bound to                    | logs                           |

### Moderation (19 commands)

| Name              | Description                                                 | Usage                                 |
| ----------------- | ----------------------------------------------------------- | ------------------------------------- |
| **addrole**       | Adds a Role to a User                                       | addrole [@NAME/ID] [@ROLE/NAME/ID]    |
| **ban**           | Bans a User from your Guild                                 | ban [@NAME/ID] [REASON]               |
| **kick**          | Kicks a User from your Guild                                | kick [@NAME/ID] [REASON]              |
| **mute**          | Mutes a User from your Guild                                | mute [@NAME/ID] [TIME] [REASON]       |
| **purge**         | Deletes a specific amount of Message from a Channel         | purge [#]                             |
| **removerole**    | Removes a Role to a User                                    | removerole [@NAME/ID] [@ROLE/NAME/ID] |
| **strike**        | Strikes a User in your Guild                                | strike [@NAME/ID] [REASON]            |
| **unban**         | Unbans a User from your Guild                               | unban [@NAME/ID] [REASON]             |
| **lockdown**      | Locks Down that Specific Channel                            | lockdown [TIME][M-S]                  |
| **commend**       | Commends a User in your Guild                               | commend [@NAME/ID] [REASON]           |
| **slowmode**      | Sets a Slowmode to a channel                                | slowmode [#]                          |
| **createemoji**   | Adds Emotes from Other Servers to yours (MAX 5 AT ONCE)     | createemoji [EMOTES]                  |
| **setprefix**     | Sets Prefix to your Guild for Hypertonic                    | setprefix [PREFIX]                    |
| **setlogs**       | Sets Logging Channel in your Guild for Hypertonic           | setlogs [LOGS_CHANNEL_ID]             |

### Giveaway (3 Commands)
| Name               | Description                                              | Usage                                            |
| ------------------ | -------------------------------------------------------- | ------------------------------------------------ |
| **giveawaystart**  | Starts a Giveaway                                        | giveawaystart [CHANNEL] [TIME] [WINNERS] [PRIZE] |
| **giveawayend**    | Ends a Giveaway                                          | giveawaystop [GIVEAWAY_MESSAGE_ID]               |
| **giveawayreroll** | Rerolls a Giveaway                                       | giveawayreroll [GIVEAWAY_MESSAGE_ID]             |