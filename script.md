Slide 1
-------
* My name is John Karahalis. I am a Computer Science student at the Rochester 
  Institute of Technology focusing on software engineering, psychology, and 
  human-computer interaction.
    * I want the world to have more usable software, and try to help by 
      creating or managing that software.
* I'm here to talk to you about my internship at Mozilla.
* My presentation is entitled "MDN Development Process Improvements: Tales of 
* an Engagement intern doing software engineering"
    * That subtitle is obviously a bit tongue in cheek, and I'll get to that in 
      a moment...

Slide 2
-------
* But first!

Slide 3
-------
* I wanted to extend my thanks to everyone who made this internship possible. I 
  am grateful for everyone at Mozilla, but there are a few people in particular 
  I would like to point out.
    * Julie, who helped an excited young kid join the company of his dreams and 
      who helped him along every step of the way
    * Jill, the first person I met here in Mountain View who made this summer 
      as fun as it was educational
    * My manager Jay Patel, who gave me the creative freedom I needed this 
      summer and who has been helping me move forward in my career
    * Head of Developer Engagement Stormy Peters, who I was honored to work 
      under, who also gave me the creative freedom I needed, and who really 
      recognized my passion for free software
    * and The Developer Engagement, Engagement, and WebDev teams, which are 
      all helping to make the web a better place
    * [If live] So why don't we have a round of applause especially for the 
      people I mentioned, but also for everyone here at Mozilla
    - [If recorded] I really appreciate what these people, and everyone at 
      Mozilla, have done, and they really do deserve a lot of praise

Slide 4
-------
* So what did I do this summer? This is how I capture it in one sentence. 
  "Found problems, offered solutions, and got people excited along the way."
* By the way, that picture on the left is a reference to a "Norman door", which 
  should be familiar to anyone who has ever read "The Design of Everyday 
  Things". For those who haven't, take a few seconds and think about why that 
  door needs to be fixed. [pause] That's the kind of stuff I love doing -- 
  asking why things are sometimes so hard and trying to make them better
* I joked in the first slide, but my work this summer really involved three 
  areas: engagement, user research, and software engineering

Slide 5
-------
* Engagement.
* My biggest engagement project this summer was my work to promote the June Dev 
  Derby, a contest that encouraged creative web developers to share their work 
  with the world.
* I searched for developers doing interesting work, learned as much as I could 
  about them, and "started the conversation".

Slide 6
-------
* The results?
* 11% of the people I contacted ended up contributing
* 21% of all June contributors came from this group
* 34% of all June demos came from this group
* We got some really great submissions, including some have already become 
  famous here at Mozilla.

Slide 7
-------
* User research.
* This summer, I wanted to learn as much as anything else. The team decided 
  that user research was an important topic, and I really appreciate everything 
  Diane from UX did to help me learn more about it.
* I interviewed some core MDN users and outlined all takeaways in bugs so that 
  developers could start working on them. More on that later.
* Some highlights...
    * One user said "When users start liking articles, we'll do XYZ". This was 
      really interesting. I thought about it for a while and realized that we 
      had never considered this. We never thought about users liking articles.
      But we should have.
    * Another explained that it might be hard for him to learn the MDN, as he 
      had never used it to write a spec before. Again, this was very revealing.  
      I had no idea he was planning to use the site in this way.
    * Another user mentioned that user profiles on the site should list IRC 
      handles, as Mozilla uses IRC heavily. We had planned user profiles very 
      carefully, but this never crossed our minds.
    * My favorite was a user who mentioned that he was burned ever since the 
      site went offline for an extended period of time a couple of years ago.  
      Jay, the product manager of the site, had never heard of this. But it's 
      an important issue nonetheless. The site did something to make this user 
      believe it was broken, and we need to avoid that in the future.

Slide 8
-------
* Software engineering.
* When I first joined, there were many feature discussions for MDN 2.0, but 
  spread out across different sites. Some features were discussed on EtherPad, some on the 
  Mozilla Wiki, some in Google Docs. There was no definitive list.
* I've seen this problem many times in past work. Without a definitive record 
  of features, people don't remember what they decided on, duplicate work, and 
  forget what they promised to users and stakeholders.
* I made it my priority to change this. By the end of my first week, I 
  collected all of these discussions into one, comprehensive feature list.  
  There were no longer any questions. "If we talked about it, it's on the 
  list."

Slide 9
-------
* At about the same time, the team was discussing new ideas. "The interface 
  will look like this, the software will do that, etc." The problem was that 
  these discussions were informal but very detailed.
* Developers can't implement discussions, they need small, manageable chunks of 
  work.
* But they're busy enough already. The responsibility of distilling actionable 
  work from these discussions shouldn't be on their shoulders, it sould be on 
  my shoulders.
* To help the developers, I acted as the interface between discussions and 
  actionable work. "There's a lot of stuff being discussed over there, but 
  don't worry about that. I'll worry about that. You just worry about 
  completing work that is assigned to you in Bugzilla."

Slide 10
--------
* We had similar problems with UserVoice, a tool that allows MDN users to 
  submit feedback. A lot of great feedback was provided through this tool, but 
  again it was too much for developers to handle.
* UserVoice also presented new challenges.
* Contributing needed to be easy for developers *and* for users.
    * The development team loved to have Bugzilla tickets, but users probably 
      would not have loved to submit feedback that way. Instead, they preferred 
      the simple "Feedback" button that UserVoice provided.
* Finally, I wanted to ensure that people providing feedback on UserVoice were 
  rewarded for their efforts. They took the time to submit this great insight, 
  so they deserved to see some action taken in response.
* Again I turned these thoughts into individual tasks. Developers had specific 
  tasks and users had an easy way to provide feedback. Everyone was happy.

Slide 11
--------
* And finally, my main focus this summer. I was hired for this internship 
  especially because I had experience with Scrum, a software engineering 
  framework.
* This team had never used Scrum before, so I started slow.
    * I created a product backlog, that big, definitive list of features I 
      talked about earlier.
    * Every three weeks I would meet with the development team to look at that 
      product backlog, identify the high-priority work, and turn it into a 
      Sprint backlog, a list of things that should be done within a three-week 
      period.
* But most importantly, I started retrospective discussion -- a chance for the 
  team to identify what aspects of our process were working well and what 
  aspects weren't. As far as I am concerned, these discussions are the 
  cornerstones of Scrum.
* In these last few slides, I will outline some of the improvements that I 
  implemented in response to these discussions. Bear with me -- there are many 
  examples here (and this list doesn't even include everything!), but I think 
  it gives a good overview of the process improvements that were made.

Slide 12
--------
* This one is sort of meta. A team member mentioned that "We should start an 
  email thread for discussing changes to our meetings and processes."
    * "We should start holding retrospective discussions."

Slide 13
--------
* I started an email thread to do exactly that. After doing this for a while, I 
  got some additional feedback from the team. "I'm glad we're actually making 
  the process better."

Slide 14
--------
* Here's another. "I would like if we had a Daily Standup."
    * For those unfamiliar with the term, a Daily Standup is just a short 
      meeting for a team to touch base once a day and identify problems that 
      are holding it back.

Slide 15
--------
* Again, I started doing exactly that.
* A couple of weeks later, I got more feedback from the team. "Daily standups 
  are great! They're short, unobtrusive, and I get a daily sync of what 
  everyone is doing."
    * These are all actual quotes, by the way.

Slide 16
--------
* Another. "I lose track of what I actually need to do for a release."

Slide 17
--------
* The solution? Provide a public link to each Sprint backlog, broken down by 
  team member.

Slide 18
--------
* "Our releases keep slipping."
    * If work was not done by the original deadline, the deadline was just 
      pushed back.

Slide 19
--------
* To solve this, I helped to enforce more strict "timeboxes". If work wasn't 
  completed by the deadline, it was moved out to later.
* This is an important point. The features moved, not the release dates.  
  Because we decided on a high-level goal for each period of work (which you can see 
  here), we had some flexibility to do this.
* Anyway, the result? "We finished with enough time for dedicated QA!"

Slide 20
--------
* "As a user, it's hard for me to know what you're working on."

Slide 21
--------
* I considered this a critical problem, so I responded with a very detailed 
  and well-thought-out process for providing feedback.
* The result? "This new feedback process sounds fabulous."
    * This actually came from one of the people who was most concerned about 
      the difficulty of providing feedback.

Slide 22
--------
* And finally, "We are very bad at estimating, so we never know how much work 
  we should take on at a time."

Slide 23
--------
* I worked with the team to start estimating individual tasks and, using some 
  spreadsheet magic, used this information to estimate the amount of work we 
  could complete in a given amount of time.
* The result? So far, our estimates have been more accurate. You see that 
  there is only a small difference between the average velocity (speed of 
  development) and the velocity of "last week".
* "I like the point system - I think it gives us an idea how much we're doing, 
  where we're spending our effort, and if we're on track." 

Slide 24
--------
* So that was my summer. Finding problems, offering solutions, and getting 
  people excited along the way.
* Thanks again to everyone at Mozilla for making this possible.
* My contact information is provided. Please feel free to get in touch with me 
  if you want to continue this discussion.
* Otherwise, thanks!
