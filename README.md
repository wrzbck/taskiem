# Taskiem
### Simple way to create, estimate and manage product / project backlog.

# Motivation
Every time I started a new product, project, or program I faced the same dilemma: I had everything (well... almost) in my head and I needed a tool that would let me work on the spec and the project plan at the same time.  

- text editors are great for describing features but useless for project management
- spreadsheets are great for estimating time, costs, risks, etc., but not so convenient for describing features... 
- project management tools... don't even get me started...  

I decided to create the tool… just for me.

# Download
There is a binary in the release section, available for free.
Direct link: https://github.com/wrzbck/taskiem/releases/tag/version_0.2

*Taskiem author shall not be liable to Taskiem users for any lost profits, lost revenues or opportunities, downtime, or any consequential damages or costs, resulting from using Taskiem.*

# Run
1. Execute 'java -jar taskiem-0.2.jar --taskiem.user.email=... --taskiem.user.password=...' in commandline (java 17 required)
2. Open a web browser and type 'localhost:8085' in address bar

# How it works

- Manage backlog items (almost) as easy as using text documents. 
- Estimate the time, get to the burndown, and the project finish. 
- Group backlog items "from different perspectives" or get the Gantt chart. 
- Convert documents, ie Google Docs to tasks and push them to your task management tool.
- Instant time and cost estimates without the hassle of project management tools.
- Select one of the three views: tree, grid, or board.
- Customize visible properties, size, colors, and more.
- Do not be tied to one and only tool. Ultrasimple import/export to CSV, markdown, or document.
- And more ...

# Techstack
- Java 17
- Spring Boot
- Vaadin
- h2database

# Issues / Bugs
Yes, probably many.

# Security concerns
1. No, it is not a malware.
2. It has not been tested extensively.

# Roadmap
* Login using password [done!]
* Resources rules: create team members along with their availability, velocity and cost. Auto assign rules. [done!]
* Burndown analysis.
* Multiuser. 
* Remote estimation: ask team members (separately) to estimate tasks... offline simulation of planing poker or Whiteband delphi.
