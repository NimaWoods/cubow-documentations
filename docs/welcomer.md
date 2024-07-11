# CubowBot Welcome Feature Documentation

## Overview

The Welcome feature of CubowBot allows server administrators to configure automated welcome messages for new members joining the server. This feature enhances the user experience by making new members feel acknowledged and providing them with essential information as soon as they join.

## Setting Up Welcome Messages

### Step 1: Set the Welcome Channel

To specify the channel where welcome messages will be sent, use the following command:

```plaintext
/options welcome_channel welcome_channel:<#channel>
```

### Step 2: Set the Welcome Message

To customize the message that new members will receive, use the following command:

```plaintext
/options welcome_message welcome_message:<message>
```

**Placeholders:**

- `{member}`: Mention the new member.
- `{guild}`: The name of the server.

** more will be added in the future (Maybe make some [suggestions](https://nimawoods.github.io/cubow-documentations/feedback)) **

**Example:**

```plaintext
/options welcome_message welcome_message:Welcome {member} to {guild}! We're glad to have you here.
```

### Step 3: Set the Welcome Title

To set a title for the welcome message embed, use the following command:

```plaintext
/options welcome_title welcome_title:<title>
```

**Example:**

```plaintext
/options welcome_title welcome_title:Welcome to {guild}!
```

## Enabling the Welcome Feature ([Coming Soon](https://open.codecks.io/cubowbot/decks/13-backend/card/16j-add-an-option-to-enable-disable-welcomer-and-goodbye))

Ensure that the welcome feature is enabled by setting the appropriate option:

```plaintext
[/options enable_welcome enable_welcome:true](https://open.codecks.io/cubowbot/decks/13-backend/card/16j-add-an-option-to-enable-disable-welcomer-and-goodbye)
```

## Advanced Configuration

### Adding an Image to Welcome Messages ([Coming Soon](https://open.codecks.io/cubowbot/decks/13-backend/card/16k-custom-server-image-on-server-join))

CubowBot allows you to include a custom image in the welcome messages. Ensure that the image is uploaded and accessible.

### Setting a Goodbye Message

In addition to welcome messages, you can also set up goodbye messages for when members leave the server.

**Set the Goodbye Channel:**

```plaintext
/options goodbye_channel goodbye_channel:<#channel>
```

**Set the Goodbye Message:**

```plaintext
/options goodbye_message goodbye_message:<message>
```

**Placeholders:**

- `{member}`: Mention the leaving member.
- `{guild}`: The name of the server.