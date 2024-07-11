# CubowBot Command List
Sure, here's the updated command list with an added column indicating if moderator permissions are required:

| Command                | Description                                                        | Usage                                                | Moderator Permissions |
|------------------------|--------------------------------------------------------------------|------------------------------------------------------|-----------------------|
| **General Commands**   |                                                                    |                                                      |                       |
| `/ping`                | Checks the bot's response time.                                    | `/ping`                                              | No                    |
| `/help`                | Displays a list of available commands and their descriptions.      | `/help`                                              | No                    |
| `/website`             | Provides the link to the official website.                         | `/website`                                           | No                    |
| `/commands`            | Shows a detailed list of all commands.                             | `/commands`                                          | No                    |
| `/serverstats`         | Displays statistics about the server.                              | `/serverstats`                                       | No                    |
| **Ticket Commands**    |                                                                    |                                                      |                       |
| `/ticket create`       | Creates a new ticket.                                              | `/ticket create`                                     | No                    |
| `/ticket add`          | Adds a user to the ticket.                                         | `/ticket add <@user>`                                | Yes                   |
| `/ticket remove`       | Removes a user from the ticket.                                    | `/ticket remove <@user>`                             | Yes                   |
| `/ticket claim`        | Claims responsibility for the ticket.                              | `/ticket claim`                                      | Yes                   |
| `/ticket unclaim`      | Unclaims responsibility for the ticket.                            | `/ticket unclaim`                                    | Yes                   |
| `/ticket close`        | Closes the current ticket.                                         | `/ticket close`                                      | No                    |
| `/ticket closerequest` | Requests to close the current ticket, asking for user confirmation.| `/ticket closerequest`                               | No                    |
| `/ticket reopen`       | Reopens a previously closed ticket.                                | `/ticket reopen`                                     | Yes                   |
| `/ticket sendpanel`    | Resends the ticket panel.                                          | `/ticket sendpanel`                                  | Yes                   |
| `/ticket transfer`     | Transfers the ticket to another staff member.                      | `/ticket transfer <@user>`                           | Yes                   |
| **Moderation Commands**|                                                                    |                                                      |                       |
| `/ban`                 | Bans a user from the server.                                       | `/ban <@user>`                                       | Yes                   |
| `/tempban`             | Temporarily bans a user for a specified time.                      | `/tempban <@user> <hours> <minutes> <seconds>`       | Yes                   |
| `/kick`                | Kicks a user from the server.                                      | `/kick <@user>`                                      | Yes                   |
| `/unban`               | Unbans a user by their ID.                                         | `/unban <user_id>`                                   | Yes                   |
| `/mute`                | Mutes a user for a specified duration.                             | `/mute <@user> [duration in seconds]`                | Yes                   |
| `/unmute`              | Unmutes a user.                                                    | `/unmute <@user>`                                    | Yes                   |
| `/timeout`             | Puts a user in timeout for a specified duration.                   | `/timeout <@user> <hours> <minutes> <seconds>`       | Yes                   |
| `/removetimeout`       | Removes timeout from a user.                                       | `/removetimeout <@user>`                             | Yes                   |
| **Feedback Commands**  |                                                                    |                                                      |                       |
| `/bug`                 | Reports a bug with a title and description.                        | `/bug <title> <description>`                         | No                    |
| `/suggest`             | Suggests a feature with a title and description.                   | `/suggest <title> <description>`                     | No                    |
| **Giveaway Commands**  |                                                                    |                                                      |                       |
| `/creategiveaway`      | Creates a new giveaway.                                            | `/creategiveaway <prize> <winners> <duration in seconds> [minutes] [hours] [days]` | Yes                   |
| **Music Commands**     |                                                                    |                                                      |                       |
| `/play`                | Plays a song from a YouTube link or song name.                     | `/play <link or song name>`                          | No                    |
| `/join`                | Joins a voice channel.                                             | `/join`                                              | No                    |
| `/leave`               | Leaves a voice channel.                                            | `/leave`                                             | No                    |
| **AI Commands**        |                                                                    |                                                      |                       |
| `/chatgpt`             | Interacts with ChatGPT for AI-driven responses.                    | `/chatgpt <prompt>`                                  | Configurable          |
| `/dall-e`              | Generates an image using Dall-E based on a prompt.                 | `/dall-e <prompt>`                                   | Configurable          |
| **Miscellaneous Commands** |                                                               |                                                      |                       |
| `/avatar`              | Retrieves a user's avatar in various formats.                      | `/avatar <@user>`                                    | No                    |
| `/addemoji`            | Adds an emoji to the server.                                       | `/addemoji <name> <image>`                           | Yes                   |
| `/removeemoji`         | Removes an emoji from the server.                                  | `/removeemoji <emoji>`                               | Yes                   |
| `/coinflip`            | Flips a coin.                                                      | `/coinflip`                                          | No                    |
| **Notification Commands** |                                                             |                                                      |                       |
| `/notificationoptions` | Configures notification settings for the server.                   | `/notificationoptions <subcommand> <options>`        | Yes                   |
| **Report Commands**    |                                                                    |                                                      |                       |
| `/report`              | Reports a user with a reason.                                      | `/report <@user> <reason>`                           | No                    |
| **Lockdown Commands**  |                                                                    |                                                      |                       |
| `/lockdownchannel`     | Locks down a specific channel for a specified duration.            | `/lockdownchannel <minutes>`                         | Yes                   |
| `/lockdownserver`      | Locks down the entire server for a specified duration.             | `/lockdownserver <minutes>`                          | Yes                   |
| **Temporary Text Channel Commands** |                                                      |                                                      |                       |
| `/textchannel sendpanel` | Sends the control panel for temporary text channels.             | `/textchannel sendpanel <channel> <category ID>`     | Yes                   |
| `/textchannel create`  | Creates a temporary text channel.                                  | `/textchannel create`                                | No                    |
| `/textchannel add`     | Adds a member to the temporary text channel.                       | `/textchannel add <@user>`                           | No                   |
| `/textchannel remove`  | Removes a member from the temporary text channel.                  | `/textchannel remove <@user>`                        | No                   |
| `/textchannel rename`  | Renames the temporary text channel.                                | `/textchannel rename <name>`                         | No                   |
| `/textchannel delete`  | Deletes the temporary text channel.                                | `/textchannel delete`                                | No                   |