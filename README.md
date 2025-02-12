# IP Logger

This is a simple IP logging tool that collects information about a user's IP address, location, and device details, and sends it to a Discord webhook.

## Installation

1. Clone the repository:
```
git clone https://github.com/Javadkarami-com/ip-logger.git
```

2. Install the required dependencies:
```
cd ip-logger
```

3. Create a `config.json` file in the root directory and add your Discord webhook URL and API key:
```json
{
  "Token":"https://discord.com/api/webhooks/....",
  "key":"APIKEY-HERE created in https://ipgeolocation.io/"
}
```

## Usage

1. Open the `index.html` file in a web browser.
2. The script will automatically fetch the user's IP information and send it to the configured Discord webhook.

## Contributing

If you find any issues or have suggestions for improvements, feel free to open a new issue or submit a pull request. Contributions are welcome!
