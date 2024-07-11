Sure, here's a detailed `embeds.md` documentation file for your CubowBot's Embed Creation feature:

```markdown
# Embed Creation with CubowBot

CubowBot provides powerful commands to create, edit, and manage embedded messages. These embedded messages can be used for announcements, rules, updates, and much more.

## Commands Overview

1. `/embedcreate` - Create a new embed.
2. `/embededit` - Edit an existing embed.
3. `/embedaddfield` - Add a field to an existing embed.

## Embed Creation

### Command: `/embedcreate`

**Description:**  
Creates a new embed message in a specified channel.

**Usage:**  
```plaintext
/embedcreate title:<title> description:<description> channel:<#channel> color:<color>
```

**Parameters:**
- `title`: The title of the embed.
- `description`: The main content of the embed.
- `channel`: The channel where the embed will be sent.
- `color`: The color of the embed (optional).

## Embed Editing

### Command: `/embededit`

**Description:**  
Edits an existing embed message.

**Usage:**
```plaintext
/embededit message_id:<message_id> channel:<#channel> title:<new_title> description:<new_description> color:<new_color>
```

**Parameters:**
- `message_id`: The ID of the embed message to edit.
- `channel`: The channel where the embed is located.
- `title`: The new title of the embed (optional).
- `description`: The new description of the embed (optional).
- `color`: The new color of the embed (optional).

**Example:**
```plaintext
/embededit message_id:123456789012345678 channel:#rules title:"Updated Server Rules" description:"1. Be respectful to everyone.\n2. No spamming or flooding the chat.\n3. Follow the Discord Terms of Service."
```

## Adding Fields to Embeds

### Command: `/embedaddfield`

**Description:**  
Adds a field to an existing embed message.

**Usage:**
```plaintext
/embedaddfield message_id:<message_id> channel:<#channel> name:<field_name> value:<field_value> inline:<true/false>
```

**Parameters:**
- `message_id`: The ID of the embed message to edit.
- `channel`: The channel where the embed is located.
- `name`: The name of the field.
- `value`: The content of the field.
- `inline`: Whether the field should be inline with others (optional, default is false).

**Example:**
```plaintext
/embedaddfield message_id:123456789012345678 channel:#rules name:"Rule 4" value:"No offensive language." inline:false
```

## Advanced Usage and Tips

### Formatting Text
You can use Discord's markdown to format text within your embeds. For example:
- `**bold**` for bold text.
- `*italic*` for italic text.
- `` `code` `` for inline code.

### Managing Permissions
Ensure that CubowBot has the necessary permissions to send messages and manage embeds in the specified channels.