# Kirn

Kirn is a course channel management bot for Discord servers. It allows servers to offer course channels that can be accessed on-demand by users through the use of commands or through a shareable URL.

## Components

- kirn-bot: Discord.py bot (Python) component of the software based on a modified version of the [ConU GCS Bot](https://github.com/GryPr/ConU-GCS-Bot).
- kirn-discordid: Appwrite cloud function (Python) that retrieves the user ID of users logging through the webapp and stores it in the Appwrite database.
- kirn-url: Appwrite cloud function (Python) that sends information to kirn-bot that a user is requesting to join through an URL
- kirn-frontend: React (Typescript) frontend that integrates with Appwrite for Discord OAuth2, and interacts with the cloud functions to provide the course channel URL functionality.

![Ph3rpcdYfm2](https://user-images.githubusercontent.com/51273366/135680551-ed9269bf-0d73-4159-ae0f-a632cd1b4d17.gif)
