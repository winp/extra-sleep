Sleep for specified time in Windows Console.
> 1. Download [exe file](https://raw.githubusercontent.com/winp/extra-bel/master/ecd.cmd).
> 2. Copy to `C:\Program_Files\Scripts`.
> 3. Add `C:\Program_Files\Scripts` to `PATH` environment variable.


```batch
> esleep [options] [<milliseconds>]
:: [-d|--days <days>]
:: [-h|--hours <hours>]
:: [-m|--minutes <minutes>]
:: [-s|--seconds <seconds>]

:: [] -> optional argument
:: <> -> argument value
```

```batch
:: sleep for 250 milliseconds
> esleep 250

:: sleep for 8 seconds
> esleep 8000

:: sleep for 2 days 8 hours
> esleep -d 2 -h 8
```
