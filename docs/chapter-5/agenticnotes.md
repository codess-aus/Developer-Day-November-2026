
## Slide 1: Agentic engineering past the pilot: An Enterprise Playbook

Good morning, everyone. Welcome to Universe!
[Brief introductions.]
Today is about getting beyond a successful pilot.
How do you make agents part of the way your organization builds and ships software, rather than something a few enthusiastic people use?
We'll start with a little audience participation, talk about what needs to change, then bring it to life with the product and a demo.
We've planned around 30 minutes, with another 10 for your questions.

## Slide 2: Large statement

If you've been to one of my talks before, you know I like a bit of audience participation.
So we're starting with a quiz. Nothing too painful. Shout out your answers, and we'll see how close you get.

## Slide 3: How many commits did GitHub receive this time last year?

Think back to this time last year, just before Universe.
How many commits do you think GitHub received in a single week?
I'll give you a clue: we're talking millions.
[Take two or three guesses before advancing.]

## Slide 4: 236 Million / week

236 million commits. In one week.
And to put that in perspective, it's about 1b per year. That's the most GitHub has ever received in history.
That's our starting point. Keep that number in your head, because the next question is about what happened in just 12 months.

## Slide 5: Now, what about last week? 12 months on.

Now bring it forward to last week.
Same platform. Same seven-day window. How many commits do you think we received?
[Take a few guesses.]

## Slide 6: 1.225 Billion / week

2.1 billion commits. In a single week. That's more then we saw in 2025 all together, in a single week
[Pause. Let the number land.]
We've gone from hundreds of millions to billions.
Quick bit of audience math: compared with 212 million, how many times larger is that?

## Slide 7: 5.8x

Roughly ten times.
The barrier to creating code has dropped dramatically. Experienced developers can do more, and people who wouldn't previously have built software can get started.
We saw examples of that in the keynote.
But I want to ask a slightly different question.

## Slide 11: Does everyone here feel 418% more productive?

Hands up: who feels ten times more productive than they did this time last year?
Not ten times more code. Ten times more useful work getting into customers' hands.
[Pause for the response.]
That's the distinction I want us to focus on.
The productivity gains can be real. But more commits across GitHub don't mean every developer, or every organization, is delivering proportionally more value.
You might be starting more work, opening more pull requests, and generating more code. Are you also finishing more work? Shipping better software? Solving more customer problems?
More activity isn't automatically more progress.
So what gets in the way?

## Slide 12: We automated authorship. We didn't focus on what it means to build software.

As an industry, we've put enormous effort into making code easier to write. And it's worked.
But look at everything around that one step.
You still need to understand the problem, decide what matters, design a solution, review it, test it, and ship it safely.
If we accelerate coding but leave the rest of that process unchanged, we don't remove the bottleneck. We move it.
And one of the clearest places we're seeing that is verification.

## Slide 13: The bottleneck moved. Nobody moved with it.

I hear a version of this from customers all the time: "We can generate the code. Getting it reviewed and shipped is the hard part."
Faros AI's 2026 study gives us a concrete example. It compared periods of low and high AI adoption within the same organizations.
Median time in code review increased by about 441%. And pull requests merged without any review, human or automated, increased by about 31%.
That's an increase in unreviewed merges, not a claim that 31% of all pull requests went unreviewed.
These aren't GitHub-wide figures, and they don't mean every team has the same experience. But they show the pressure: work can spend longer waiting for review, while more changes also get through without it.
We need to improve that process, not just generate more work for it.
[Source, not spoken: Faros AI, The Acceleration Whiplash, takeaways 7–8.]

## Slide 14: Generation got cheap.

Generating a change has become much easier. Knowing whether that change is correct, secure, and ready to ship still takes work.
And as the volume grows, that work becomes more important.
The answer can't just be asking the same reviewers to read faster. We need better checks earlier, clearer context, and agents helping with verification, not only generation.
The goal is more software we can trust, not just more software.

## Slide 15: Human request

That's the shift this picture represents: plan, build, verify, and observe, with context carried through the whole cycle.
Work might start with a person's request, a code change, or a signal from production. But the outcome we care about is something finished: a feature delivered, a bug fixed, a dependency updated.
Use the latest models. Put agents to work. But look at the process around them too. Where does work wait? What context gets lost? What has to happen before a change is ready?
Getting past the pilot means making that whole cycle work, not just making the coding step faster.
As we move into the demo, watch for that. Not only what the agent writes, but how the work gets checked and completed.
Over to you.

## Slide 16

* Check in on 4th – preferred purveyor of caffeinated concoctions
* Few enhancements needed to our public facing site

* Take a look at how 4th has built an agentic sdlc with CP
* but first, let's take a look at the not so old way

* NICK: Like most things in work---meeting

## Slide 17

Know the drill: team gather in room on a Monday
Discuss, take notes (transcript?), agree on next steps, then...on to the next meeting

NICK: And at that point we all know exactly what needs to be done...

## Slide 18

Nope, then we dig into Slack for follow ups. Weigh alternatives.
Asking people for more context, maybe alt-tab b/w code
Figuring out when Nick's going to open those tracking issues

## Slide 19

* Sometime during this the issues are opened* Always complete, right? Not just the template text and a quick title?

## Slide 20

* More complex work may require detailed documentation
* Context, Decision, Alternatives, Consequences
* ADR or other name, maybe committed in

## Slide 22: Days of work!

* All this happens before code is touched
* The long tail takes days
* So what's the new way

## Slide 23

* much like the old starts In a meeting* BANTER
* still discussing what we want to do, but here's where it changes

## Slide 24

After meeting slip Copilot DMs start session
Pull in Observability and Business data, transcript
Check assumptions

## Slide 25

Results shared w group, discussed
Quick mock up added, idea further refined

## Slide 26

Copilot tasked w creating issues...CLICK and filling in the deets

## Slide 27

Here they come now

NEXT SLIDE AZ BOARDS

## Slide 28

Of course, if you're planning in something like Jira, or Azure Boards

## Slide 29

Once opened, automations by gh-aw spring into action
triage each issue T-Shirt size & core area(s)
4th grew confident enough to start asgn XS/S direct to copilot
Frees the team to focus on further defining and refining more complex work

## Slide 30

Much now happens in GH CP App
Become fav of many teams at 4th (GH)

## Slide 32: /PLAN

Left (projects, sessions)

## Slide 33: /PLAN

Access each project's issues
Hey look, there's the triaged...and CP assigned

## Slide 34: /PLAN

grab an issue + create session to work
This API is bigger amt work, need plan
Call the plan task
Agt consult: tools, skills, mcp, code
Developer guides, refines

Pattern: multipath- /plan, spec-kit, lightweight between?

## Slide 37: 10:04 AM PLANNING THREAD IN SLACK

Recap. Started the morning planning in a meeting and slack

## Slide 38: 10:04 AM PLANNING THREAD IN SLACK

Got our issues opened, triaged, and some work began

## Slide 39: 10:04 AM Planning thread in Slack

Later in the morning we had an approved plan for implementing a more complex task

## Slide 40: LESS THAN 3 HOURS

All before lunch.
alignment & planning once days -> hours
Now time to check in on implementation

## Slide 41: Before: one task at a time.

4th Coffee is not new to Copilot
They're much like the majority of all you enterprise companies in the room...we have the data
Code completion in IDE and adding agent mode
Work often single threaded, sessions not operating in complete isolation

## Slide 42: Now: agents build the plan in parallel.

Now the agents build in parallel
Saw part of this when Copilot was auto assigned to issues
And in the copilot app

## Slide 43

The GitHub Copilot App makes this so much easier to manage
Each session runs on its own isolated version of the code (worktree)
Multiple sessions across multi projects
Here's the API implementation
I'll just go walk the dog..

## Slide 44

Oh, forgot about that mtg
Walk dog after
Catch up on a few bits
Now I'll go walk the do

## Slide 45: Inspiration strikes anywhere. Pick up the same session.

Steer same session from phone
Dog had  energy to burn
Need to get this

## Slide 47: Every agent runs on three new capabilities

With memory
Dreaming
'27 is the year of the cloud dev environment

## Slide 48: WORKING

All these agents are powered* Single agentic harness
Access to all models & Fusion
With memory
Dreaming
'27 is the year of the cloud dev environment

## Slide 50: Code generation is the easy part. Verification is the new bottleneck.

Now aligned on what needs to get done.
We've got our teams using a fleet of agents to plan and implement our features.
CLICK
Should be G2G, right? nothing to slow us down now…Oh that's right....All that's gotta be verified.(NICK): like I said at the beginning.

Reference to 2010s focus on agile

## Slide 51

Just in time for Halloween, It's the monster PR.
You've seen / been stuck reviewing
might have created your fair share
Agents are creating more of them…and larger.
you've got to find the needle in the haystack.
&  several features blocked by this behemoth
No wonder the YOLO merge rate is going up.

## Slide 52

That's why we shipped stacked PRs (GA)
People and agents break up work
Dependent work stacked on top
Copilot stacked API on top of index update, then the map, then docs
This makes review easier, kinder…and it also unblocked the work of those building on top

GA

## Slide 53

Of course, each of those PRs still need to be independently verified.

## Slide 54: Code Quality

Agent & human gen code held to the same high standards
Running GitHub Code Quality helps ensure all code created aligns with good practices and the standards of our company.

## Slide 55: Copilot code review

Copilot Code Review on each PR - helpful first-pass
reducing review burden for team members
It's customizable to the orgs way of working and the level of analysis is configurable.
Lite, Balanced, and now a Max mode for the most complex changes.

## Slide 56

Moving faster requires more robust security practices.

## Slide 57: AI scan for PRs and repos

AI scanning of PRs and repositories for languages not covered by CodeQL
PRs targeting HCL, PHP, bash scripts, SQL, and legacy languages like COBOL are now covered.

## Slide 58: AI secret detection

AI powered secret detection
GH is now looking out for 180+ providers
AND ALSO things that look secret-y, but aren't well structured.

## Slide 59: License compliance

License Compliance, (GA), ensures any new packages introduced by a PR are in full compliance with an organization's open source policy.

## Slide 60: Agentic Autofix

If Copilot detects a security issue in the PR, agentic autofix will automatically suggest the repair.

## Slide 61

That process happens across every PR
Wait – This is looking familiar.
Now burden is shifted from reviewing to keeping track of all our PRs & addressing feedback and helping them get to green.

## Slide 62: Copilot keeps watch and cleans up while you keep building.

That's where agent merge steps in, Copilot will keep watch over your PRs in the background, and work to automatically:
Fix actions failures
Address review comments from peers and Copilot Code Review
Fix any merge conflicts
And optionally merge it when all checks pass

## Slide 64: To build software, you need the whole process.

These aren't separate stages
Go through each of the new product relases on what makes it posible
We want you to work with agentic pace, we want you to move at the pace you need to, but that doesn't take away from the fact you need an ability to collaborate on a plan, it doesn't take a way from the need to verif. It isn't just focused on thecode
We want you to think about these features as one

## Slide 65: The takeaways

So, what are some key takeaways we want you to takeaways
Start with a plan, align with the business. It's easy to focus on the code, and that's because it has so much of the agentic pracitses

Secondly, context your context, and it's not just on code. Think about using WorkIQ/FabricIQ in the planning

Third, for the bigger tasks, maybe requires a few rime, focus on the habbit of intent

## Slide 66ipped. The hidden slides (21, 35 and 36) have no notes. The slide numbers above are for the deck as it stands now.
