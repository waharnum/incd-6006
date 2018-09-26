*The below are my outline notes to myself for the class. We'll see how much they are actually adhered to.*

# Towards a Theory Approaching Towards a Theory of Inclusive Systems Design

- About the title: https://scholar.google.ca/scholar?as_sdt=1,5&q=%22towards+a+theory%22&hl=en&as_vis=1 ("about 225,000 results")
- In my opinion, people like to compose "Towards a Theory of..." papers or presentations when they have thoughts, but not necessarily a central thesis; I am so far from any kind of central thesis that I have titled this appropriately

## 6:30 - 7:15: Introductions & Framing

### Opening Questions To Consider

- what would be some characteristics of a system capable of achieving one-size-fits-one for everyone?
- what attitudes, processes and tools would we need to imagine, design, build and maintain such a system?
- how large are the gaps between what we need and the typical attitudes, processes and tools we experience in systems design?
- what directions for change would we need to see in attitudes, processes and tools to reduce those gaps?

### Who Am I?

- I'm Alan Harnum
- I've worked at the Inclusive Design Research Centre as a senior developer since mid-2015
- Prior to that, I worked for Toronto Public Library for a decade; in the first half of my time there I was a public service librarian in various forms (I have a master's degree in library and information science), in the second half of my time there I was the senior developer on the library's web services team
- I've got a longstanding if not continuous involvement with Jutta and the IDRC, as I worked with people from the research group before in 2002-2004 as a student software developer
- I've been a professional software developer since the early 2000s (by "professional" here I mean that was the first time someone gave me money to build a website for them, as software developers do not undergo formal licensing or credentialing)
- alongside the incredibly rapid pace of development in the modern field of systems and software design tools and processes, I am interested in the historical roots of the field, and in the lessons people concerned with the design of software systems can learn from an examination of that history

### Who Are You?

- please tell me a little about yourselves
- your name and your experiences with systems design? (it's OK if it is "none"!) - this could include (but is far from limited to):
    - building a website or working with someone building it for you
    - working as a software developer, systems administrator, or similar (you have experience directly implementing software-based systems)
    - working as a designer, researcher, business analyst or project manager on a software project (you have experience working adjacent to those directly implementing software systems)
    - being part of a requirements workshop, product development workshop, user testing exercise or similar (you have experience providing feedback about the design of software systems)

### What Do We Talk About When We Talk About Systems Design?

- I am specifically thinking about software systems, because this is the primary domain of my experience     
- of course, software systems intersect in complex ways with other kinds of non-software systems, and general systems theory and thinking are useful and necessary in thinking about the topic holistically    
- I will try to focus my remarks on processes and tools as they are talked about in the software development world - how is the work to imagine, design, build and maintain systems done? How do you look at these things through an inclusive design lens? How, as Jutta put it to me, can you achieve one-size-fits-one for everyone in an integrated fashion when designing a system?
- how I think about one-size-fits-one when thinking about system design
    - this is a guiding aspirational and longitudinal goal of a system design
    - no system can be designed up front and then delivered to accommodate all possible future uses and needs, even for a very limited audience - believing that through sufficient up-front analysis we can deliver a fully satisfactory system that then only needs to be "maintained" going forward is one of the hallmarks of failed system design efforts
    - rather, we need to have, building on the three dimensions of inclusive design:
        - mindsets and goals as systems designers that recognize diversity and uniqueness - part of this, critical for systems designers, is personal humility and recognition of the limitations of one's own experiences, and respect for the experiences of others
        - inclusive processes and tools that support the ongoing visibility, refinement, alteration, extension and change of software systems
        - consideration of the broader beneficial impact (and care for the potential broader detrimental impact) of our work
    - therefore, it's important for inclusive design to supplement the common and sometimes useful manufacturing/engineering-oriented language of systems design ("product", "scope", "build", "project", etc) with language that conceptualizes software systems as:
        - evolving and organic, capable of exhibiting unexpected behaviour
        - amenable to and expected to change as we learn more about the domain
        - interacting with and connected to other software and non-software systems

## 7:15 - 8:15: Inclusive Processes  

- Conway's Law: "organizations which design systems... are constrained to produce designs which are copies of the communication structures of these organizations" (1967)
    - http://www.melconway.com/Home/Conways_Law.html (one neat thing about a young field is many of the people who coined foundational ideas are still alive, and even have their own websites)
    - updated for 2018: "those who design systems are constrained to produce designs which are copies of  their communication structures"
    - process matters, as does team composition; diverse teams bring diverse insights into the necessity and importance of considerations
- an incredibly brief and personally biased history of thinking about system design / software development methodologies:
    - software system design emerges as a distinct discipline in the 1960s; its tools, thinkers and private and public-sector drivers predominantly originates in North America, in the Anglosphere, and in Western Europe
    - much of the thinking about processes, tools and "best practices" emerges from applied science disciplines with strong historical connection to both the military-industrial complex and the managerial class
        - software-based automation is seen, among other perspectives, as a means of reducing the power of organized labour in manufacturing (see David F. Noble's FORCES OF PRODUCTION on this, among others)
        - it is also extremely important to the development of modern weapon systems, especially in the Cold War era
    - we still live in the echo and shadow of these times   
        - "the past is not dead. it's not even past" (Faulkner)
    - here is an infographic laying out a general history of:
 https://intetics.com/blog/a-brief-history-of-software-development-methodologies
        - large version: https://intetics.com/wp-content/uploads/2018/05/A-brief-History-of-Software-Development-methodologies.png
- in general, the predominant ideology of software development follows the conceptual theorizing of work in North America from a manufacturing-based economy to an information/service-based economy, with the additional meta issue that software systems both participate in and enable the information economy
    - so we see a pattern of development from manufacturing-oriented command-and-control processes (computers, like industrial machinery, are big and expensive! we need lots of processes, layers and control around them, and "experts" supervising the "workers")...
    - to ideologies of "empowered" workers and teams - speed, agility, efficiency! computers are cheap and ubiquitous! people are expensive! we can use computers to replace people!
    - as with anything, there is a distinction to be made between how things actually work, and how people in charge talk about how they work - many organizations remain hierarchical and siloed in nature, as do their system design processes, but because "hierarchical" and "siloed" are bad words in modern organizational discourse, everyone is agile, collaborative, etc
- living in the post-Agile world, scaling processes, and working in the open
    - scaling any process is hard - command-and-control organizations (like the military organizations and large corporations who formulated much of what was considered "best practice" in software development in the late 1960s) try to achieve scaling by enormous investment of money and people in compliance through measures including rules, lines of approval, acculturation, self-management and punishment
    - much of the enthusiasm for "Agile" methods is not because of their promise of more humane and collaborative systems development, but because they are sold by theorists and consultants as a means of reducing the expense and overhead necessary to exert control - "the team will manage itself!" (but still produce the outcome management wants)
    - why the concern for scaling processes? like any conversation about "scaling", it is important to excavate the values and assumptions behind this concern - digging in will often turn out to be about concerns for efficiency and a one-size-fits-all process
    - the point of focus should not be on finding a single process that works for every project and every team

## 8:15 - 8:30: Break

## 8:30 - 9:30: Inclusive Tools

- "We shape our tools and, thereafter, our tools shape us." (John Culkin, 1967; often mistakenly attributed to McLuhan)
- open source software - the good, the bad and the ugly
    - from "free software" to "open source"
        - [Why Open Source misses the point of free software"](https://www.gnu.org/philosophy/open-source-misses-the-point.en.html) (Richard Stallman)
- how tools encode and model values    
    - "Programming languages teach you not to want what they don't provide." (Paul Graham)
    - modern programming languages can have a lot of similarities in broad strokes, but a great deal of variance in the things that they consider "important"
        - the honest answer to "what is the best programming language?" is, without exception, "it depends on your context"
        - successful and useful systems have been implemented in a wide variety of general-purpose programming languages
        - some languages have important characteristics for uses like safety-critical systems
        - especially in the open source era, the ecosystem around a language (available frameworks, availability of programmers, quality of documentation and community) are also extremely important
    - database design considerations
        - "any classification scheme, and especially a formal one, will inevitably 'do violence' to its subject... any act of classification fails to do justice to at least some dimensions of that which is classified, [which can] have serious ethical, economic, political and other consequences" (Brian Cantwell Smith)
  - centralized vs. distributed systems
  - scarcity model vs. abundance model
- how tools and processes impact one another    
    - the limits of the tools place limits on the process
    - tools promote, restrict, impede, forbid, ignore certain models of thinking and doing
      - tools must be used with consciousness and awareness of their strengths and limitations
