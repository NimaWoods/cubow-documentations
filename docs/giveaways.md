# Giveaways Guide

## Overview

CubowBot includes a comprehensive giveaway feature that allows server admins to easily create, manage, and conclude giveaways. This guide will explain how to use the giveaway commands and provide detailed examples of each step.

## Giveaway Commands

### Command List

The following commands are available for managing giveaways:

| Command          | Description                      | Usage                                                                                             |
|------------------|----------------------------------|---------------------------------------------------------------------------------------------------|
| `/creategiveaway`| Creates a new giveaway           | `/creategiveaway gewinn:<prize> winner:<number_of_winners> seconds:<seconds> minutes:<minutes> hours:<hours> days:<days> channel:<#channel>` |

** [More will be added soon](https://open.codecks.io/cubowbot/decks/13-backend/card/16a-extend-giveaway-feauture) ** 

### Examples

#### Creating a Giveaway

To create a giveaway, use the `/creategiveaway` command with the required options:

```plaintext
/creategiveaway gewinn:"Awesome Prize" winner:1 seconds:0 minutes:30 hours:0 days:0 channel:#giveaways
```

This command creates a giveaway with the prize "Awesome Prize" in the `#giveaways` channel, which will last for 30 minutes and have 1 winner.

## Giveaway Workflow

### Step-by-Step Guide

1. **Start a Giveaway**: Use the `/creategiveaway` command to initiate a new giveaway. Specify the prize, number of winners, duration, and the channel where the giveaway message should be sent.

   Example:
    ```plaintext
    /creategiveaway gewinn:"Gaming Headset" winner:1 seconds:0 minutes:0 hours:1 days:0 channel:#giveaways
    ```

   This command creates a giveaway for a "Gaming Headset" that lasts for 1 hour and is announced in the `#giveaways` channel.

2. **Join a Giveaway**: Users can join the giveaway by clicking the "🎉 Join" button on the giveaway message. Their user ID will be stored in a `users.json` file.

3. **End a Giveaway**: The bot will automatically end the giveaway after the specified duration. A winner will be randomly selected from the `users.json` file, and an announcement will be made in the giveaway channel.

4. **Announce the Winner**: The bot will edit the giveaway message to announce the winner and ping them in the channel.