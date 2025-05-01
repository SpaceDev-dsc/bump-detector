# Bump Detector Bot

![Bump Detector Logo](https://cdn.discordapp.com/icons/1363414762318462986/fac3acb05df05688f371b2a4625154b9.webp?size=300&quality=lossless)

Bump Detector is a Discord bot designed to streamline your server’s bumping process by detecting bumps (Disboard) and pinging a customizable role to notify members. Built with simplicity and privacy in mind, it ensures seamless integration without advertising or promotional clutter.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Privacy and Compliance](#privacy-and-compliance)
- [Support](#support)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Automatic Bump Detection**: Detects server bumps and sends notifications to a designated role.
- **Customizable Role Pinging**: Choose which role to ping for bump notifications.
- **Privacy-Focused**: No personal data collection or advertising.
- **Easy Integration**: Simple setup with minimal permissions required.
- **Compliant with Discord**: Adheres to Discord’s [Terms of Service](https://discord.com/terms) and [Community Guidelines](https://discord.com/guidelines).

## Installation
To add Bump Detector to your Discord server, follow these steps:

1. **Invite the Bot**:
   Click the invite link below to add Bump Detector to your server:
   [Add Bump Detector to Discord](https://discord.com/oauth2/authorize?client_id=1360884173430067240&permissions=867328&integration_type=0&scope=bot)

2. **Grant Permissions**:
   Ensure the bot has the necessary permissions (e.g., Send Messages, Mention Roles) to function properly. The invite link includes minimal permissions (867328).

3. **Verify Setup**:
   Once added, the bot will confirm its presence in your server. Use the setup commands to configure it (see [Usage](#usage)).

## Usage
After adding the bot to your server, you can interact with it using commands. Below are some example commands (prefix: `bd!`):

- `bd!roleping`: Sets the role to be pinged when a bump is detected. If you are'nt an administrator of the server, you cannot execute this command.
- `bd!help` or `bd!config`: Displays a list of available commands and their descriptions. If you are'nt an administrator of the server, you cannot click on "change role to be pinged".
- `bd!timeout`: Displays the time until a new bump is able to do.

Note: Ensure the bot has permission to mention the selected role and access the channel where bumps occur.

## Configuration
To configure Bump Detector:
1. **Set the Role**:
   Use the `bd!roleping` command to designate a role for bump notifications.
2. **Channel Settings**:
   Ensure the bot has access to the channel where bump commands (Disboard’s `/bump`) are used.
3. **Test the Setup**:
   Trigger a test bump or use `bd!timeout` to verify the configuration.

For detailed configuration options, refer to the bot’s help command (`bd!help`).

## Privacy and Compliance
Bump Detector is committed to protecting your privacy:
- **No Personal Data Collection**: The bot only collects server IDs, role IDs, and bump metadata (e.g., timestamps) necessary for its functionality.
- **No Advertising**: The bot does not engage in or support promotional activities.
- **Compliance**: Fully compliant with Discord’s policies.

Read our full [Privacy Policy](https://spacedev-dsc.github.io/bump-detector/privacy-policy/) and [Terms of Service](https://spacedev-dsc.github.io/bump-detector/tos/) for more details.

## Support
For questions, issues, or suggestions, contact us via Discord:
- **Official Contact**: [Bump Detector Discord server](https://discord.gg/tE7CxRCr7q)

Join our support server or reach out directly for assistance.

## Contributing
We welcome contributions to improve Bump Detector! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit (`git commit -m 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.
6. If you want, please boost Discord server.

Please ensure your code follows our coding standards and includes relevant documentation.

## License
This project is licensed under the Mozilla Public license 2.0. See the [LICENSE](LICENSE) file for details.

---

Thank you for using Bump Detector! Keep your server active and engaged with our hassle-free bump notifications.
