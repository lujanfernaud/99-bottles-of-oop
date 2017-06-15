## 99 Bottles of OOP

My work through [99 Bottles of OOP](https://www.sandimetz.com/99bottles) by
[Sandi Metz](https://www.sandimetz.com/) and [Katrina Owen](http://www.kytrinyx.com/).

### In Brief

Write the *Shameless Green* solution described in the book for *99 Bottles of Beer*
using TDD. Then, refactor the code to meet the requirement of outputting
'1 six-pack' instead of '6 bottles' in verses seven and six of the song.

### To Remember

#### Flocking Rules

1. Select the things that are most alike.
2. Find the smallest difference between them.
3. Make the simplest change to remove that difference:
* parse the new code
* parse and execute it
* parse, execute and use its result
* delete unused code

As you’re following the rules:

- In general, change only one line at a time.
- Run the tests after every change.
- If you go red, undo and make a better change.

#### Canons

- Strive for simplicity.
- Don’t abstract too soon.
- Focus on smells.
- Concentrate on difference.
- Take small steps.
- Follow the *Flocking Rules*.
- Refactor under green.
- Fix the easy problems first.
- Work horizontally.
- Seek stable landing points.
- Be disciplined.
- Don’t chase the shiny thing.
- Deal with new requirements by first refactoring existing code to be open to them,
and then writing new code to meet them.
