# keyboard-pro

## Description

keyboard-pro is a fun, fairly simple project to get started with HTML, CSS, and Javascript.

This is a development project with known list of issues, intended for accepting hacktoberfest contributions. Checkout issues board for more info.

### Features

keyboard-pro features color-based state indicators:
- Reset: Silver
- Correct text (in progress): Mightnight Blue
- Incorrect text (in progress): Orange Red
- Complete: Green

The website runs a timer once the user starts typing in the *test area*, and stops once the text in *test area* matches the *origin text*. You may reset the *test area* along with the timer anytime during the test.

The *test area* border as such changes color to indicate current state as listed above. 

### Built with

- HTML
- CSS
- Javascript
- Love

## Getting started

### Prerequisites

Nothing special. Just a javascript-enabled browser should do.

### Setup

Checkout [this](https://www.dataschool.io/how-to-contribute-on-github/) awesome guide on how to get started with your first open source contribution as a beginner.

## Contribution

This project has two major feature implementation requirements. Any PRs that achieve the features illustrated in this section are acceptable.

### State representation

1. Reset (initial) state:
![](images/001-start.png?raw=true "Reset (initial) state")
2. Correct (in-progress) state
![](images/002-in-progress-correct.png?raw=true "Correct (in-progress) state")
3. Incorrect (in-progress) state
![](images/003-in-progress-incorrect.png?raw=true "Incorrect (in-progress) state")
4. Complete (finish) state
![](images/004-complete.png?raw=true "Complete state")

### Reset button hover effect
1. The reset button is supposed to have hover animation (button and text color change):
![](images/005-reset.png?raw=true "Reset state")

### Miscellaneous
* If you can find any other project issue not listed [here](../../issues), then please feel free to [raise one](../../issues/new).

### License

This project is licensed under the [MIT License](LICENSE).