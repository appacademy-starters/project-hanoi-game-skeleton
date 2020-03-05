# Towers of Hanoi: Reading and Passing Tests

Time to put your newfound mocha knowledge to the test! In this project you'll be
following what is now a familiar pattern - running automated tests and writing
code to pass those tests. The difference this time round is that we will only
provide very minimal written information for the code you'll be writing. This
project will revolve around reading the provided tests and then writing code to
pass those tests.

We've provided you with a skeleton for a JavaScript version of the famous
[Towers of Hanoi][hanoi] game. If you've never played the game take a moment to
watch a quick video of how it is played or check out [this][hanoi-game] playable
version (beware the game has sound). For the version we are building, a game of
Towers of Hanoi will be played using three towers and using three pieces which
we'll refer to as `disks` from now on.

Once you've downloaded the skeleton make sure you `npm install` to install the
dependencies the tests will rely on. We'll be using [`Chai`][chai] in
combination with [`chai-spies`][chai-spies] as our assertion libraries for this
project so we recommend keeping both documentation pages open. The tests you'll
be working on will be in the `test/game-spec.js` file and you'll be doing all
your work within the `hanoi/hanoi-game.js` file. You will not need to specify
any new methods upon the `HanoiGame` class - just fill in empty methods
provided.

Carefully read each spec and concentrate on passing them one at a time in the
order they are written. As always, to run the specs use the `mocha` command in
the top level directory.

You got this! Once you've passed all the specs feel free to play a game of Hanoi
in your terminal by running `node hanoi/play-script.js` before moving on to the
next project.

[hanoi]: https://en.wikipedia.org/wiki/Tower_of_Hanoi
[hanoi-game]: https://www.mathplayground.com/logic_tower_of_hanoi.html
[chai]: https://www.chaijs.com/api/bdd/
[chai-spies]: https://www.chaijs.com/plugins/chai-spies/
