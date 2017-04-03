# Harold

Simple macOS menubar system monitor, written in Python. Forked from half0wl/simon to use my name instead of Simon.

![Harold Screenshot](screenshots/dark.png)

Only tested on **macOS Sierra 10.12.4** and **Python 3.6**.

## Installation & Usage

Harold depends on `pyobjc` and `psutil`.

```bash
$ git clone https://github.com/haroldfredshort/harold.git
$ cd harold
$ mkvirtualenv harold && workon harold
$ pip install -r requirements.txt
$ python harold.py
Harold is now running.
CTRL+C does not work here.
You can quit through the menubar (Harold -> Quit).
```

To run Harold in the background, use `nohup`:

```bash
$ nohup python harold.py &
```

To quit Harold, quit through the menubar.

## Todo / Upcoming

* Standalone .app
* More stats - battery, temperature, etc.
* Measure impact on system resources
* Preferences/settings: allow user to set update interval, etc.
* ...

## License

MIT
