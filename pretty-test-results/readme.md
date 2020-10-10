# Pretty-Test-Results

Using [Łukasz Wasylkowski's code from Medium](https://medium.com/@wasyl/pretty-tests-summary-in-gradle-744804dd676c) as - _ahem_ - inspiration, I've extended the prettification to add some features I find make the test results a little more impactful 😉

The reason I can claim some sense of ownership is the addition of the following:

## Additions
### Colorizing the results

  - Fails: Red
  - Skipped: Yellow
  - Pass: Green

### Screaming Status 
I've added an obnoxiously large, colored output to denote the overall status of the tests (credit to [TAAG](http://patorjk.com/software/taag)):

#### Pass:
```
    █████╗ ██╗     ██╗          ██████╗  ██████╗  ██████╗ ██████╗         ██╗'
    ██╔══██╗██║     ██║         ██╔════╝ ██╔═══██╗██╔═══██╗██╔══██╗    ██╗ ╚██╗'
    ███████║██║     ██║         ██║  ███╗██║   ██║██║   ██║██║  ██║    ╚═╝  ██║'
    ██╔══██║██║     ██║         ██║   ██║██║   ██║██║   ██║██║  ██║    ██╗  ██║'
    ██║  ██║███████╗███████╗    ╚██████╔╝╚██████╔╝╚██████╔╝██████╔╝    ╚═╝ ██╔╝'
    ╚═╝  ╚═╝╚══════╝╚══════╝     ╚═════╝  ╚═════╝  ╚═════╝ ╚═════╝         ╚═╝'
```
#### Fail:
```
    ██╗   ██╗██╗  ██╗         ██████╗ ██╗  ██╗         ██╗'
    ██║   ██║██║  ██║        ██╔═══██╗██║  ██║    ██╗ ██╔╝'
    ██║   ██║███████║ █████╗ ██║   ██║███████║    ╚═╝ ██║'
    ██║   ██║██╔══██║ ╚════╝ ██║   ██║██╔══██║    ██╗ ██║'
    ╚██████╔╝██║  ██║        ╚██████╔╝██║  ██║    ╚═╝ ╚██╗'
     ╚═════╝ ╚═╝  ╚═╝         ╚═════╝ ╚═╝  ╚═╝         ╚═╝'
```
