# talk ideas for you to steal

I have more ideas for programming talks than talks I actually want to give.

Here are a couple of talk abstracts. I would 100% go to these talks. feel free to steal them (or slightly more likely, come up with a talk that *you're* more interested in giving)

### Writing Fast Code in Slow Languages

Audience: all Python programmers

Are you frustrated by the speed of your Python programs? You don't need to be. Python is slow, but it's not *that* slow. You can run [100 million](http://computers-are-fast.github.io/) iterations of a loop in a second in CPython. We'll get deep into the performance limitations of Python code, give you intuition for where to spend your time optimizing, explain when it might be appropriate to use PyPy, and get you to write code that's comparable (not more than 10x slower) to the equivalent C/C++ code.

(title stolen from http://prog21.dadgum.com/210.html)

### What you need to know about JVM garbage collection

Audience: Java/Clojure/Scala programmers who aren't super familiar with JVM internals

Have you ever written a JVM web application? Then you've probably seen your application stop for seconds because of garbage collection.

All hope is not lost! Understanding a little more about how JVM garbage collection works can take you a long way. We'll discuss the basics, talk about how to monitor your workload, do memory profiling, and make your JVM application run more reliably.
