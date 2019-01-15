## Contributing to DanceKickRun

Thanks for thinking about contributing to DanceKickRun, improvements and bugfixes are most welcome. 

The following is a brief set of guidelines for contributions:

* **Be nice.** Please follow the [code of conduct](https://github.com/casteer/DanceKickRun/CODE_OF_CONDUCT.md).
* **Bug-zapping** If you find a bug, please [open an issue](https://github.com/casteer/DanceKickRun/issues), with some simple steps on how to reproduce it. Try not to make duplicate requests.
* **Feature requests.** Feel free to make feature requests, also by [opening an issue](https://github.com/casteer/DanceKickRun/issues). Be clear about what it is and why it would be awesome.
* **Pull requests.** If you add a cool feature you think would be useful broadly, please issue a pull request with some notes on what it does.
* **Git comments.** ...are very welcome too, especially if they're friendly, clear, and helpful. 
* **Major changes.** As a few people use this package, we have tried to maintain backwards compatibility as much as possible. As such, please open a discussion before you start your quest, to make sure the changes can be merged without upset.
* **Unit tests.** If you add new functionality, please write a unit test (if you're familiar with how to). This should be places in the `./tests` directory, and will run with py.test.
* **Travis-CI.** When you issue a pull request, Travis-CI will automatically run the unit tests. You can test yourself by running `cd tests; coverage run --source=hickle -m py.test`.
* **Style.** Try and keep your code Py2.7 and Py3 compatible for modifications/additions to the receiver code, and roughly follow [Google's C++ style guide](https://google.github.io/styleguide/cppguide.html) for the main Arduino library
* **Beginners welcome.** If you're not yet comfortable with some of the fancier things mentioned above, hey we're here to help. Just package up your idea/thought/code and [open an issue](https://github.com/casteer/DanceKickRun/issues) with some clear details.

That's about it - we look forward to your contributions!
