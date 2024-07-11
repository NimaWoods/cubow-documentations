## Option Commands

| Command                | Description                                        | Usage                                                                  |
|------------------------|----------------------------------------------------|------------------------------------------------------------------------|
| **General Options**    |                                                    |                                                                        |
| /options language      | Set the language for Cubow.                        | `/options language language:<language>`                                 |
| /options rules         | Set rules to send in the rule channel.             | `/options rules rules:<rules_text>`                                     |
| /options automod       | Enable or disable Automod.                         | `/options automod automod:<true/false>`                                 |
| /options rule_channel  | Set the channel for rules embed.                   | `/options rule_channel rule_channel:<#channel>`                         |
| /options welcome_channel | Set the welcome channel.                         | `/options welcome_channel welcome_channel:<#channel>`                   |
| /options welcome_message | Set the welcome message.                         | `/options welcome_message welcome_message:<message>`                    |
| /options goodbye_channel | Set the goodbye channel.                         | `/options goodbye_channel goodbye_channel:<#channel>`                   |
| /options goodbye_message | Set the goodbye message.                         | `/options goodbye_message goodbye_message:<message>`                    |
| /options website       | Set your website link.                             | `/options website website:<link>`                                       |
| /options discord       | Set your Discord link.                             | `/options discord discord:<link>`                                       |
| /options twitter       | Set your Twitter link.                             | `/options twitter twitter:<link>`                                       |
| /options instagram     | Set your Instagram link.                           | `/options instagram instagram:<link>`                                   |
| /options facebook      | Set your Facebook link.                            | `/options facebook facebook:<link>`                                     |
| /options youtube       | Set your YouTube link.                             | `/options youtube youtube:<link>`                                       |
| /options twitch        | Set your Twitch link.                              | `/options twitch twitch:<link>`                                         |
| /options mute_role     | Set the mute role.                                 | `/options mute_role mute_role:<@role>`                                  |
| /options join_autorole | Set the autorole for new members.                  | `/options join_autorole join_autorole:<@role>`                          |
| /options moderation_roles | Set the moderation roles.                       | `/options moderation_roles moderation_roles:<@role1,@role2>`            |
| /options chatgpt_permissions | Set permissions for using ChatGPT.           | `/options chatgpt_permissions chatgpt_permissions:<ALL/ADMIN/OWNER>`    |
| /options chatgpt_api_token | Set the ChatGPT API token.                     | `/options chatgpt_api_token chatgpt_api_token:<token>`                  |
| /options chatgpt_prompt | Set the default ChatGPT prompt.                   | `/options chatgpt_prompt chatgpt_prompt:<prompt>`                       |
| /options temp_voicechat_channel | Set the temporary voice chat channel.     | `/options temp_voicechat_channel temp_voicechat_channel:<channel_id>`   |
| /options temp_voicechat_category | Set the temporary voice chat category.   | `/options temp_voicechat_category temp_voicechat_category:<category_id>`|
| **Ticket Options**     |                                                    |                                                                        |
| /ticketoptions ticket_channel | Set the channel for the ticket panel.       | `/ticketoptions ticket_channel ticket_channel:<#channel>`               |
| /ticketoptions ticket_category | Set the category where tickets are created. | `/ticketoptions ticket_category ticket_category:<category_id>`           |
| /ticketoptions transcript_channel | Set the channel for transcripts.        | `/ticketoptions transcript_channel transcript_channel:<#channel>`        |
| /ticketoptions ticket_title | Set the ticket title.                         | `/ticketoptions ticket_title ticket_title:<title>`                       |
| /ticketoptions ticket_description | Set the ticket description.             | `/ticketoptions ticket_description ticket_description:<description>`     |
| /ticketoptions ticket_name | Set the name for ticket channels.              | `/ticketoptions ticket_name ticket_name:<name>`                          |
| /ticketoptions ticket_q_and_a | Set the Q&A to send to ChatGPT.             | `/ticketoptions ticket_q_and_a ticket_q_and_a:<q_and_a>`                 |
| /ticketoptions ticket_view_role_permission | Set the roles that can view tickets. | `/ticketoptions ticket_view_role_permission ticket_view_role_permission:<@role1,@role2>` |
| /ticketoptions ticket_send_role_permission | Set the roles that can send messages in tickets. | `/ticketoptions ticket_send_role_permission ticket_send_role_permission:<@role1,@role2>` |
| /ticketoptions ticket_mention_role | Set the roles to mention on new tickets. | `/ticketoptions ticket_mention_role ticket_mention_role:<@role1,@role2>` |
| **Notification Options** |                                                  |                                                                        |
| /notificationoptions moderation_notification_channel | Set the channel for moderation notifications. | `/notificationoptions moderation_notification_channel moderation_notification_channel:<#channel>` |
| /notificationoptions report_notification_channel | Set the channel for report notifications.       | `/notificationoptions report_notification_channel report_notification_channel:<#channel>`       |
| /notificationoptions live_notification_channel | Set the channel for live notifications (Twitch). | `/notificationoptions live_notification_channel live_notification_channel:<#channel>`          |
| /notificationoptions offline_notification_channel | Set the channel for offline notifications (Twitch). | `/notificationoptions offline_notification_channel offline_notification_channel:<#channel>`     |