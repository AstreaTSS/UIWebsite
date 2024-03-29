---
title: Ultimate Investigator
description: A bot made to help automate investigations during Danganronpa/Killing Game roleplays.
---

# Ultimate Investigator

<figure markdown>
  ![Ultimate Investigator's Banner](assets/ui_banner.jpg)
</figure>

<p align="center" markdown="1">
  [![Server Setup Guide](https://img.shields.io/badge/Server_Setup_Guide-Link-f64b50?style=for-the-badge&logo=bookstack&logoColor=f64b50)](server_setup.md)
  [![Support Server Link](https://img.shields.io/badge/Support_Server-Link-5865F2?style=for-the-badge&logo=discord)](https://discord.gg/NSdetwGjpK)
  [![Donate on Ko-Fi](https://img.shields.io/badge/Donate_on_Ko--Fi-Link-ff5f5f?style=for-the-badge&logo=ko-fi&logoColor=FFFFFF)](https://ko-fi.com/astreatss)
</p>

Ultimate Investigator is a bot meant to help out investigations with Danganronpa/Killing Game roleplays. More specifically, this helps out with "typical" investigations: investigations where users are expected to find key words to get Truth Bullets.

For example, moderators can:

- Set up Truth Bullets for users to find in specific channels:
<figure markdown>
  ![The pop-up that appears while adding Truth Bullets.](assets/add_bullet_modal.png)
</figure>

- Manage Truth Bullets, including editing and removing them:
=== "Listing Truth Bullets"
    <figure markdown>
      ![An example of /list-bullets.](assets/list_bullets.png)
    </figure>

=== "Editing Truth Bullets"
    <figure markdown>
      ![The pop-up that appears while editing Truth Bullets.](assets/edit_bullet_modal.png)
    </figure>

=== "Removing Truth Bullets"
    <figure markdown>
      ![An example of removing a Truth Bullet.](assets/remove_bullet.png)
    </figure>

- Adjust other settings, like who can trigger Truth Bullets and if a role is awarded to the person who finds the most Truth Bullets:
<figure markdown>
  ![An empty server /config info.](assets/guild_config.png)
</figure>

Then, when Truth Bullet discovery is enabled, users can trigger a Truth Bullet by saying a specific phrase (a "trigger") in a channel:
<figure markdown>
  ![Example of a message triggering a Truth Bullet.](assets/trigger_example_clean.png)
  <figcaption>Notice how the trigger is "oven", as represented by the red underline.</figcaption>
</figure>

And the bot, as seen above, will reply with the Truth Bullet in the same channel and (not shown) in a separate channel of your choosing (to show them all in one place).

To see more information, you can either look at:
- [Using the Bot as a User](using_the_bot.md)
- [The Server Setup Guide](server_setup.md)