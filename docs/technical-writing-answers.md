# Intro
The following document was created by :octocat: Jenn Leaver (@jleaver) and :octocat: Matt Desmond (@beardofedu) based on [questions asked](https://github.com/campus-experts/fall-2016/issues/32) by some of the members Campus Experts program.  


## Questions

@gillchristian

```Best practices for writing, not only how the article/post/whatever should look like but also about the process of writing it?```

Answer

```How to find topics to write about?```

Answer

@ruxiang05

```How to write about technical topics when you aren't confident about it```

I think the adage 'fake it until you make it' is perfect for this question. It isn't uncommon for a technical writer to create content for something they aren't completely familiar with. When I started as a technical writer I created content for Laboratory Information Systems (aka software for hospitals) and rarely stepped into a hospital let alone familiar with the software lab technicians were using to review my tests. The first thing you need to remember is you aren't alone when trying to create content for something, and there are more knowledgeable individuals who would love to make sure their content is documented accurately. Using an open source project as an example, if you were to volunteer to create content for an open source project that you were interested in but weren't at an 'expert knowledge level', I would imagine the project owner would just be thrilled that someone wanted to create the content they didn't have the time to create. Additionally, your inexperience can be viewed as a positive, who better to create content on a project than a user who isn't an expert? You are going to run into the novice-level problems that most project owners probably won't identify.

Without diving into this topic for pages and pages, I think the biggest thing to remember is, everyone has been a novice before and your inexperience with something shouldn't be a detractor to creating content. As silly as it sounds, if you believe in your ability to do the necessary research to create awesome content, you can 'literally' write about anything.

-@beardofedu

```Best practices for writing```

From a software documentation thought process, identify your needs and wants early and often. It might be awesome to create content for an extreme edge-case because you are excited about it, but how many users are actually going to need that content over some basic workflow content? Try and find the issues that the user is going to run into when going through a process and highlighting those issues in the documentation with 'notes' or 'labeled content'.

Iteration is key. Before I started teaching GitHub I transition documentation from CHM-based documents to HTML-based documentation that could easily be updated as the product changed. Don't be afraid to release content that covers 90% of the use cases for a product and adjusting on the fly as time allows. It isn't uncommon for a feature to be incomplete by the time documentation is needed, get your documentation as close to done as possible and adjust or fix it as needed once the product has been released.

Take chances; change your the delivery format (users accustomed to paper manuals? move to web-based content as an example), encourage users to discuss issues on a forum monitored by the documentation team as opposed to sending emails to support (MadCap Software fostered an amazing forum community which I'm sure reduced support ticket submission), etc.

Encourage users to suggest changes or provide their own content. Advanced users enjoy providing how they accomplish tasks in a more streamlined process than the one you provide documentation for. Adjust your documentation based on the input from users and your documentation will definitely benefit and be better.

-@beardofedu

```How to get ideas on technical writing```

For this question, I  think you can group 'technical writing' into two categories: Software Documentation and Technical Concepts content. My experience as a technical writer focused on developing content for applications that were in development or already released for internal/external use.

From a software documentation standpoint, I typically identified the 'standard' use case of the software and developed an outline of the content that would be most beneficial to the user(s) (EDIT: go into detail about identifying users in @kim-codes question about defining an audience).

On the other hand, creating content that is more conceptual in nature, let's say, using GitHub Pages for Product Documentation, you could identify what delivery methods are currently used by most organizations, describe how GitHub Pages would be used as a delivery method, identify the pros and cons of the various delivery methods ('typical delivery method' vs GitHub Pages), etc.

If you are planning on creating content for Open Source projects or conceptual  content (for a blog or something similar), focus on topics you have are interested in, you are more likely to finish a document if you would benefit or be interested in the final product as a reader.

-@beardofedu

@kim-codes

```How does technical writing differ from any other type of writing? What should we pay attention to/be mindful of?```

I remember taking a creative writing class in college as the only 'technical writing' major and the teacher reference my degree choice as a 'writer who wanted to make a living as opposed to being creative' which needless to say didn't get a standing ovation from me...

Depending on your content, my background is software documentation, technical writing is typically more 'process driven' aka how does a user successfully complete a task. The field definitely has room for creativity, but typically in how you can deliver content more efficiently (what delivery method will actually get views? are users able to read your instructions and actually use them? etc.) as opposed to say marketing writing where you make a pair of pants sound like the only thing that is keeping you from enjoying your life (subtle jab at marketing writing).

My personal opinion on technical writing is to deliver content in an easy-to-read format and get the user to their desired destination as quickly and efficiently as possible. If we used giving directions as an example. informing a driver about the lefts and rights they need to take to successfully reach their destination is important, informing them that their is an amazing diner along the way is extraneous and takes away from their desired goal.

-@beardofedu

```How in-depth do we go? Does it depend on our audience? Is that something we should define before (define our audience)?```

When creating software documentation, the team I was on used a 60-30-10 rule to identify what content we should focus on. The breakdown for this rule looked something like this:
- 30: Below Average User - User unfamiliar with using software to complete a specific task. Uncomfortable using a computer for day-to-day activities. Need content that some would identify as incredibly basic / rudimentary. Some examples of content I created for this range included: Identifying how to use a mouse and What a keyboard shortcut was.
- 60: Typical User - Potentially had previous experience using software to complete similar tasks. Comfortable using a computer to complete daily activities. Borderline expert user but still gets hung up on some of the advanced uses of the software (either needs to look at documentation to complete the task or ask a co-worker for assistance). Some examples of content at this level includes: Performing X task (essentially 'out of the box' workflows aka what the user bought to software to accomplish) and similar content.    
- 10: Advanced User - Learns software to complete daily tasks easily. Looks for workarounds or shortcuts to complete tasks. Identified as the 'go-to person' when teammates encounter issues. Potentially creates internal content for their team on how they should be utilizing the software. Some examples of content at this level includes: Administrating your team on <software> and Creating custom workflows.

-@beardofedu

```Is writing in first person for technical writing 'bad'?```

My experience as a technical writer revolved around creating content for software and providing instructions for how to use said software. Using 'first person' language in that capacity wouldn't have been helpful for the user and really didn't fit with the overall narrative of the content I was producing. When creating instructions for a product, you are typically identifying what the *user* should be doing so using *I* or *We* wouldn't really fit.

If you are creating content for a technical blog (product review, researching a new trend, etc.) the use of first person writing might seem viable, however a basic Google search for `first person technical writing` identified that most scientific documentation guidelines prefer avoiding the use of *I* and *We* (It was found that vs I found). Off the top of my head, it isn't uncommon to see something like 'We tested the iPad's battery by....' in a product review, so it might be best to identify how you want to relay information to your reader and be consistent about it.

-@beardofedu

```If it would be possible to see a 'bad' technical post vs a 'good' technical post.```

Answer

@shubheksha

```How much do you need to know about the topic?```

Answer

```How do we decide the difficulty level of the post?```

Answer

```Average amount of research needed for a topic you're not to familiar with/an expert on?```

Answer

```How to choose a title that caters to the majority of the audience w/o evading anyone?```

Answer

@lionex

```How do we find or identify an audience?```

Answer

```What helps to reach a wide audience?```

Answer

```How should we approach pedagogical writing, and what kinds of supporting or supplementary materials should we provide?```

Answer

```What style, in a literary and grammatical sense, do we employ in technical writing?```

Answer

```How can we create effective supporting documents? (I mean items like meeting notes, design specs, etc)```

Answer

### Related Links
Blog: [I'd Rather Be Writing](http://idratherbewriting.com/)
Conferences / Meetups: [Write the Docs](http://www.writethedocs.org/)
