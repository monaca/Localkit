# Debugging Monaca Localkit

Although Monaca Localkit source code are obfuscated, you can save log output to a specific file.
To do so, please open *Preferences* and specify the file to dump the log output.

## Running with the debugging parameter

Monaca Localkit will run in debug mode when `debug` parameter is set in the 2nd option. See the example below.

```
> cd /path/to/localkit
> monaca-localkit . debug
```

Please note that when running in the debug mode, it will output all network requests.
