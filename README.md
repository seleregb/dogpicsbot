# Dog Pics Bot

A simple Telegram bot that sends random dog pictures.

## Requirements

The bot runs on `python 3` (developed and tested with `python 3.7.3` specifically), and uses the packages listed on the `requirements.txt` file.

For ease of use, you should create a Python 3 virtual environment and then use `pip` in order to install the requirements, with the following command:

```bash
pip install requirements.txt
```

## Installation

Simply clone this repository, fetch the requirements on a virtual environment as stated above and then set a new environment variable named `DPB_TG_TOKEN` with your Telegram bot API token. If you don't have a valid token, [check this out](https://core.telegram.org/bots).

## Usage

Run the following command on a command line. It will keep the polling thread running (therefore keeping your bot alive) until you kill the process.

```bash
python bot.py
```

## What's next?

The next features to be developed are:

- Replying to 'woof', 'bark', 'dog' and other dog-related words in a chat or group with a dog pic, instead of automatically replying to every message.
- Fetching dog pictures of a given dog breed on demand.
- And more!

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details.
