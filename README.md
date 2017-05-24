Parse ICS contents, namely the event start and location, and prints it out
in a human-readable format. Useful for parsing invitation files sent by mail,
right from e.g. mutt:

```
macro attach,pager \ct |"ics\n"
```
