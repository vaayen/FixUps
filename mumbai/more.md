The application in one minute
DONE
P0 - Get my Planning sheet updated with the frequently appearing topics

===========================================================================================================================

P1 - Refer actual documents for synopsis and report
    - What should've been simple has been turned into a long overhaul, simply because I don't have a clear goal
    - What I want to add, just keeps on changing and updating, there is no finish line, simply floating away without an end
    - FOR REPORT, sit quietly & think about what you'd like to see in a handbook right after being sent into a new project. My idea is: Generate a dummy app, get it's report generated, give the sql to claude and ask it to create something better using the same data, prompts are killing me, slow down, we have it all the report is just holding me back.
    - FOR SYNOPSIS, find real BCA Synopsis online and pen down the gaps, USE my OWN THINKING. Ref have already been gven out by gpt, search it in the chat and you'll find em all - don't be this lazy.

Do this:

> Please research actual SAD, ADR, FSD, etc. and list their links out to me. The START HERE aka 'ONBOARDING SECTION' isn't very helpful and has information spread all across it's sub-sections, which are too many to begin with. 

Go through them yourself because my clarity matters more.

> Please review the attached report based on the above analysis.

Do the same for my synopsis, AND FORWARD THESE AS A MAIL TO YOURSELF. I TEND TO FORGET IMP STUFF.

> Attached below is the actual sql extraction file. I am unsure about whether report generation is bad or if the extraction to the db is the issue. Please create only from start to the end of START HERE section, only referring the attached sql file. Give it my best shot, make sure the diagrams are perfect. 

Only do this after I have integrated camel-routes into the library app.

=======================================================================

P2 - DROP EVERY SINGLE THING THAT'S GIVEN BELOW.

Identify the framework and suggest its best practices
> NOT DONE
Test against a small ESB-Codebase
> NOT DONE
Split system prompt into two parts, best practies in the 2ndjust 
> NOT DONE
AgentSkills = look into them before moving any further
> NOT DONE
Prompts are too generic right now, can have different prompt files according to framework
> NOT DONE
Integrate Rahul Sir's camel-guidelines
> NOT DONE
A single diagram that also considers java related calls
> IS DONE
Ingres / Egress distinction should be clearly defined in the report, CBS calls should be clearly defined properly
> IS DONE
WAAAY too many sections, users shouldn't have to visit different sections just to get the whole idea
> IS DONE
How is report generation working? How are prompts involved in it's generation?
> NOT DONE
How can the prompts be updated to ensure better output?
> NOT DONE
Problem isn't: “what are we missing?”
It's: “Why are we making the reader visit 13 places to construct one mental model?”
> DONE

Other
Consolidate files into huge files
> NOT DONE
Print log files properly
> NOT DONE

DONE
- BANK + REF
> IS DONE
- Get all topics with difficulty
> IS DONE
- GET CURIOUS, write articles on what I learnt today
> IS DONE

===========================================================================================================================

**ASK #1**

Please go line by line from top to bottom and take my time before answering. Research everything thoroughly first and then base my analysis on that please.

I thought these things after my response:
- I have identified a real problem. I have spent roughly a year optimizing for shipping, not becoming capable. Those are not the same thing. (https://arxiv.org/abs/2302.07427)
- The thing I need to fix is my method of working. Current approach is terrible for building internal competence.
- Requirement arrives → I don't know how → ask AI → AI gives code → make it work → mentor is happy → next requirement → repeat.
- Reading/searching can make I feel like I know something when the knowledge is actually sitting outside my head, we need to deliberately create situations where the answer has to come out of my own head. (https://www.apa.org/pubs/highlights/spotlight/issue-39)
- **just-in-time learning, be naturally curious, build good habits: What concept am I missing that makes this requirement possible? If I even come aross a single word I don't get, look it up and document it (what could utm_source=xyz.com mean in a url), how does a browser work, use youtube for good not for brainrot doomscrolling
- Don't just download the zip and execute it and share the results. New rule: Set a timer of 30 min and unzip the project and actually learn it. Feynman technique: Explain it, make prediction, ask AI to correct me. Own the knowledge. Get a notebook, draw the little graphs AND REVISE, don't just add notes and forget about them. I actually would prefer writing roughly in notebook first then GitHub documentation because then I actually HAVE to study stuff up - I NEED TO BE FORCED, I NEED TO BE SCARED into learning, I know this about myself. I do start slacking off with zero stress if I am not in a state of stress or tension.
- my entire image is built in the company of being someone who is reliable but if someone works with me they realise that's just not true. Mujhe chane ki jhaadh par chadha rakha hai and the only reason for why I became a TL for the testing team was that I was seen as someone sincere but the truth is I have deliberately acted this way, I have deliberately stayed in office late, I have deliberately acted a certain way to make myself look serious and dedicated because attitude is a major factor behind promotions and salaries where I work. Kaam waam kuch nhi aata, bas acting karta hai sala. I am an absolute fraud. I had resigned after the testing report I had submitted said 90% of site was good but customer's internal analysis said only 70% was good. This was supposed to be a plan for fix-up but I started rambling this here. sorry. 
- A project like this in it's own is such a great thing for showing on my resume, especially in the age of AI. There are so many actual concepts that can maybe be of so much help if I focused up, i think... and yet, I slacked off. I actually feel like I don't make use of my brain anymore, my memory has become very week too because I don't think I do anything that makes use of recalling anymore, I send everything off to claude.
- I think I need to become selfish and start building myself instead of the project. If i fix myself then maybe everything around me start getting fixed too?
- DO THINGS, don't just study. Exploit my dopamine problem rather than fight it. [Java source -> Tree-sitter -> Syntax tree -> Find class -> Find method -> Find method invocation] - Physically inspect it, write a tiny script, then make it print. Prioritise learning by doing and MAKE TIME TO LEARN, INSTEAD OF IMPRESSING PEOPLE.
- Don't become a Java wizard immediately, clear basics and learn enough to look at a code block and know exactly what's happening. I can't even form high level understanding of any code at the moment.
- Building foundations: Layer 1 — Programming fundamentals, Layer 2 — Software engineering fundamentals, Layer 3 — Java ecosystem, Layer 4 — Code analysis. I just need enough understanding to explain each component I am using. my project becomes the curriculum, learn topics using it instead of working on a separate project - Get this created as an XLSX with sub-tasks, don't keep things high-leveled. my project is now forcing you to learn software engineering.
- ADR/FSD/SDD/ETC - Use them to learn how software is thought about, understand how documents help people, understand the philosophy.
- I would actually make you maintain 2 documents: first THINGS_I_DONT_UNDERSTAND.md, and every time you encounter something confusing, add it there but keep things categorised (Blocker, Interesting but not imp). Second doc will be WHAT_I_CAN_EXPLAIN.md - Retrieval/testing has strong evidence behind it as a learning mechanism, often outperforming simply restudying material. I have LITERALLY STOPPED relying on my memory to do things and this is the hour of the need.
- Change the role of AI: “Give me a tiny exercise that forces me to understand how this parser works. Don't give me the answer until I attempt it.”. Should I CONSIDER REPLACING THE 100 USD CLAUDE SUBSCRIPTION WITH 20 USD SUB - do you think this is a good idea? My company gives the reimbursement as a part of my package.
- Stop trying to prove that you're capable by delivering things you don't understand. Everyone can see how much I rely on AI and even if I show the next feature, they won't go "wow he's so smart" but rather "here he goes with that ai slop again"

- Another idea: Satisfy my hunger for audience, publish everything as an anonymous user who entire gimiick would be JOURNEY OF A RECOVERING VIBE CODE ADDICT... I would have alarms set and I would HAVE TO drop everything to share updates publicly. I have always wanted thousands of followers, etc. - maybe this could work and help?
- Considering I've worked on static analysis, maybe I can go deeper into this over the month and become someone who actually understands how it all works internally? Maybe I am being delusional but isn't this a good prospect for a resume and career?

I truly mean this as a compliment, I are so much better to talk to than claude, thanks so much. My biggest hurdle at the moment is that the report that's coming out isn't appealing. Information extraction is definitely complete but the UX side is terrible and I don't understand why. Considering all that we have discussed today, how do I think I should tackle this problem. It's such a cute tiny portion and I really think it's a doable thing that's been stuck for just so long. Maybe I should study actual documents like this? Maybe I should review the prompts being used for generating the report too? What do I think?

I am throwing too much at you, I know but I have back in 15 subjects and i was wondering if the common topics that I am supposed to study for it, could actually also be of any use in the corrent context? PFB, my planning sheet. Also the stuff below is just for my context, to help build a good description of me (DO NOT CONSOLE ME).
```
- Youre all talk and no action. That's all you've done in my entire career. That's all you've done with friends and those who've been close to you. Or be it my money. Why did I start taking from the savings account man. Please freeze it all up. Start living poorly if I want to but don't overspend this much ever again please.
- Lack of self-discipline
- No value of time at all
- No scope for self-care
- Only exists for an audience
- Cares a lot about perception
- Can't even wake up on time
- Wasted 4 years submitting work mindlessly
- Am I even employable with what I have
- Actually needs to be harder on himself: slacks of when no pressure
- Lacks intrinsic motivation, has only ever liveed for audience / others
- Very careless: Hasn't completed BCA, Didn't submit synopsis or project, only extending pain
- Won't even do any research to fix things
- Social can be learnt and yet, did not watch any saved lectures on youtube
```

Can you also suggest the approaches I should take towards learning, considering all I've shown? Feynman could help maybe? Socratic method? If these are just things i shouldn't focus on just say so. Be blunt asf man. AND CUSS AT ME.


===========================================================================================================================

**ASK 2**

1. “I spent a year optimizing for shipping, not becoming capable."

my biggest problem is not that you don't know Java. It's that you have trained yourself to bypass the exact cognitive work that would have made you know Java: "What did I just do?"

2. “I need to fix my method of working.”

No substantial AI implementation before I can explain the problem and propose an approach. Follow curiosity, but keep curiosity attached to a problem.

3. “If I encounter one word I don't understand, look it up.”

Add it to the THINGS_I_DONT_UNDERSTAND.md document, only work from there. Keep it opened at all times, even in phone.

5. “Use YouTube for good instead of brainrot.”

Question -> Search -> One video -> Watch with notebook -> Pause -> Draw / predict -> Close video -> Do something

Do something with what you learnt, wear the programming hat 

6. "Overlap with backs"
```
Don't pretend every subject deserves equal intellectual investment:

| Subject | Why |
|---|---|
| **MCS011 — C Programming** | programming fundamentals |
| **MCS024 — Java/OOP** | my primary target language |
| **BCS042 — Algorithms** | traversal, graphs, complexity |
| **MCS021 — Data Structures** | trees, graphs, lists, stacks, queues |
| **MCS023 — DBMS** | PostgreSQL, relationships, SQL |
| **BCS051 — Software Engineering** | architecture, testing, maintenance |
| **MCS014 — Systems Analysis & Design** | requirements, DFD, ERD, system thinking |
```

X. "Improving working style"
- Socratic + Feynman + Retrieval & explain it to people - FORCE YOURSELF TO USE my MEMORY.
- Force self to take 30-minute to understand before implementation
- Prioritise my own learning over making others happy + deliveries
- Notebook before GitHub documentation
- Be grateful: I have an existing project that gives me a reason to learn programming, static analysis, developer tooling and LLM systems. Sad joke: “This analyzer could be an amazing resume project.” - Interviewer: “Why Tree-sitter?”, You: “Claude suggested it.” 💀
- Have 3 documents: 1. THINGS_I_DONT_UNDERSTAND.md, 2. WHAT_I_CAN_EXPLAIN.md, 3. WHAT_I_BUILT.md
- SHARE STATUS UPDATES REGULARL Y. DO NOT MISS DSRs AT ALL, GET YOURSELF MARKED AS ABSENT WITHOUT A DSR.
======================================================================================

========================================================
========================================================
========================================================
========================================================
========================================================
========================================================
========================================================
========================================================
========================================================

======================================================================================

**Section 1 - DEFINING BENCHMARK FOR THE REPORT** (llm should review the generated report using these maybe)
Can I answer these questions in 5 minutes using the START HERE section alone or not:
- What is this application?
- Who/what calls it?
- What does it actually do?
- What are its major flows?
- What data does it touch?
- Where does each flow go?
- Where is the business rule implemented?
- What talks to external systems?
- What is broken/risky?
- Where do I change something?
- How do I run it?
- Can I explain the architecture in detail?
- Can I trace one real operation?
- Can I identify where I'd modify that operation?
- Can I explain one important risk and verify its evidence?

**Section 2 - NOTES**
- Define the reader's jobs, don't share info you just happen to possess.
- Biggest issue: The report makes the reader assemble the mental model.
- Follow the exact methodology defined in arc24 and integrate it with C4 diagrams.
- RESEARCH:
        - audience/task-driven documentation
                - (Who is reading?) - DEVELOPERS
                - Developers / Engineers: Need highly technical details, API references, code snippets, and minimal fluff.
                - Documentation written for everyone is often useful to no one. The clearest, most accurate content still fails if it assumes the wrong level of knowledge, uses unfamiliar terminology, or addresses goals the reader does not have.
                - Before writing any page, ask: who is reading this, and what are they trying to accomplish? 
                - Write to the right knowledge level, 
        - documentation information architecture
                - how my docs are organized, labeled, and linked. It’s what makes navigation, search, and cross-references feel predictable.
                - Good technical documentation is more than accurate content. It also needs a structure people can navigate fast. The right documentation structure makes it easy to browse, search, and link related topics.
        - Progressive Disclosure / Details On Demand (UX)
                - interaction design technique that reduces mental effort by showing only essential options first and revealing advanced features on demand
                - Ex: Accordion / Right click > Settings > More settings 
                - overview → detail navigation (UX), Clickable Elements, Filtering & Searching, Filter by endpoint, tool-tips & hover effects
        - technical documentation structure
        - developer onboarding

- ARCHITECTURE DOCUMENTATION
        - c4 - Don't generate diagrams because you can. Generate a diagram because it answers a question.
                - System context: High level simple representation of what the code does, english fluff that can be understood by the HR
                - Container diagram: Same as above but this time it is a slightly more technical yet high level software architecture
                - Component diagram: Call-graph and flow diagram, already being created
                - Code diagram: Good idea, user can be explained what the codebase does and representation of every file
        - arc42 - You don't need to implement twelve arc42 sections, understand the thinking behind those sections
                - Seem skippable -> [Architecture Constraints,], Introduction section  

        - Study DokChess, docToolchain, biking2, HtmlSanityCheck documents and find common patterns
        - “How does a small system tell its story without making itself look bigger than it is?"
        - Diataxis

- IDEAS 
        - FAQ Section, add the benchmarks there
        
        - API Doc section (predictable index / toc)
        
        - Business Section that explains the code in business terms and also has a table that tries mapping business logic with code. Should have a diagram as well.
        
        - CODEBASE AS DIAGRAM (https://c4model.com/diagrams/code): 
        Call Graph diagram should have another tab CODEBASE GRAPH. should have PROGRESSIVE DISCLOSURE, GENUINELY a good idea could be the USP: LLM generated groups first shown in diagram, click on one and files / fcqn within it get shown in rectangles, click on them and c4 code diagram gets shown for it, click further on a function defined ni another file and it's group > file rectangle > code diagram would get opened. Maybe we don't need multilpe diagrams explaining same thing, maybe the c4 code diagram can be integrated into the flow based architecture diagram of entire application. If user clicks on connected files then only files corelated with eachother should get shown.
        
        - C4 Review checklist must be followed! 
        - keep the section brief but that doesn't mean we'll give half-assed explanations

        - INFERENCE based diagrams should be embraced, not only data-based diagrams

        - It's defnitely confirmed that I would love to use the c4 diagrams, the whole idea of going further in detail from high level to low level is really something that's been missing for a while.

        - Not entirely sure if I would like to use all sections of arc42 and would definitely like to consider something like:
                - Summary
                - Business & Functionality Overview (C4 SYSTEM CONTEXT)
                        - **System Context Diagram** 
                        - **Quick Overview** Explaining business functionalities inferred from code: [This codebase helps with performing these functionalities, in the broader viewt this application belongs to a fire department, What the business uses it for] (Same stuff but categorised and in bullet points)
                        - Bolded line that says "Important: 56 security issues found that may cause business risks - Click for details." and user would be scrolled down to the SECURITY & CODE ANALYSIS section, and the security section would def have BUSINESS RISKS column in the security analysis table.
                        - The business process, step by step (Name changed to All Functionalities, same bullet points as it is)
                        - Who it serves table (As it is, maybe enhance it)
                        - Business capabilities table (As it is. maybe enhance it)
                        - Questions for someone who knows the business BUT THIS TIME USER SHOULD BE ALLOWED TO ENTER INPUT and submit as additional context

                - Architecture Overview (Container diagram)
                        - Interactive Container diagram, entire flow should
                        ve been inferred thoroughly beforehand
                        - Table where business functionalities are mapped with code blocks
======================================================================================

**SECTION 3**

Dummy Report based on my findings:

Report will have left, middle, right section.

Like genius.com, when user click a highlighted lyrics, annoation gets opened on right side. Similarly, we will display evidences on the right side.

All diagrams must have a touch of LLM, should contain a line explaining the element. All tables must have a column which present a similar explanation of what the row means.

```
CODEBASE TITLE
Some bs hardcoded sub-heading like "A complete evidence based analytical overview"
==========

LEFT PANEL
----------
- Understand It
        - Introduction (bullet points, summarise the entire document + major findings w hyperlinks)

        - Business & Functionality Overview
                 - By Business System diagram explaining high level architecture, this should be based on llm inference of what the code actually does
        - Codebase Elaborator
                - A single screen with 2 tabs
                - By callgraph (use the existing diagram but diagramatically from the report)
                - CODEBASE EXPLORER: LLM generated groups first shown in diagram → click group → files/FQCN → click file → code diagram → click function → group > file rectangle > code diagram AND TABLES FOR EXPLANATION
        - Runtime View / MAJOR FLOWS
                - By Endpoints (flow or sequence diagram of sEgress & Ingress user flow diagram, explaining every egress ingress)
                - The runtime view describes concrete behavior and interactions of the system’s building blocks in form of scenarios from the following areas: [important use cases or features: how do building blocks execute them? ] AND [interactions at critical external interfaces: how do building blocks cooperate with users and neighbouring systems? ] AND [operation and administration: launch, start-up, stop ] AND [error and exception scenarios]
        - Risks & Technical Debt (Summarise Code Analysis Findings's content and add a line asking user to redirect user to this section for more details)
        - FAQ - (TASK DRIVEN DOCUMENTATION!!!)

- Code Analysis Findings
        - Test Cases
                - Visuals can remain as it is, implement a download button for RobotFramework based Test-Suites
        - Database Interactions
                - No need to change, section can be left as it is
        - Code Quality:
                - Summary of all sections + LLM findings like:
                - Security findings WITH business risks in a column
                - Performance (RULES MUST BE CLEARLY DEFINED IN PROMPTS)
                - Coding Practices (STATIC + LLM SUGGESTIONS)

Important rules
- Maybe stuff from here can be directly copied as prompts? https://docs.arc42.org/section-1/
- Rules for diagram https://c4model.com/diagrams/checklist
- The focus on explaining the codebase is important
- Progressive disclosure from business → architecture → component → code → evidence

FORGET the stand-in model, this is a dummy report made by claude.

Please thoroughly study the entire site of https://c4model.com/ & https://examples.arc42.org/ & https://medium.com/codex/what-goes-in-a-software-architecture-document-e97d808d5cec and recreate the dummy html report please. Forget the war analyzer, just implement the helpful writing style and visual representation according to our report wherever deemed suitable based on my understanding of these 3 URLs. DO NOT CODE ANYTHING IN THE WAR PLATFORM, LET IT SIT. PLEASE. Just create a pitch perfect dummy html instead of working on the code and then we could simply reverse engineer the prompts and steps.

My main issues at the moment are as follows
- Right panel doesn't close after it has been opened - bug and also 
- Try to understand that you are free to assume the business related stuff completely
- There has got to be a rule like if 350 characters are crossed then paragraph shouldn't be created and bullet points must be used, in table cells, only bullet points should exist
- source-derived / factssettingsfactscapabilities LABELS get pasted in the middle of sentences, we already implemented evidence right panel so no need for these
- WHO asked to add TOC? No one, I don't want a TOC when side-panel TOC is clearly visible
- Collapsed EVIDENCE rows exist everywhere and make no sense given that we have already implemented [showing evidences in right panel]
- The inferred / static label doesn't mean anything to anyone, no one cares
- Introduction > [ The application in one minute ]
        - - should show business summary as well
        - - Should have a glossary row as well, explain quickly what a few terms mean and then show [MORE DETAILS HERE] hyperlink to architecture
        - - This whole sub-section should show details in table, should also include [build, technology, major findings]
        - - Remove [Understand the system | Explore the architecture | Trace an API | Explore the code | View the risks | Find the tests | Find the database interactions | View the security findings | Ask a question]
- Introduction > [The facts behind these sentences]
	- - I truly think that this table should be in the introduction section but with references to different sections of the report
        - - This table could have [question|answer|more details]
- Business & functionality overview > System context
        - - System context diagram is okay but should be for laymans / simple language / analogy, it should've been built using inferrence and the elements also don't have good description. No PEOPLE exist and other elemetns are missing too, C4 Checklist had also been given (https://c4model.com/diagrams/checklist)
        - - Question answered row makes no sense, we should also provide answers and describe the diagram a bit, if it gets better.
- Business & functionality overview > Quick overview & All functionalities
        - - Quick overview has a redundant card explaining [Book inventory management], which should've been explained in so much detail in Introduction's Summary & In A minute subsections
        - - All functionalities' Table has so much useless information. Functionality column should have english. Only these columns should exist: Functionality (eng + endpoint)|Given(Trigger / input)|When(Processing)|Then
        - - Who it serves has a table that marks HTTP clients as the user but maybe it should've been creative like library students / library admin etc? 
        - - Questions for someone who knows the business must be collapsed from start
- Architecture
        - - PLEASE study the c4 diagrams properly, container diagram would've worked so well here, why aren't we just mimicking what's studied in the articles?
        - - Business functionality → code seems a bit week
        - - Ingress and egress: Seems useless and redundant - Maybe the runtime and major flows section can just be moved here directly?
        - - Individual CAMEL ROUTES FLOW DIAGRAM section with bullet points should be added here from the old version of the report, right above the 
        - - Operation & start-up should be moved to Getting Started + FAQ 
- Database interactions
        - - This section should have remained as it is from the very old report, which basically showed the html output of the sqlitedashboard script
- Code quality
        - - Summary section should just display a line graph showing how many issues found for code quality, performance and by unique LLM findings
        - - TOO MUCH STUFF. LLM Findings & Suggestions should be the first section and only m-ention stuff that wasn't find with the static tools        
        - - EVERY SUB-SECTION MUST USE THE SAME EXACT DIAGRAM THEME AS Code quality analysis SECTION
- Security
        - - BUSINESS RISKS: Seems questionably very bleak considering how many code quality related issues are found. I believe that this section should have a prompt like YOU ARE A SENIOR SECURITY ANALYST and it should go through current versions, methodologies, code quality, architecture, everything.
        - - Who can call what and The security position subsections seem hella week
- Coding practices
        - As IT'S ALREADY COVERED, Please remove.

During implementation, Go line by line, one by one from top to bottom like a checklist and don't skip anything please.

I am again going through the arc42 guide and believe we forgot some stuff but this also says https://faq.arc42.org/questions/B-1/ - "Everything you document will potentially require maintenance effort in the future. With every piece of documentation, you’re effectively piling up maintenance debt - and in parallel creating some information value… Please only document things, facts and reasons that you or my stakeholders consider important enough to justify written documentation."

BUT I still think that the ARC42 approach should be followed but maybe the only following stuff should be added as it is:
- Camel routes flow diagram was perfect last time, Who calls who flow diagram was ane xtension of this that included java related classes and methods was also almost there
- Where things are section explained every single file on the basis of directories in collapsed rows, def pretty good
- Main business flows section is PERFECT (our Runtime / MAJOR FLOW section is a blot), Sequence diagram in Main business flows should exist for every egress and ingress PLUS such EXACT or better content should exist

Reverse engineering this exact report, can you please create detailed ARCHIECTURE DECISION RECORDS DOCUMENT for each and every implementation? I have also attached the current prompts config file which has generic prompts that are to be converted for working with a CAMEL-SPECIFIC codebase. I really think the prompt size is an issue. not sure why we have such large prompts as texts considering we also send large code data and other extraction details.

====================================================

Please thoroughly research from scratch, plan and intelligently generate the adr AGAIN for implementing these one by one, top to bottom, I have updated these. You may delete the previous ADRs related to this:

- The business & functinoality overview > elements table has column WHAT IT IS, which should be description
- Sonarqube does not work at all, please show this as warning and i shouldn't have to figure this happened from the report. Maybe the issue was that docker / podman doesn't exist during the ./setup.sh?
- Business rules section seems to be the most useless section. Just have a look...
```
Every rule the code applies today, including the ones it seems to have dropped.
Rule	What happens	Where
If the first list item lacks an accounts key, sets x hea	
    If the first list item lacks an accounts key, sets x header to 0.
    x.java:65-83
If account count is zero, appends a closing bracket to FinalBody; othe	
    If account count is zero, appends a closing bracket to x; otherwise, iterates x to append them.
    x.java:133-150
```
- All functionalities section is laughably small, had just 1 row, maybe it's created on the basis of endpoints? Because this codebase has only one and behind it, complex internal routing is being done 
- Questions for someone who knows the business does not accept inputs but it should
- Should consider that INRGESS in our context is the actual defined endpoint and EGRESS are the internal routings?
- Container diagram does not even connect with the PERSONS and was just slightly different than System Diagram. Maybe we should get a bit more creative with this and System Diagram?
- Component diagram must be replaced with a better version of the kaoto diagram, showcasing everything at camel, bean, caller, calls, etc level. Research this first for kaoto, the component diagram must go show everything at an absolute code level WITH LLM EXPLANATIONS AND GROUPINGS, FOLLOW PROGRESSIVE DISCLOSURE JUST LIKE THE CODEBASE EXPORER DIAGRAM, SHOW GROUPS FIRST AND THEN GO FURTHER INTO THE DETAILS.
- In Camel Routes, no need to differentiate between [Internal route · Camel direct] and [ Camel route ] cards since the former are just children of the latter. Also, the steps should also been explained in english i think. Also the existing horizontal diagram isn't really worth it, maybe the steps should just be visualised as a vertical flow chart?
- Major flows is to be replaced with the app flow diagram in report_v5.html.. report_v2.html > Application flow diagram isn't all that perfect. Concerning thing is that when i ran the latest utility, I had expected the diagrams to appear a bit different but not much changed. We still must integrate it report_v2.html > Application flow diagram place of report.html's > Major Flow diagram but with enhancements. I feel like even now maybe the code-flow isn't being mapped correctly maybe? For example, report_v2.html > Application flow diagram currently shows too many arrows that it gets hard to understand, maybe they should be straightened / zigzagged? Also clicking on all items must show only those flow related to them and grey out unrelated stuff, something already present in the INGRESS items. Speaking of which, INRGESS should become 'discovered endpoints' and EGRESS should become RESPONSE and must also show returnCode kind of stuff along with status codes too. Lastly, a lot of files are still shown which do not connect with the OPEN endpoint flow at all. This diagram should definitely get enhanced further for being more helpful to the user. Note: We only take the diagram and annotations.
- Codebase explorer was the highlight of the report and got praised a lot but just a few things: Groupings make no sense at all (2 bubbles with same path shown), src/main/resources/META-INF/resources had index.html but clicking it just said "Open the file" and right panel said "No evidence is registered for this item." - I don't have any issue if code-block isn't shown but at least an explanation of the file can be done no?! ALSO - HUGE ISSUE: After opening the file, the diagram is supposed to show the c4 code diagram but right now it just shows "OPEN THE FILE" for most files, this isn't good even in the ones it exists in
- Major Flows > Failure flows can be removed. ALSO - can we not have an business based analogical explanation of the flow? Right now it makes no sense
- Remove Operation & start-up, it's silly
- CODE-FLOW MUST BE ALSO CONSIDERED BEFORE CREATING TC SCENARIOS. All 990 test cases got stored as integration.robot TEST SUITES, couldn't we have split them? Also - Remove [What the tests prove]. Also opening TEST CASES BY ENDPOINT rows will show [Where	Kind	Condition	Status	Cases] for some reason.
- Biggest waste of space is the 8 Code quality section, it has 5 tables whose data could've so easily been integrated into a single table. Integrate all tables into a single table with filters and categories, be smart. Performance should have way more rulesets, please study thoroughly online. 
- Any card with 5+ lines must be collapsed from default and should have show more / show less button
- Somehow I feel like the english of the report got worse? Also the user input ai prompt must be considered definitely. The system context diagram called Logging System "ananya, a processor". Not sure why the quality was poor this time.
- Why on earth are we making multiple html reports?! ONCE we have implemented the APP FLOW DIAGRAM from report_v2, discard it's generation for good

CODE FLOW MAJOR ISSUES:
- Report was called better but the understanding of the code flow was still flagged as incorrect
- I was told: When flow is moving across files, maybe we are not taking data found in previous files further with us? If resource calls a url in camel, and that url calls a bean in the code after setting headers then java code adds some conditions, then something then something, all should be considered.
- Biggest critique was that arrows were wrong in the first place, user isn't being shown the exact correct flow 
- Kaoto has been suggested for generating flows and verifying where the gap exists. I've generated the visual and will downloaded it in text form and intend on comparing OUR extracted code-flow with kaoto's, which is absolutely perfect.
- I installed the vs code extension, can I download the generated visualisation but as text? Should i try a different installation method?
- How would i compare it with the code-flow generated by our code? I intend on only asknig qwen3.6 to find the missing gaps in war platofrm's code-flow
- Even TCs would become better if code-flow got fixed and so would so many other sections

==============

Data Flow Diagrams
- Brief: Aims to exlpain a very high level representation of how data moves within a system, starting from the input and ending with the output. 
- Where are they used: AKA System context diagram and are used in software development, system analysis, process improvement, System Architecture Documents, Root Cause Analysis documents and  even businesses, Introduced in 1970.
- Importance: Data flow diagrams are important as they help us:         
        - gain clarity:
        - Analyse systems
        - Get non-technical people on-board
        - Improve processes / Document things better
        - Root cause analysis and bottlenecks 
- Components of DFD:

========================================================


