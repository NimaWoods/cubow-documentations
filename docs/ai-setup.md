# Setting Up AI Features in Cubow Bot

Cubow is capable of utilizing AI features both directly and within its ticket system. Follow this guide to set up and use these features.

## Step-by-Step Setup

### 1. Set API Key

First, you need to set up an API key for OpenAI. Follow these steps:

1. Go to the [OpenAI API Keys page](https://platform.openai.com/settings/profile?tab=api-keys).
2. Generate an API key.
3. Use the following command to set the API key in Cubow:

```plaintext
/options chatgpt_api_token <your_chatgpt_api_token>
```

### 2. Define a Prompt for Tickets

Cubow can respond to tickets using AI, but you need to provide a prompt for it. This prompt guides the AI on how to handle and respond to ticket queries.

Use the following command to set the prompt:

```plaintext
/options chatgpt_prompt <your_chatgpt_prompt>
```

### 3. Try ChatGPT and DALL-E

Once you have set a valid API key, you can start using the AI features to generate content.

#### Using ChatGPT

Generate text content with ChatGPT:

```plaintext
/chatgpt prompt:<your_prompt_here>
```

**Example:**

```plaintext
/chatgpt prompt:Tell me a joke.
```

#### Using DALL-E

Generate images with DALL-E:

```plaintext
/dall-e prompt:<your_image_prompt_here>
```

**Example:**

```plaintext
/dall-e prompt:A futuristic city skyline at sunset.
```

## Advanced Configuration

### Set API Key

To set your ChatGPT API key, use the following command:

```plaintext
/options chatgpt_api_token <your_chatgpt_api_token>
```

### Define a Prompt for Tickets

To set a default prompt for ticket responses, use:

```plaintext
/options chatgpt_prompt <your_chatgpt_prompt>
```

### Use AI Commands

Once the API key is set, you can use the `/chatgpt` and `/dall-e` commands to generate AI content. Make sure your prompts are clear and specific to get the best results.