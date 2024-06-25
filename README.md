# AbbiBot

AbbiBot is a Telegram bot that helps manage user verification and channel invites. It includes features for both regular users and admins, ensuring a smooth and secure experience.

## Features

- 🛡️ User verification through captchas.
- 🔗 Generate invite links for verified users.
- ⚙️ Admin panel for managing users and invites.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/mphank/TeleGateWayBot
    ```

2. Navigate to the project directory:
    ```sh
    cd TeleGateWayBot
    ```

3. Edit `gateway.py` with your telegram settings.

4. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

5. Run the script:
    ```sh
    python gateway.py
    ```


## Usage

### Regular Users

- `/start` - Start the verification process.
- `/invite` - Generate an invite link (if verified).

### Admins

- `/admin` - Open the admin panel.
- `/join_channel` - Join a channel (forward a message from the channel or send the channel link).

## Configuration

- **TOKEN**: Your bot's token.
- **CHANNEL_ID**: The ID of the channel to manage.
- **ADMIN_IDS**: List of Telegram user IDs of the admins.

## Contributing

Feel free to fork the repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is dedicated to the public domain under the CC0 license.

Made with ❤️ by mphank
