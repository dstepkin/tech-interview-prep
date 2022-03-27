# tech-interview-prep

This repo was created to provide my own advice on how to prepare to tech interviews

## Learning the basics

I have no suggestions on how to learn the very basics of the first programming language of your choice. But I just list
a few things you need to know in order to continue with this guide:

- Variables and how to assign them
- Types (the most basic ones like boolean, integer, string, array)
- Basic operators (like addition, multiplication, modulo, string concatenation, logical and / or etc.)
- Conditional logic (if / else statements)
- Loops (and how to iterate through array from start to end and from end to start)
- Functions (a piece of code which could be reused)

It will be nice to get an understanding of what class is, how to create one, how to create an instance of this class and
so on.

## Preparation to algo interview

The best way to prepare to algo interview in my opinion is to solve interview-like problems. The most popular site to do
it is [LeetCode](https://leetcode.com/). So make sure you have an account there since most of the recommendations below
require it.

### How to solve LeetCode problems

Since preparation to coding interview is mostly about the volume of problems solved and about understanding several
principles we do not need to spend more than 10-15 minutes per problem. If you did not come to any solution or idea to
try - no reason to spend any more time on this. Just try to find any hint or tip which will help you to move forward.

If even that is not enough - feel free to look for a solution and explanation on YouTube. Try to get an idea on how to
solve the problem or even the whole algorithm. But try to avoid copy-pasting a solution.
The main goal is to **understand** the solution and implement it yourself.
Even if you are not the one who invented the algorithm.

### Helpful YouTube channels

Here are some useful YouTube channels which could help:

- [Happy Coding](https://www.youtube.com/channel/UCnIYOzDChH7V8s5BqvjGSEQ) - Great explanation and solution.
- [Timothy H Chang](https://www.youtube.com/channel/UCYN7_u5craa4dZc12Ik2P0g) - Short and concise video solutions.
- [NeetCode](https://www.youtube.com/c/NeetCode) - Sometimes overcomplicated but beginner-friendly.
- [LarryNY](https://www.youtube.com/c/Algorithmist) - Real-time solution (without preparation), but a lot of content.

A few more non-beginner-friendly channels of great Competitive Programmers. Just to take a look at how pros could solve
a problem faster than newbie could even read it (;

- [Errichto](https://www.youtube.com/c/Errichto) aka Kamil Debowski
- [tmwilliamlin168](https://www.youtube.com/c/WilliamLin168) aka William Lin

And a few additional links with explanation of some useful concepts and datastructures
(most likely will not be that useful at the very beginning):

- [Alexander Le](https://www.youtube.com/channel/UC5dsglSe4sYDeN_nULuVg2Q/videos) - very few problems solved with great
  visuals
- [WilliamFiset](https://www.youtube.com/c/WilliamFiset-videos/videos) - great explanation of different concepts (mostly
  graph-related)
- [Ben Langmead](https://www.youtube.com/user/BenLangmead/videos) - just an example of how algorithms could help in
  Biology

### Getting the right mindset

Getting a job offer is a matter of good preparation. So be prepared to spend several weeks or even month on this.
Everyone reading this could do it - just keep the process going.

Solving 1 problem per day for a month is better than solving 30 problems during the first day and doing nothing for the
rest of the month.
**Consistency is key.**

Before trying to get a job offer from a particular company we need to cover the basic data structures and principles.

In order to do so it is recommended to start learning concepts one-by-one.

More to that try follow the algorithm below:

1. Read the problem (including constraints)
2. Understand what exactly need to be done (pen and paper could help)
3. Define several examples (possibly edge cases) of input data and write down the output
4. Write down an algorithm (if you can not do it on your own - use tips or YouTube explanations)
5. Implement it (the first step when you actually need a computer).

Feel free to use IDE on Step 5 if you are new to your programming language. But if you want an interview-like experience
you need to write your solution without IDE in a text editor like notepad. Syntax highlighting is ok for some cases
and [VSCode Online](https://vscode.dev/) could be used here.

Of course, you could use LeetCode editor but please avoid submitting / running incomplete solution just to try it. And
also avoid printing anything to **stdout** for debugging purposes.

You should only **submit a solution you think will work and will be accepted**.

### Building the foundation

It is suggested to start with LeetCode Cards since it has both theory articles and problems to solve.

Ideal situation is to solve the following cards in order. Since some of them have prerequisites.

1. [Arrays 101](https://leetcode.com/explore/learn/card/fun-with-arrays/) - a beginner-friendly card to warm up and to
   get familiar with LeetCode
2. [Array and String](https://leetcode.com/explore/learn/card/array-and-string/) - pay attention to 2-pointer technique
   since it is used not only in array-related problems
3. [Hash Table](https://leetcode.com/explore/learn/card/hash-table/) - one of the most popular concept in interview
   questions
4. [Binary Tree](https://leetcode.com/explore/learn/card/data-structure-tree/) - quite simple concept which helps to
   learn graph problems and recursion later
5. [Queue and Stack](https://leetcode.com/explore/learn/card/queue-stack/) - another extremely important data structure
   which need to be learned
6. [Recursion I](https://leetcode.com/explore/learn/card/recursion-i/) - introduction to a concept of recursion and
   memoization
7. [Recursion II](https://leetcode.com/explore/learn/card/recursion-ii/) - more advanced concepts like backtracking

### Deepening your knowledge

Once you get the basics you will be able to solve about 20-35% of all the problems. More to that, most likely you will
be able to pass an interview to 3rd or 2nd tier companies.

If that is not enough for you, then let's move on.
The key point here is that you need to practice and there is a separate chapter about that topic later.
But in this chapter you can find few more links and topics worth knowing about.

- [Competitive Programmer’s Handbook](https://cses.fi/book/book.pdf) - even if you are not planning to become a
  competitive programmer this book is quite helpful to learn some theory and approaches used to solve problems.
- [14 Patterns to Ace Any Coding Interview Question](https://hackernoon.com/14-patterns-to-ace-any-coding-interview-question-c5bb3357f6ed) - somewhat short article
  about helpful concepts to solve coding problems.
- **Dynamic Programming** - is a popular method to solve specific kind of problems. There is a beginner-friendly
  [5-hour video](https://www.youtube.com/watch?v=oBt53YbR9Kk) or a bit more advanced
  [videos from Errichto](https://www.youtube.com/watch?v=YBSt1jYwVfU&list=PLl0KD3g-oDOGJUdmhFk19LaPgrfmAGQfo).
- **Binary Search** - fast way to find solution if input satisfies specific criteria. Another topic worth learning.
- **Bit manipulation** - it is quite helpful to know how integers are stored in memory and how this could be utilized for solving real problems extremely fast.
- **Other data structures** - there are a lot of different data structures out there,
  and the vast majority of these problems could be solved using data structures you already know.
  But there are a few more worth taking a look at: *Priority Queue*, *Linked List*, *Binary Search Tree*,
  *Trie (or Prefix Tree)*, *Disjoint set (or Union-Find)*
- **Graph algorithms** - is a whole world. Once you become familiar with most frequent graph algorithms like
  *DFS (or Depth-First Search)* and *BFS (or Breadth-First Search)* and different graph representations like
  adjacency list and matrix you will be ok. But here are a few more worth learning:
  *Topological Sort*, *Dijkstra's algorithm* and a concept of *Strongly Connected Components*
- **Sorting algorithms** - to know the difference in complexity and applicability between different algorithms 
  is helpful. Just a few examples of such algorithms: *Bubble sort*, *Merge sort*, *Quicksort*, *Counting sort*

### Honing your skills

Alright, at this point you should at least know all the concepts in foundation section and maybe some more.
But ideally got your hands dirty and solve some amount of problems.

The only way to prepare for solving a problem during interview is to solve a lot of problems beforehand.
Solving problems is a skill and in order to acquire it you need to practice.
The smarter you practice - the faster you get the desired result.

The core idea is that there are limited amount of concepts you need to know in order to solve any interview problem.
And fortunately enough there are people who created a list of problems to illustrate (and teach) these concept.

And before getting to actual lists I suggest you to create a spreadsheet with your own notes and progress.
An example of such spreadsheet (along with the first list) is shown in
[this video](https://www.youtube.com/watch?v=SVvr3ZjtjI8). And the link to
[LeetCode list](https://leetcode.com/list/xi4ci4ig/) and to the original
[Curated list of 75 questions from Blind](https://www.teamblind.com/post/New-Year-Gift---Curated-List-of-Top-75-LeetCode-Questions-to-Save-Your-Time-OaM1orEU).

Different people called the same things differently. And another popular list is called
[LeetCode Patterns](https://seanprashad.com/leetcode-patterns/).

Of course each list is opinionated one. But the more problems you solve - the better. So here is
[Top 100 Liked LeetCode Questions](https://leetcode.com/list/79h8rn6/).

And the last but not least, 3 more lists by LeetCode itself with top interview problems grouped by difficulty:
- [Top Interview Questions - Easy Collection](https://leetcode.com/explore/interview/card/top-interview-questions-easy/)
- [Top Interview Questions - Medium Collection](https://leetcode.com/explore/interview/card/top-interview-questions-medium/)
- [Top Interview Questions - Hard Collection](https://leetcode.com/explore/interview/card/top-interview-questions-hard/)

### Putting the volume in

At this point you should be well-prepared overall.
Solving problems when you know you could get help from your notes or google something is nice.
But solving the same problems under the pressure when clock is ticking is a little different.

At this point it will be nice to become more familiar with how interview to a top tier company looks like.
Depending on that you will be able to fine-tune your preparation process yourself.

There is a [YouTube channel](https://www.youtube.com/channel/UCaO6VoaYJv4kS-TQO_M-N_g)
created by ex-Googler Clément Mihailescu where you could find some examples of such interviews.
Even though on his channel there are some interviews with "normal" applicants I decided to put a few links
to mock-interviews with great competitive programmers:
[Errichto's interview](https://youtu.be/EuPSibuIKIg),
[First William Lin's interview](https://youtu.be/qz9tKlF431k),
[Second William Lin's interview](https://youtu.be/-tNMxwWSN_M).

Since you will not be able to execute your code during an interview process you should pay additional attention to
stuff like *off-by-one error* or *integer overflow*. And please re-read the section about the correct mindset.
Hopefully you will be able to find something new after watching videos above.

Another useful thing you need to practice is to solve problems in limited time frame.
Programming competitions (contests) could help here.
I personally prefer LeetCode ones over the rest because of two things:
you do not need to bother with stdin / stdout, problems are easier and more interview-like.
Here is a short list of competitions I personally tried:

 - [LeetCode weekly and biweekly contests](https://leetcode.com/contest/) - in addition
  to what was said above, these contests are running regularly at the same time
 - [Google code jam](https://codingcompetitions.withgoogle.com/codejam) - runs once per year,
 tough problems, ability to get partial score for partially correct solution, good learning value in past events
 - [Google kick start](https://codingcompetitions.withgoogle.com/kickstart) - almost all from *code jam*
 is applicable here with a few differences. Runs about 10 times per year. The actual problems are easier than
 *code jam* problems, but harder than *LeetCode* ones.
 - [Codeforces contests](https://codeforces.com/contests) - different divisions (based on problem difficulty),
 you need to pay attention to calendar to be sure that you will not miss a competition.

Even though you could "virtually participate" into archived (past) contest,
I strongly recommend participating at least a few times live to get an idea of how it feels like.

And the last topic to cover here is actually putting the volume into solving problems.
Once you learn all the necessary concepts it is time to practice them.

One way to get volume and confidence is to sort problems by difficulty and acceptance rate
and to start solving these problems one-by-one from easiest with the highest acceptance rate to more hard ones.

Another great way to put the volume is to know exactly which company you want to join,
find the questions they are asking during interview.
And just practice these questions in order of frequency.

And the final strategy is to review your spreadsheet, find the weakest areas.
And simply work on your weaknesses by solving problems related to that topics.

But these recommendations are not set in stone, so feel free to select the strategy which fits best for your needs.

### Keeping in shape

Even if you did not put that much volume you should start attending interviews.
Simply select companies you could easily decline offers from and start your interviewing journey.

Do not wait for time "when you will be ready enough" - most likely it will not happen in foreseeable future.
And more to that interviews are not only about coding and algorithms.
Stuff like communication skills are also needed in order to get the offer.
But that is not a subject of the current document.

The main point is that if you are not working on your coding and algo skills
then these skills are slowly but surely degrading.
In order to at least slow down the degradation process you need to constantly practice your skills.

The best way from my personal perspective is to attend [LeetCode Daily Challenge](https://leetcode.com/discuss/general-discussion/655704/).
All you need to do is to solve a single problem in a 24-hour timeframe.
Problems are selected random (or close to random) and differs in topics and difficulty.

More to that for some people even the fact that you will get a badge if you solve all the problems in a month
is a great motivation itself.
But the benefit of solving daily challenges is that you are practicing your coding / algo skills every single day.
And consistency is key here.

You could even start doing daily challenges before you learned mandatory stuff like *DFS*, *BFS*, *stack* etc.
But this way you could get stuck with daily problem, and it could be quite demotivating.
So keep that in mind.

## Finishing strong

If you followed everything you read above - you are definitely prepared to any kind of technical / coding interview.
But please do not forget that no matter how good you are prepared it will only
improve you chances but will not give any guarantees.

You should accept the fact that there are some amount of luck involved in interview process.
But that is ok. That is the way it works. So keep going!

**Never give up** and good luck in getting offer you desire! (;
