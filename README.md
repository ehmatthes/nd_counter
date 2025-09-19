nd_counter
===

This is a sample [nanodjango](https://nanodjango.dev) project, taken straight from the [Getting started](https://docs.nanodjango.dev/en/latest/get_started/) docs.

To run this project locally:

```sh
$ git clone https://github.com/ehmatthes/nd_counter.git
$ cd nd_counter
nd_counter$ uv venv .venv
nd_counter$ source .venv/bin/activate
(.venv) nd_counter$ uv pip install -r requirements.txt
(.venv) nd_counter$ nanodjango run counter.py
```

This will run the initial migration, prompt you for a superuser name and password, and then start the local development server.
