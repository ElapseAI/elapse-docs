# How to add Elapse to your Discord server?

To add Elapse to your Discord server, follow these steps:

1. Obtain the **'TEAM_MENTION_ID'**:

   - Mention the name of the "Team" role (or the role that will handle user queries when the bot fails to respond) by using **'@'** in any channel or thread.
   - Add a backslash **'\\'** before the mention to escape it.
   - The resulting output will contain an integer value enclosed in **'<@&>'**. This value is the **'TEAM_MENTION_ID'**.

   Example:
   Sending this message in any channel, mentioning the role using **'@'**:

   ```
   \@Team
   ```

   The result will be something like this:

   ```
   <@&1111111111111111111>
   ```

2. Obtain the **'MODERATOR_CHANNEL_ID'**:

   - Mention the moderator channel or private customer support channel using **'#'** in the chat of that channel.
   - Similar to the previous step, add a backslash **'\\'** before the mention.
   - The resulting output will contain an integer value enclosed in **'<#>'**. This value is the **'MODERATOR_CHANNEL_ID'**.

   Example:
   Sending this message in any channel, mentioning the channel using **'#'**:

   ```
   \#Support_Team_channel
   ```

   The result will be something like this:

   ```
   <#2222222222222222222>
   ```

3. Provide the **'ALLOWED_CHANNELS'** list:

   - Create a list of channels where you want the Elapse bot to chat with users.
   - Follow the same steps as used for obtaining the **'MODERATOR_CHANNEL_ID'**.
   - Mention each channel individually using **'#'** and add them to the list.
   - Share this list of channels with the Elapse team.

   Example:
   Sending this message in any channel, mentioning the channels using **'#'**:

   ```


   \#Channel_1
   \#Channel_2
   ```

   The results will be something like this:

   ```
   <#3333333333333333333>
   <#4444444444444444444>
   ```

Once you have collected all these values, contact the Elapse team with your request. They will provide you with a **URL** to add the Discord bot to your server. Follow the simple steps mentioned by Discord after visiting the provided URL to add the bot successfully.
