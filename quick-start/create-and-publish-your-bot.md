---
description: >-
  You can quickly create your own AIbot on JarvisAI without writing code
  yourself. This article will use sending commands as an example to demonstrate
  how to create a robot on the platform.
---

# Create and publish your bot

***

## Step 1: Create a bot <a href="#step-1-create-a-bot" id="step-1-create-a-bot"></a>

* Log in to [<mark style="color:purple;">JarvisBot</mark>](https://jarvisbot.emchub.ai/)<mark style="color:purple;">.</mark>
* Go to **AIbot** > **My bots.**
* Click **Create AIbot.**

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
JarvisBot provides you a bot to use by default. The bot was created by system, cannot be deleted. You can create a new bot or duplicate the default bot to use.
{% endhint %}

* Enter a name and description for the bot.                                                                                     &#x20;

&#x20;      The name and description will be visible to other users as a symbol once the bot is published.&#x20;

* Click **Change** icon to replace the logo or just use the default logo.
* Choose function "**Chat**" and "**TXT2IMG**"
* Click **OK.** Once the bot is created, you can start to set a bot on **Settings** Page.

<div align="left">

<figure><img src="../.gitbook/assets/image (1).png" alt="" width="290"><figcaption></figcaption></figure>

</div>

<table><thead><tr><th width="126">Settings</th><th>Description</th></tr></thead><tbody><tr><td>Profile</td><td>Displays the basic info and role definition.</td></tr><tr><td>Memory</td><td>Displays Q&#x26;A Base and Knowledge Base choosed.</td></tr><tr><td>Model</td><td>Display the Large Language Model and the model for generating images.</td></tr><tr><td>Platform</td><td>Display the platform which you want the bot to be used in.</td></tr></tbody></table>

***

## Step 2: Set Profile <a href="#step-1-create-a-bot" id="step-1-create-a-bot"></a>

### Basic Info

* Select the target bot and click **...** > **Settings** button.

<div align="left">

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

</div>

&#x20;.![](<../.gitbook/assets/image (8).png>)

* Enter EMC API ID and EMC API key, and click **Verify**.
* Choose function you need. The default function is **Chat**.

{% hint style="info" %}
EMC API ID and API key will be filled once you create the token in EMC Hub.

Also you can enter other token in different bot.
{% endhint %}

### Role Definition

Enter the prompts below to set role of bot. Prompts are a fundamental mechanism used by chatbots to drive the conversational flow, gather user input, and generate appropriate responses, ultimately enabling a more natural and engaging interaction between the user and the bot.

* **Role:** You can write Introduction of bot, such as the bot's character.

&#x20;      Example: `You're an AI senior advertiser who has designed many popular creative advertisements.`

* **Specialty:** You can write the skills of the bot.

&#x20;     Example: `Create a creative advertising slogan based on my requirements and description.`

* **Owner:** Who create the bot.

&#x20;      Example: `You're an created by xxx company.`

* **Constraints:** You can specify the steps requied to complete a task. You can specify the desired length of the output. You can instruct the model to answer using a reference text. You can also do something other to configure the bot.

&#x20;     Example1: `Explain the problems you found in the original code and how your fixes address them.`

&#x20;     Example2: `The corrected code should be functional, efficient, and adhere to best practices in Python programming.`

&#x20;     Example2: `Answer questions using language exactly same as last user input to avoid misunderstanding.`

&#x20;![](<../.gitbook/assets/image (69).png>)

***

## Step 3: Set memory <a href="#step-1-create-a-bot" id="step-1-create-a-bot"></a>

<div align="left">

<figure><img src="../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

</div>

### Link Q\&A Base <a href="#step-1-create-a-bot" id="step-1-create-a-bot"></a>

1. Click **Link button.**
2. Select a Q\&A Base to the bot.
3. Click **OK**.

<div align="left">

<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

</div>

{% hint style="info" %}
If you don't have any Q\&A base, you can also use the bot.
{% endhint %}

***

### Link Knowledge Base <a href="#step-1-create-a-bot" id="step-1-create-a-bot"></a>

1. Click **Link** button.
2. Select a Knowledge Base to the bot.
3. Click **OK**.

{% hint style="info" %}
If you don't have any knowledge base, you can also use the bot.
{% endhint %}

## Step 4: Choose model <a href="#step-1-create-a-bot" id="step-1-create-a-bot"></a>

* Choose a Large Language Model.
* If you select the function "**Txt2Img**", you can choose a model for image generation.

<figure><img src="../.gitbook/assets/image (70).png" alt=""><figcaption></figcaption></figure>

## Step 5: Choose platform and verify token <a href="#step-1-create-a-bot" id="step-1-create-a-bot"></a>

* JarvisBot was the default platform.
* Enter the copied right Telegram bot token and click **Verify**.
* Enter the copied right Discord bot token and click **Verify**.
* Choose Telegram and Discord.

## Step 6: Active your bot <a href="#step-1-create-a-bot" id="step-1-create-a-bot"></a>

Click **Active**.

{% hint style="info" %}
If you want to publish your bot, you must active it first.
{% endhint %}

## Step 7: Use your bot <a href="#step-1-create-a-bot" id="step-1-create-a-bot"></a>

Click the bot card, you can use your bot directly. Send a message to chat with bot or generate images.

<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

## Step 8: Publish your bot <a href="#step-1-create-a-bot" id="step-1-create-a-bot"></a>

* Click **Publish.**
* On the **Bots page,** you can search your published bot.





