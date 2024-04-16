# Schedule for the Week

Link to [Week 45 on Canvas](https://appacademy.instructure.com/courses/337/modules#context_module_item_59659)

## Monday

On Canvas, there's only ReCap Accademy, no reading, no links

- [Local Greenlit Lecture](./Greenlit.md) 10 Minutes
- [AI Lecture Slideshow](https://docs.google.com/presentation/d/1dx58N4hnMS0oXruvShPnLlzDLI_Xho8nde6WWpFeQj8/edit#slide=id.g2577b611152_0_172)
- Talk about the general idea of AI tools, how they work, how they may output hallucinations, and where you may use it usefully (journalism, legal review etc.)
- Showcase the use of bard (https://bard.google.com/?utm_source=sem&utm_medium=paid-media&utm_campaign=q4enUS_sem7)
    - showcase how bard can access the internet unlike chatgpt. Try the following prompts with students:
        - "Find github repos that are good for learning Typescript"
        - "provides sources for the output above"
    - showcase how bard can acces recruiter info:
        - "find information on <insert instructor name>" (this will probably output info from your linkedin)
        - "Write a greeting email to the person above using the information found on their linked in to explain why I am a good candidate for their software engineering position. I have experience with Javascript, Python, react, docker, and express"
    - showcase you can have it read pdfs:
        - "read and summarize this article: https://www.congress.gov/117/bills/hr4346/BILLS-117hr4346enr.pdf" (This is a 393 page document outlying the CHIP act, which is relevant to software engineers but is too long to read)
        - "Provide bullet points for the summary in the previous prompt"
        - "Provided sources in the article for your summar output"
        - review with students that those things are referenced in the article

- showcase the use of chatgpt(https://chat.openai.com/)
    - show how each question solved should be done within a new chat window to help clarity and reduce ai confusion
    - show how to properly make prompts that follow "few-shot" style as discussed in power point

- Break out students to work on some of the problems using ai of their choice to get used to it.
- Talk about their use of AI, and provide some example promps and how you, as a human, would check the validity of some code output.
For example: If I have it solve the adjacent list problem I should specify to use javascript es6 syntax, and I should expect it to use a Set, utilize some way of finding neighbors, and use breadth first traversal so find the shortest path.


- This lecture may be done by another insturctor if you need help with grading projects.

## Tuesday

- [AI lecture part 2: Security and ethics](https://docs.google.com/presentation/d/1q7XCiGbwlIUSHBuDTk0_bb4vrhUFUSdYz3XRMSrQnq8/edit?pli=1#slide=id.g20a5ff4faf7_0_0)
    - discuss how chatgpt and a lot of these companies trained their code on open source material which has led to litigation
    - "Imaging you made some cool code and shared it for everyone for free, but then these massive companies like google and amazon which are the main ones that can afford to keep an LLM, decide to train their model on your free code and then they make a profit of it."
    - Discuss how code provided to ai may be made public and this can breach NDAs with companies for releasing private/propritary information.
    - Disucss how Scale AI recently received 50+ applications from a/A students and decided to turn down all applications during that cycle. Imagine if you spent the time prepping and studying and didn't use chatgpt but then other students ruined it for you. We almost lost this partnership because of this
    - Discuss how some a/A students got hired at a company and were found to have either used a/A on some of their projects or to be using ai for their new job and they were fired.

- Open the floor for discussion
- Have them research ethics for the a/A assignment (30 min)
- Have them work discuss with group project mates what changes they want to do to their group project and possibly plan any additional features they will want to add. Make sure they are all on the same page on if they are going to use ai or not. If one person is not cool with it, then all of them should not use it.
- Let them know that Wednesday and Thursday will be for benchmarking and strongly advise that they do not flex. If they have to flex, they should set up 3 hours of time to do the benchmark. Benchmark HAS TO BE SUBMITTED

## Wednesday

Canvas has [Road to Greenlit content](https://appacademy.instructure.com/courses/337/modules#context_module_item_59661)

#### Old notes:

- Administer the benchmark 1
    - They CAN NOT USE AI
    - This is to test their strengths/weaknesses
- Make sure to ask if anyone would rather do the Python DSA portion
- Proctor the test with strict 60 min timer
    - All students must submit at the end
- you can pull the grading template for benchmark from here:
- after all students are done being graded (after thursday) they will get a DM of their final score


- While students work on the benchmark, instructor should begin reviewing the following items and making notes:
    - Group project
        - is repo good?
        - is the site live?
        - do they have good commit messages?
        - can a demo user delete all the seeder content, and modify their own profiles (dont want demo user bio to become inappropriate)
        - are there any css bugs
        - check for padding/marin spacing
        - check for default buttons \
        - add an about footer at the bottom with a link to each students' github/personal portfolio
        - is there a 404 page?
        - do they have at least 4 REALLY well done features?
        - do they have a plan to add at least 2 more features?
    - Capstone:
        - is repo good?
        - is the site live?
        - do they have good commit messages?
        - can a demo user delete all the seeder content, and modify their own profiles (dont want demo user bio to become inappropriate)
        - are there any css bugs
        - check for padding/marin spacing
        - check for default buttons \
        - add an about footer at the bottom with a link students's github/personal portfolio, and all other projects
        - is there a 404 page?
        - do they have at least 4 really well done features?
        - do they have a plan to add at least 3 more features?

- Example of a student Anthony Bronca did a review for. This student completed all points and became greenlit on the day of graduation: https://docs.google.com/document/d/1TYnN0Xk1X9JQxPGe-aafiRlU_Ts6vjAR0I7nircIWhI/edit?usp=sharing

## Thursday

administer the benchmark 2. Make sure all students submit it. They CAN NOT USE AI. This is for their own benefit to test their strengths/weaknesses
Students should receive a DM of their score as follows:

" Your final benchmark score is: xyz%

Areas to Improve: - React - DSA - Vanilla.js

I recommend going back to the mod 3 content during job search to refresh on DOM and Promises. I also think you would benefit from attending additional workshops in these areas during your job search. Especially with regard to DSA, you may be benefit from attending those workshops on Tuesday and Thursday to increase the likely hood of passing your real technical assessment. "

After students finish React and DSA test on this date, they can move on to working on their capstone. This is the last day they will have some free time to work on it until their group project looks greenlit.

## Saturday

Group project
Showcase CRON Jon
You may also consider showcasing using google sheets to do this (super easy)