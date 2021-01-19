---
layout: fr
title: mj part time coding (3 months)
author: mj
date: 10 Jan 2021
amount: 64
milestones:
  - name: 1st-month
    funds: 33% (21 XMR)
    done:
    status: unfinished
  - name: 2nd-month
    funds: 33% (21 XMR)
    done:
    status: unfinished
  - name: 3rd-month
    funds: 33% (22 XMR)
    done:
    status: unfinished
payouts:
  - date:
    amount:
  - date:
    amount:
---



# What

I propose to work for 3 months, spending additional 20 hours a week on Monero Core, on topics such as CI fixes, general firefighting, reviewing, and when there’s nothing left to extinguish, fixing compiler warnings and Clang-Tidy findings.


# Who

Without repeating too much info from [my previous CCS proposal](https://ccs.getmonero.org/proposals/mj-compil-time-reduction.html), I have now 13 years of experience in IT, a master’s degree in Computer Science and specialize in coding in object oriented languages and support-like tasks. This includes using specialized tools to find causes of problems, instead of relying on a gut feeling.

My achievements so far, are [documented in this post](https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/138#note_10583).


# Why

After starting my previous work package for Monero, I noticed, that it was hard to follow my fixed plan, because of many tasks, that were arriving in-between. These tasks were mostly CI fixes, that couldn’t have been predicted before. I see, that there’s a strong need for somebody to help fixing them while they arrive. There still exist some prevailing bugs, waiting to be fixed, like the infamous random crash (with about a 65% chance for every build) of the `functional_tests_rpc`.

Another reason for my plan being delayed, is that there seems to be a lack of reviewing power. The team was also super busy doing great job with simulating and fighting off attacks on the network, but because of the lack of man power, [list of my open PRs](https://github.com/issues?q=is%3Apr+is%3Aopen+author%3Amj-xmr) stagnates and I need to spend empty hours on resolving conflicts, while other branches are being merged. I’d like to help in both of those tasks (reviewing and improving security) as much as I can, so that the hands of others are freer.

Thirdly, as a partial, but already usable result of my previous CCS proposal, I started to automatically and regularly generate a report of Monero code base from various perspectives. The report is available for everybody [on this page](http://enjo.hopto.org/pub/monero/).

This helped me discovering, that there’s a lot more work to do on the code base, than my fixed plan assumed. The type of work to do, shown mostly by Clang-Tidy, is a mixture of overreactions (errors of low severity) and serious memory-related bugs, that either sporadically crash the application already or could crash it in the future, when some yet untested parameter combinations are to be used.


# Proposal

Realistically I am able to spend 20 hours a week more on the project. If the Community wishes to "hire" me for the mentioned perpetual tasks (not covered by my first proposal), then I’ll arrange it accordingly with my job. The previous proposal is still in place, but for reasons not related to me, it can’t move at the pace, that I initially intended. I’d like to oil this machine in all possible ways.

I propose a wage of 40 $/h for 3 months. The XMR/USD as of 10.01.2021 is at around 150 $. This would make a total of:
40 ($/h) *  20 (h/week) * 4 (weeks) * 3 (months) / 150 (XMR/USD) = 64 XMR.

Cheers!
