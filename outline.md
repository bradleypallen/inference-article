# Inference Corporation: From Expert Systems Shells to Customer Support Applications 

## Early years
Inference was originally started as Systems Cognition Corporation by Alexander Jacobson of Hughes Research and Chuck Williams of USC ISI, who teamed up to attempt to tackle the problem of building a usable natural language user interface to relational databases.

### Origins at USC ISI and Hughes Research
Chuck Williams was a young researcher at USC ISI. Alex Jacobson was a senior executive at Hughes Research, with roots in the Caltech community.

### Work on natural language understanding at CDC
In 1979, Jacobson and Williams obtained a contract from CDC to prototype a natural language interface. Work on this project created much of the incentive and many of the technical ideas around expert systems reasoning and knowledge representation embodied in Inference's products.

### Involvement with Wolfram and the development of SMP
As an additional business line, to provide a source of revenue to support the  project, Jacobson worked with Steven Wolfram of Caltech to build and productize a computer algebra system created by Wolfram, called SMP. The relationship was difficult to manage, and SMP would eventually lead Wolfram to establish his own company Mathematica, which carries forward many of the ideas initially build into SMP. The time spent on building a team to support SMP brought many talented technologists to Inference.

### The early development of the expert systems shell
The work on building a natural language understanding system yielded a great deal of effort in building tools. Eventually the focus shifted to building the tools themselves as a initial step to get software products to market. An initial version of this tool where called Axiom, but it would be renamed to the Automated Reasoning Tool (ART).

### Involvement with the founding of Lisp Machines Incorporated
The tools were built on top of Lisp, and the emergence of specialized hardware and workstation environments for Lisp application development was seen as a way to dramatically improve developer productivity. Jacobson and Williams got involved with the MIT-based efforts in building Lisp machines, and were directly involved in the founding of Lisp Machines Incorporated (LMI), one of the two startups out of MIT to deliver Lisp machines to the market.

## The "Gang of Four" and the dawn of the expert systems market
Motivated by governmental and defense initiatives in the industrialization of artificial intelligence, interest in the venture capital community in the creation of startups to deliver products in support of those initiatives, and the glamor associated with the "thinking machine" trope, a number of expert systems companies formed around the period from 1982 to 1985. Inference was one of the initial "Gang of Four" venture-funded expert systems startups, joined by Intelligenetics, Teknowledge and Carnegie Group.

### Venture funding by Venrock
In 1983, Alex Jacobson managed to close an investment round with Venrock, with Tony Sun of Venrock taking a seat on the board. This was the initial capital infusion that allowed Inference to begin to build the team that would deliver ART to market. Chuck Williams and his team demonstrated Axiom, an initial version of a expert systems shell, and the first to incorporate an assumption-based truth maintenance system (ATMS), that together with a forward- and backwards-chaining inference engine supported the ability to do hypothetical reasoning. Recruiting of a technology team to be led by Williams began in earnest, but was challenging due to the scarcity of developers familiar with the key technologies.

### Growth of the technical team and the launch of the Automated Reasoning Tool
A team of expert systems technologists (Brad Allen, Mark Wright, and Paul Haley) were recruited from Carnegie Mellon and joined the team in Los Angeles starting in February 1984, with the goal of being able to launch a ART at the AAAI84 Conference in Austin, Texas in August. Working on a set of Symbolics lisp machines, the team made substantial architectural changes and innovations while creating one of the first hybrid knowledge engineering environments (combining rules, structured objects, facts and truth maintenance) in time for the conference debut.

## Applications successes and rapid growth
The interest by the American government and military in expert systems and artifical intelligence technologies, prompted by the ongoing Cold War and the perception of a economic challenge from Japan, led to a period of significant demand for expert systems tools and consulting services. The success of the company during this period was accompanied by growth in annual revenue to approximately $10 million. Williams established an advisory board composed of a number of leaders in the AI community, including Doug Lenat, John McCarthy, and Gerry Sussman.

### Early adoption of expert systems technologies
During the period from 1984 to 1986, Inference engaged with a number of early adopters to build expert systems using ART. A professional services organization under Phil Klahr took shape, and several of the systems built by this team would be recognized as early successes in the commercial application of expert systems.

#### NASA
The NAVEX system, built jointly with technologists at the Mission Planning and Analysis Division at NASA's Johnson Space Center, was a rules-based expert system that automated the decision of when to restart the extended Kalman Filter model used for real-time prediction of Space Shuttle trajectories during launch.

#### American Express
The Authorizer's Assistant, built for American Express, automated the decision process associated with the real-time determination of whether or not to approve a charge on a customer's credit card.

#### American Airlines
An Inference team worked closely with American Airlines to develop a knowledge-based approach to aircraft flight scheduling.

### Investment by Ford Motor Corporation
In 1986, Ford determined that expert systems technology was going to be an important part of its future products, and invested $6 million in Inference. At the urging of the Inference board, Ted Marr assumed the position of CEO, and Alex Jacobson moved into the position of Chairman.

## The decline of the expert systems market and the onset of the "AI winter"
By the start of the nineteen-nineties, it began to become clear that the initial burst of adoption and investment in expert systems technology, driven largely by the US military, was commerically unsustainable. The original "Gang of Four" companies began to be disrupted by a newer generation of expert systems shell vendors delivering solutions natively built for either the Intel/Microsoft or Apple platforms, at a substantially lower price point that the original generation of expert systems shells.

### Barriers to adoption by mainstream enterprises
Barriers to adoption in mainstream commercial enterprises included the cost and effort involved in integrating special hardware into traditional mainframe business systems, the cost and scarcity of developers capable of using expert systems technology effectively, and the brittle nature of even the most successful applications.

### The purchase of Expertech and growth of Inference Europe
In 1987, Inference purchased Expertech, to give it a foothold in the European market and rule-based expert systems shell that was simpler to use and deploy than ART. Peter Price and his team joined the company as a result, and Inference began to actively expand in the European market.

### The development of CLIPS, ART-Enterprise and ART-IM
Convinced of the utility of hybrid expert systems languages and shells like ART, but frustrated by the high costs of the commercial software licenses provided by the expert systems vendors and the specialized Lisp machines needed to use them, a team at NASA Johnson built an expert systems language called CLIPS using the C programming language, adopting much of the syntax and functionality of ART, and releasing it as an early example of open source software. Rather than fight this development as an act of intellectual property infringement, Inference instead embraced CLIPS, modified and rebranded it as ART-IM. The more fully-featured LISP-based version of ART was reengineered to make it work on Unix workstations in additional to the range of LISP machines to which it was initially limited, and rebranded as ART-Enterprise. This gave the professional services team the ability to deploy expert systems on Unix workstations and Intel-based personal computers, which were beginning to emerge into broader use in mainstream commercial enterprises. Ted Marr left the company, and the board brought in Peter Tierney, an experienced senior marketing executive from Oracle Corporation, to lead the company at this time.

## Pivoting to the customer support market
One application area where expert systems had shown promise was in providing decision-making support to customer service representatives. The Authorizer's Assistant was an example of that type of application. However, the issue of the scarcity of knowledge engineers and the difficult of the knowledge acquisition process worked againset rapid adoption. Inderence made efforts to develop a simple rules-based expert system shell for customer support built on ART-im for the personal computer, but then began to focus on case-based reasoning as a way to reduce the costs of both knowledge engineering and knowledge acquisition.

### The development of CBR Express
A simple application for the Intel/Windows platform was written that provided a way for customer service representatives to create and retrieve product problem / customer solution pairs in the context of real-time customer support, which at that time was typically implemented using a call center.

### Traction in the emerging customer relationship management market
The customer relationship management market began to take shape in the early nineties, and companies such as Clarify and Vantive began to offer broader solutions that those provided by tools like CBR Express.

#### Compaq
Compaq used CBR Express to develop a help desk assistant for its PC manufacturing business.

#### GTE
GTE used CBR Express to create a help desk application for its phone service customer support teams.

#### Microsoft and Project Cairo
Work was done under contract to Microsoft to begin to incorporate information retrieval capabilities rooted in CBR Express development into the in-development Cairo version of the Windows NT product. Inference consulants worked closely with Cairo developers for two years, at the end of which an exclusive license was sold to Microsoft for the use of the retrieval technology in future versions of Windows operating systems, but with the failure of the Cairo project, the technology never saw public distribution.

### Spinning out Brightware and Limbex
As the CBR Express revenue grew and began to outpace the revenue coming in from the traditional expert systems shell market, it became clear to management and the board that there was an window during which to take the company public, and that would necessitate focusing on the CRM market, and abandoning the original expert systems shell market. Chuck Williams, however, felt strongly that there was still an significant opportunity with the original business model, and ART-Enterprise and a portion of the development, sales and marketing teams where spun out as new company called Brightware. At roughly the same time, Alex Jacobson and Brad Allen spun out a new company called Limbex, funded by Quarterdeck Corporation and with equity position being held by both Quarterdeck and Inference, using concepts emerging from the development of the Project Cairo effort and CBR Express to deliver a search assistant for the emerging consumer Internet.

## IPO and acquisition by eGain
Inference succesfully went public in 1996. Within a few years, with heavy competition from other CRM vendors with more fully-realized products, growth stagnated again. The company was sold to eGain, another CRM vendor, in 2000.

## Retrospective assessment
Inference unfolded over a twenty year period that saw a complete boom-and-bust cycle in the artificial intelligence applications market. The same period saw the emergence of the PC and Unix workstation/server platforms, the Microsoft Windows near-monopoly, and the birth of the Web. After the initial optimism over expert systems technology faded, the company successfully pivoted into providing intelligent assistance in the customer relationship management market, where it experienced a second brief period of growth before its ultimate sale to eGain.

### The role of the expert systems company in the evolution of artificial intelligence
The experience of the expert systems companies during the period from 1985 to 1990 showed that initial enthusiasm from early adopters did not establish an indubitable value for the technology in the broader enterprise market. Those companies that managed to take their original products and find an application area where value was demonstrable survived, and with the customer service market Inference was one such company. This can be viewed as an example of what today is addressed as achieving the correct product/market fit.

Expert systems failed to usher in a golden era of intelligent assistants working hand in hand with people. One cause was the barrier of adoption posed by the tremendous gulf between the Lisp machine and the mainframe computing platforms, but over the nineties that issue was addressed with the emergence of expert system shells written for the PC/Windows and Web platforms. Unfortunately, the expert systems approach to the knowledge engineering of decision making processes turned out to be brittle and labor-intensive to grow and support a wide range of use cases.

However, the emergence in the 2010s of scalable and productionized machine learning approaches to the creation and maintenance of predictive models and object recognition systems began  to yield significant successes in avoiding the knowledge engineering bottleneck, but for applications closer to acts of perception, rather than human judgement. In addition, the requirement for vast amounts of clean, curated data necessary to build such applications has shifted the costs and risks in building intelligent assistants from knowledge engineers to data engineers. There is currently debate about the degree to which purely deep-learning based applications need some degree of task-specific data- and knowledge-engineering to avoid the brittleness of the earlier expert systems era.

## Acknowledgements
* _A list of collaborators, which may be large if this becomes a crowd-sourced narrative._
* _Chuck Williams' inspiration, technical leadership and legacy after his untimely death should be specifically called out._

## References
_Cited sources to include:_
* _Trade publications (AI Magazine, CACM, etc.)_
* _CLIPS Manual_
* _IAAI Proceedings_
* _Nii/Fiegenbaum/McCorduck books (The Fifth Generation, The Rise of the Expert Company, etc.) and other materials_
* _Discussions with and materials from Inference alumni, especially that pertains to the financial performance, structure, and owenership of the company_
* _Business media (Forbes, NYT, etc.)_
