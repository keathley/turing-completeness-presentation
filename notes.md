* Explain Universality
* Explain the machine
* Problem 1:
  - The rules and machine are the same thing
  - that means that we have to have a machine to solve every problem
  - OR
  - we need a machine that can understand turing machines.
  - This is Universality
  - This is how modern programming languages work.
  - We feed them code -> they run it.
* Problem 2:
  - The tape head system doesn't seem very "scalable"
  - Talk about Ram and how we can replace the tape strip. Emphasize that
    we didn't make things more powerful, we simply made them faster.
  - Power means that we could solve problems that we could not have solved
    before. The enhancements that we could make to a Turing machine could
    be replicated by a turing machine.
  - TL;DR - Everything is equally powerful and there is nothing we can do about
    it.





# Conclusion

Many people get dismayed by the fact that everything is equivalent. They think
equivalency means that they never have to learn anything besides their pet tool.
I have the opposite reaction. I'm encouraged to learn more. Looking back on this
year I've shipped code that was written in:

  * Ruby
  * Node
  * Javascript
  * Python
  * Elixir
  * Java
  * Go
  * Rust
  * Haskell

If I had to pick one I probably learned the most from learning Haskell. I spent
about 3 months learning Haskell with some friends and even in that short time it
had a huge impact on me. It forced me to think differently about data, program structure, purity, correctness, and most importantly, types. In the end I even created a little web service with it. I haven't written much Haskell since then. However, I've taken all of the experience and lessons from writing real Haskell code and applied them to languages I spend more time in. Now the Ruby and Javascript I write looks a lot more like a series of functional transforms. The "work" of my code is much more separated from the "arrangement" of my data. Even in Elixir, a functional language, I tend to use type specs, behaviours and protocols to achieve some of the same type system power inherent in Haskell.

That's why Turing completeness is amazing. It allows you to appropriate everyones good ideas and apply them in your favorite language. Turing completeness empowers you to make your favorite tools better. By the same token it creates a world where you can choose to use the right tool for the right job because the right tool is the tool that empowers you and your team to get things done. If no one on your team wants to write Java, then you don't have to. You can favor tools that empower your people, which at the end of the day, is all that matters anyway.

Notes:
  - Instead of just stating the issues here it would be good to give examples.
  - Explain by saying, "Ok so this obviously isn't going to scale for 2 reasons"
  - 1. We will have to build a custom machine for every application.
  - 2. There are limitations of the tape and tape head system.
