# Git Practice

## Article

[Continuous Integration](https://martinfowler.com/articles/continuousIntegration.html) by Martin Fowler, updated January 18, 2024.

## Reflection by ij2298-oss

What stands out to me is that continuous integration depends on how people work together, not just on installing an automated tool. Fowler explains that developers should integrate small changes frequently and use automated builds and tests to find problems quickly. This connects to our Git practice because making a change locally is only part of the job. The change also needs to work with everyone else's code. Smaller changes seem easier to understand and review than a large update that has been kept separate for a long time.

I also found the distinction between a successful merge and working software interesting. Git can combine files without reporting a conflict, but the combined program can still behave incorrectly. Automated tests help catch that difference, while code review gives teammates a chance to question the design. For a student project, I think keeping changes small and checking the shared code regularly would make collaboration less stressful. I would be interested in how a team balances frequent integration with giving reviewers enough time to review each change carefully.
