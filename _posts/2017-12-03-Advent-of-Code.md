---
layout: post
title: 'Advent of Code'
tags:
- Jekyll
- AdventOfCode
- C++
---
![_config.yml]({{ site.baseurl }}/images/pexels-photo.jpg)

Once again we are in this magic holiday season.
Aroma of cakes and Christmas tree is right around the corner. For geeks like me its time to roll up their sleeves and dive deep into algorithms & competition.
For those that are not aware new [Advent of Code](https://adventofcode.com/) just started!.
Follow by its [reddit](https://www.reddit.com/r/adventofcode/) description:
>Advent of Code is a series of small programming puzzles for a variety of skill levels. 
>They are self-contained and are just as appropriate for an expert who wants to stay sharp as they are for a beginner who is just learning to code. 
>Each puzzle calls upon different skills and has two parts that build on a theme.

During the current month, all of my solutions to these puzzles will be on [my github](https://github.com/michalglen/AoC_2017)
and unlike last year (ah python one-liners) this time, I will try to get all solution written in modern C++ (11 and forward).
For quick unit test (gtest is too big) I used small helper which provide me with nice colorful output :)
```c++
template<typename V, typename F, typename... P>
void testEQ(V v, F f, P&& ... p){
    if (v == f(p...))
    {
        cout << "\033[1;32mPASSED\033[0m" << endl;
    }
    else {
        cout << "\033[1;31mFAILED\033[0m" << endl;
    }
}
```
For anyone that has rivalry in his blood & wants to be high on [leaderbord](https://adventofcode.com/2017/leaderboard) few tips
* use high-level language like Python, Ruby etc.
* get familiar with your preferred language standard library
* prepare helper functions for file opening, testing etc.
* avoid reading as much of the flavor text as possible & focus on examples (although read them later:))
and most important one
* practice makes perfect.

Cya next time and have fun with coding.