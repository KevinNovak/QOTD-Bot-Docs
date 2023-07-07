__**Introduction**__

QOTD Bot helps keep your community active by automatically posting questions, facts, quotes, and more!

__**Features**__

-   **Schedule posts** daily, weekly, monthly, or whatever custom schedule!
-   Use the **built-in "QOTD Starter Deck"** or add your own **custom cards** (questions, facts, quotes, etc).
-   Control how posts are made, with support for **threads** and **pinning** messages.
-   Automatically **ping roles** when posts are made.
-   Allow users to **submit card suggestions** for the server!
-   Use the **queue** to control which cards are posted next!
-   Customize your post with a **custom title, description, and color**!

__**Getting Started**__

To get started, simply run the `/setup` command using a channel that you want QOTD Bot to automatically post cards in. If you don't already have a channel, please create one first.

The setup process will guide you through the settings needed to get started. Simply follow the prompts and enter responses where appropriate.

__**Cards and Decks**__

**What are Cards?**

**Cards** are the items being posted in the channel. These could be questions, facts, trivia, quotes, or whatever you'd like.

Cards can be created in 2 different ways:

1. Creating cards with the `/card add` command will directly add new cards to a deck.
2. Suggesting cards with the `/suggest new` command will add the card to the channel's suggestions. These will need to be approved by staff before they are added to a deck.

**What are Decks?**

**Decks** are a group of cards, and all cards must be part of a deck. They help to organize cards into different categories, or with different settings, within the same channel.

For example, you might have separate decks for `Would You Rather`, `Video Game Questions`, and `Member Suggestions` all under the same `#question-of-the-day` channel.

You can create new decks with the `/deck new` command.

Decks can also be prioritized to determine which cards are posted first. For example, you might want to post any cards in the `Member Suggestions` deck before posting `Would You Rather` cards, so you can give `Member Suggestions` a higher priority of `1` and `Would You Rather` a lower priority of `2`. Decks with the same priority will be treated as if they were combined.

__**List of Commands**__

Below is a list of all commands available in QOTD Bot. Some commands may be hidden if you don't have permission to view them in Discord.

-   `/setup` \- Run setup for a channel.
-   `/view`
    -   `channels` \- View all channel setups.
    -   `decks` \- View all decks in a channel.
    -   `cards` \- View cards in a deck.
    -   `card` \- Preview a specific card.
    -   `suggestions` \-View suggested cards for a channel.
-   `/community`
    -   `browse` - Browse community decks.
    -   `tags` - Browse community deck tags.
    -   `search` - Search community decks.
    -   `info` - View a community deck's information.
    -   `edit`
        -   `name` - Edit a community deck's name.
        -   `description` - Edit a community deck's description.
        -   `tag` - Toggle a community deck's tag.
        -   `language` - Edit a community deck's language.
    -   `delete` - Delete a community deck.
-   `/server`
    -   `settings` \- View server settings.
    -   `edit`
        -   `time_zone` \- Edit server time zone.
        -   `language` \- Edit server language.
-   `/channel`
    -   `settings` \- View a channel's settings.
    -   `permissions` \- Check the bot's permissions for a channel.
    -   `edit`
        -   `schedule` \- Edit a channel's post schedule.
        -   `mode` \- Edit a channel's post mode.
        -   `ping` \- "Edit a channel's ping.
        -   `title` \- Edit a channel's title.
        -   `description` \- Edit a channel's description.
        -   `color` \- Edit a channel's post color.
        -   `max_suggestions` \- Edit a channel's maximum number of suggestions per user.
    -   `move` \- Move a channel's setup to a different channel.
    -   `pause` \- Pause a channel.
    -   `resume` \- Resume a channel.
    -   `skip` \- Skip or unskip a channel's next post.
    -   `delete` \- Delete a channel setup.
-   `/deck`
    -   `new` \- Create a new deck.
    -   `settings` \- View a deck's settings.
    -   `edit`
        -   `name` \- Edit a deck's name.
        -   `priority` \- Edit a deck's priority.
        -   `card_order` \- Edit a deck's card order.
        -   `auto_reset` \- Edit if a deck should auto-reset or not.
    -   `move` \- Move a deck to a different channel.
    -   `order` \- Reorder a card in a deck.
    -   `enable` \- Enable a deck.
    -   `disable` \- Disable a deck.
    -   `shuffle` \- Shuffle order of all cards in a deck.
    -   `reset` \- Reset a deck.
    -   `delete` \- Delete a deck.
-   `/queue`
    -   `add` \- Add a card to the queue.
    -   `first` \- Add a card to the front of the queue.
    -   `order` \- Reorder a card in the queue.
    -   `remove` \- Remove a card from the queue.
-   `/suggestions`
    -   `approve` \- Approve a suggested card.
    -   `deny` \- Deny a suggested card.
-   `/card`
    -   `add`\*\* \- Add a new card.
    -   `edit`
        -   `text` \- Edit a card's text.
        -   `image` \- Edit a card's image.
    -   `set` \- Set a card as posted or unposted.
    -   `move` \- Move a card to a different deck.
    -   `delete` \- Delete a card.
-   `/test` \- Trigger a test post.
-   `/post` \- Force a card to be posted.
-   `/publish` - Publish (or republish) a deck to the community.
-   `/download` - Download a community deck.
-   `/suggest`
    -   `new`\*\* \- Suggest a new card.
    -   `edit`
        -   `text` \- Edit a suggested card's text.
        -   `image` \- Edit a suggested card's image.
-   `/premium`
    -   `info` \- View premium information.
    -   `subscribe` \- Subscribe to premium.
-   `/vote` \- Vote for QOTD Bot.
-   `/info` \- View bot info.
-   `/help` \- Find help or contact support.

\*\*This command requires you to have voted recently if your server is not subscribed to premium. Afterwards you will have access to any vote-required commands for 7 days.

__**Command Permissions**__

Want to restrict commands to certain roles, users, or channels? Set up permissions in the bot's integration page by going to **Server Settings** > **Integrations**, and then **Manage** for this bot.
