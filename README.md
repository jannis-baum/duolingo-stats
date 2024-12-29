# Duolingo Stats

Duolingo only likes to show us stats when it feels like it. This repo allows you
to peak into your own comprehensive stats based on the weekly e-mails Duolingo
sends you.

## Demo

You can look at the [`stats.ipynb` Notebook](stats.ipynb) in this repo to see
the output that is produced at the example of my own Duolingo stats.

## Setup

Set up a Python environment at the version specified in
[`.python-version`](.python-version) and install the
[`requirements.txt`](requirements.txt).

Then grab all e-mails you have ever received from Duolingo (it doesn't matter if
non-stats related e-mails are also included), export them as `.eml` and place
them into the [`emails/`](emails) directory. In case you use the native macOS
e-mail app, you can just search for `Duolingo`, select all and drag & drop them
there.

Now run the [`stats.ipynb` Notebook](stats.ipynb) & enjoy!
