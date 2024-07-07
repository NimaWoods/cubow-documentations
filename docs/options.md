## Option Commands 

The `OptionCommands` class loads and configures all commands available in Cubow Bot. These commands allow you to set various options for your server, manage tickets, and configure notifications.

### Command Categories

1. **General Options**: `/options`
2. **Ticket Options**: `/ticketoptions`
3. **Notification Options**: `/notificationoptions`

Each category contains several subcommands to set specific options.

## General Options

The `/options` command allows you to set various general options for your server.

### Subcommands

- **language**: Set the language for Cubow.
  ```plaintext
  /options language language:<language>
  ```
- **rules**: Set rules to send in the rule channel.
  ```plaintext
  /options rules rules:<rules_text>
  ```
- **automod**: Enable or disable Automod.
  ```plaintext
  /options automod automod:<true/false>
  ```
- **rule_channel**: Set the channel for rules embed.
  ```plaintext
  /options rule_channel rule_channel:<#channel>
  ```
- **welcome_channel**: Set the welcome channel.
  ```plaintext
  /options welcome_channel welcome_channel:<#channel>
  ```
- **welcome_message**: Set the welcome message.
  ```plaintext
  /options welcome_message welcome_message:<message>
  ```
- **goodbye_channel**: Set the goodbye channel.
  ```plaintext
  /options goodbye_channel goodbye_channel:<#channel>
  ```
- **goodbye_message**: Set the goodbye message.
  ```plaintext
  /options goodbye_message goodbye_message:<message>
  ```
- **website**: Set your website link.
  ```plaintext
  /options website website:<link>
  ```
- **discord**: Set your Discord link.
  ```plaintext
  /options discord discord:<link>
  ```
- **twitter**: Set your Twitter link.
  ```plaintext
  /options twitter twitter:<link>
  ```
- **instagram**: Set your Instagram link.
  ```plaintext
  /options instagram instagram:<link>
  ```
- **facebook**: Set your Facebook link.
  ```plaintext
  /options facebook facebook:<link>
  ```
- **youtube**: Set your YouTube link.
  ```plaintext
  /options youtube youtube:<link>
  ```
- **twitch**: Set your Twitch link.
  ```plaintext
  /options twitch twitch:<link>
  ```
- **mute_role**: Set the mute role.
  ```plaintext
  /options mute_role mute_role:<@role>
  ```
- **join_autorole**: Set the autorole for new members.
  ```plaintext
  /options join_autorole join_autorole:<@role>
  ```
- **moderation_roles**: Set the moderation roles.
  ```plaintext
  /options moderation_roles moderation_roles:<@role1,@role2>
  ```
- **chatgpt_permissions**: Set permissions for using ChatGPT.
  ```plaintext
  /options chatgpt_permissions chatgpt_permissions:<ALL/ADMIN/OWNER>
  ```
- **chatgpt_api_token**: Set the ChatGPT API token.
  ```plaintext
  /options chatgpt_api_token chatgpt_api_token:<token>
  ```
- **chatgpt_prompt**: Set the default ChatGPT prompt.
  ```plaintext
  /options chatgpt_prompt chatgpt_prompt:<prompt>
  ```
- **temp_voicechat_channel**: Set the temporary voice chat channel.
  ```plaintext
  /options temp_voicechat_channel temp_voicechat_channel:<channel_id>
  ```
- **temp_voicechat_category**: Set the temporary voice chat category.
  ```plaintext
  /options temp_voicechat_category temp_voicechat_category:<category_id>
  ```

## Ticket Options

The `/ticketoptions` command allows you to set various options for managing tickets in your server.

### Subcommands

- **ticket_channel**: Set the channel for the ticket panel.
  ```plaintext
  /ticketoptions ticket_channel ticket_channel:<#channel>
  ```
- **ticket_category**: Set the category where tickets are created.
  ```plaintext
  /ticketoptions ticket_category ticket_category:<category_id>
  ```
- **transcript_channel**: Set the channel for transcripts.
  ```plaintext
  /ticketoptions transcript_channel transcript_channel:<#channel>
  ```
- **ticket_title**: Set the ticket title.
  ```plaintext
  /ticketoptions ticket_title ticket_title:<title>
  ```
- **ticket_description**: Set the ticket description.
  ```plaintext
  /ticketoptions ticket_description ticket_description:<description>
  ```
- **ticket_name**: Set the name for ticket channels.
  ```plaintext
  /ticketoptions ticket_name ticket_name:<name>
  ```
- **ticket_q_and_a**: Set the Q&A to send to ChatGPT.
  ```plaintext
  /ticketoptions ticket_q_and_a ticket_q_and_a:<q_and_a>
  ```
- **ticket_view_role_permission**: Set the roles that can view tickets.
  ```plaintext
  /ticketoptions ticket_view_role_permission ticket_view_role_permission:<@role1,@role2>
  ```
- **ticket_send_role_permission**: Set the roles that can send messages in tickets.
  ```plaintext
  /ticketoptions ticket_send_role_permission ticket_send_role_permission:<@role1,@role2>
  ```
- **ticket_mention_role**: Set the roles to mention on new tickets.
  ```plaintext
  /ticketoptions ticket_mention_role ticket_mention_role:<@role1,@role2>
  ```

## Notification Options

The `/notificationoptions` command allows you to set various notification channels for your server.

### Subcommands

- **moderation_notification_channel**: Set the channel for moderation notifications.
  ```plaintext
  /notificationoptions moderation_notification_channel moderation_notification_channel:<#channel>
  ```
- **report_notification_channel**: Set the channel for report notifications.
  ```plaintext
  /notificationoptions report_notification_channel report_notification_channel:<#channel>
  ```
- **live_notification_channel**: Set the channel for live notifications (Twitch).
  ```plaintext
  /notificationoptions live_notification_channel live_notification_channel:<#channel>
  ```
- **offline_notification_channel**: Set the channel for offline notifications (Twitch).
  ```plaintext
  /notificationoptions offline_notification_channel offline_notification_channel:<#channel>
  ```

## Conclusion

This guide covers the setup and usage of commands in Cubow Bot to configure server settings, manage tickets, and set up notifications. Make sure to have the necessary permissions to execute these commands. Use the provided examples to configure your server effectively.