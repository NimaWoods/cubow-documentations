# Ticket System Documentation

## Setup

### Set a Ticket Channel and Category

To configure the channel where new tickets will appear, use the following command:
```bash
/ticketoptions ticket_channel <ticket_channel:#ticket>
```

To set the category ID for ticket channels, use this command:
```bash
/ticketoptions ticket_category <ticket_category:category_id>
```

### Set a Ticket Title and Description

To configure the title and description for new tickets, use the following commands:
```bash
/ticketoptions ticket_title <ticket_title:Your Ticket Title>
```
```bash
/ticketoptions ticket_description <ticket_description:Your Ticket Description>
```

### Set AI Token for AI Response

To set an AI Token for AI Response, follow the guide available [here](https://nimawoods.github.io/cubow-documentations/ai-setup/).

## Overview

The CubowBot Ticket System allows users to submit support requests or other inquiries in a structured and organized manner. The system supports the creation, management, and closure of tickets, as well as communication between members and moderators.

```bash
/ticket <command>
```

## Main Components and Functions

### Key Functions

#### Ticket Creation

The system enables the creation of a ticket by checking the user's permissions and, if authorized, generating a new ticket channel with the appropriate settings and roles. A button can be used to trigger this process.

#### Dashboard Panel

A dashboard panel for ticket creation can be sent to a predefined channel, allowing users to easily create new tickets.

#### Adding and Removing Members

Moderators can add members to an existing ticket, granting them access to the ticket channel. They can also remove members from the ticket, revoking their access.

#### Ticket Closure

Tickets can be closed by the creator or a moderator. The system confirms the closure, archives the ticket, and notifies the relevant parties. Closure requests can be made, and confirmations are handled through user interaction.

#### Claiming and Unclaiming Tickets

Moderators can take responsibility for a ticket, assigning it to themselves and updating permissions. They can also release responsibility, making the ticket available for others to claim.

#### Transferring Tickets

Responsibility for a ticket can be transferred from one member to another, updating permissions accordingly.

#### Transcript Creation

When a ticket is closed, the system creates a transcript of all messages in the ticket channel. This transcript is sent to a defined transcript channel, ensuring that records of the conversation are maintained.

### Usage Examples

#### Creating a Ticket

A user clicks on the "Create Ticket" button. The system checks permissions and, if successful, creates a new ticket channel with appropriate settings.

#### Adding a Member

Moderators can use the system to add a member to an existing ticket, giving them access to the channel.

#### Closing a Ticket

To close a ticket, a confirmation process is initiated. Once confirmed, the ticket is archived, and a transcript is created.

#### Claiming a Ticket

Moderators can claim a ticket to take responsibility for it. The ticket is then assigned to them, and the necessary permissions are updated.

#### Transcript Creation

Upon ticket closure, a complete transcript of the ticket channel's messages is generated and sent to a predefined transcript channel.

#### Reopening a Ticket

If a [ticket channel](#set-a-ticket-channel-and-category) and a [ticket category](#set-a-ticket-channel-and-category) are set, users can reopen tickets that were previously closed. They receive a notification upon ticket closure and can click on a button to reopen the selected ticket.