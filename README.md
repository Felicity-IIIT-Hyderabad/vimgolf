vimgolf for IIITH
=======

This project contains a vimgolf client written in Python. It is forked from the Python client [written by dstein64](https://github.com/dstein64/vimgolf).
It acts as the terminal client to the [main website](https://events.felicity.iiit.ac.in/vimgolf).

### Initial setup

1. `git clone` this repo so you can pull changes (if any later).
2. Run `python3 -m pip install -r requirements.txt`.
3. Keep your working directory as the repo root.
4. Run `python3 -m vimgolf config "<API_KEY>"` to locally store your api key. This will be used to verify the submission is coming from your user account. You can get your apikey [here](https://events.felicity.iiit.ac.in/vimgolf/apikey). The "<API_KEY>" is of the form "Bearer TOKEN" hence it needs to be put in quotes when running the command.

### Usage

Run `python3 -m vimgolf` shows the list of commands.
Use `python3 -m vimgolf put 0` to play the 0-th challenge. You can view all challenges on the main website.

**If the CLI starts failing**, the apikey has likely become invalid after eight hours. Kindly reperform step 4 of initial setup to get a new api key. (Apikey refreshes every eight hours)

Good luck and happy golfing!

#### Requirements

- Python 3.5 or greater

License
-------

The source code has an [MIT License](https://en.wikipedia.org/wiki/MIT_License).

See [LICENSE](https://github.com/dstein64/vimgolf/blob/master/LICENSE).
