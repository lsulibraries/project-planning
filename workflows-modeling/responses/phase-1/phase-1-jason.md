# The system

Needed to:
- impose some order on the chaos of a group
- enable efficient work
- direct/inform communication activities
- facilitate appropriate information sharing

## Summary

The software system should be more powerful than Trello, but not a mystery like Jira (so far). Power-ups include richer task metadata, intuitive linking, search that approaches a query language to enable rich views of the contents of the system.

Regarding the human system, I describe a front desk role that mediates communication between us and them. There is also a description of project-specific planning activities after the style of the Broadway project, which I cite a lot lately.

## The software system(s)

### Tasks
- **Task breakdown**: You should be able to take a big idea and break it down, as in `big idea` `->` `feature chunk` `->` `bite-sized task` but let the parts remain interlinked.
- **Arbitrary linkage**: Likewise, you should be able to associate arbitrary tasks by creating links between theme.
- **Task interdependency**: There ought to be a way to represent task dependencies. X must finish before Y can start, etc.

### Human interface
- **Multiple assignment**: It should be possible to assign a work unit to more than one person.

### Communication
- The system should **facilitate *and* capture communication** for later reference, like Trello's threaded comments are timestamped, attributed, permanent-ish.
- It should support **at least two tiers** (public/internal) of access. In researching an issue, for example, I should be able to @ someone using informal language knowing that the exchange will be captured for future reference but that it need not be part of the correspondence with our 'customer'.

### Search & query
- Full-text search
- Metadata should be sufficiently rich, yet regular, so as to support **querying**.
  - `All 'completed' tasks` is a query with nominal utility,
  - better if you can get `all tasks 'assigned to me' and 'assigned to Will' that are 'incomplete', having priority X, and associated with a project Y`, or
  - what are the `tasks currently in progress, grouped by assignee`

### Documentation & Future reference

The information captured in the 'operations system' (most of what is described above) should be available in the future, for reference.

There should be searchable electronic documentation that is available on/off campus, on mobile, and that supports access tiers.

---

## The people system

### Front desk (input)
A [Janus](https://en.wikipedia.org/wiki/Janus)-like role positioned on the border between 'the team' and 'the outside world'.
This person is skilled and experienced with professional communication; their outward communication protects the reputation of 'the team', the libraries, the institution...

This role does not assign work or solve problems, rather, this role mediates dialog between domain experts on 'the team' and the originators of queries, requests, trouble reports in the outside world.

These queries, requests, trouble reports become 'assigned work items' through a planning and prioritization process.

### New project/initiative (input)
This is different from handling support tickets (immediately above). Presumably, there is a clear leader with a clear vision that will define nearly everything about the project.

### Planning and prioritization process

Emergency work items are assigned immediately by someone with decision authority for the appropriate scope.

Non-emergency work items are enqueued for consideration at the next appropriate planning session.

#### Terms
##### "Decision authority"
Self-explanatory, right ? Maybe:

For a given scope, the person with decision authority will be one of
- scope owner,
- domain expert
- and perhaps in the absence of those, highest workday org chart person.

NB: Perhaps also similar to the 'A' in [RACI](https://www.projectsmart.co.uk/how-to-do-raci-charting-and-analysis.php) in [Mike's](https://gist.github.com/myqua/b2f3fe77ba6bc5c67fa8b1105dc11790)

##### "Scopes"
In this department, there are many scopes. Generically, a scope could be a domain, project, or product. Specifically, LDL is a scope; Broadway; compound theme in LDL is another, much smaller scope, metadata guidelines is a wide scope that overlaps the scopes of many projects and that contains many sub-scopes.

##### "Appropriate planning session"

For a given scope, there should be an appropriate planning process.
- whiteboard list
- morning huddle
- structured planning session

### Prioritization

Roles with 'decision authority' in a scope should prioritize tasks. Inter-scope priority conflicts should be resolved at the next higher/wider scope that contains all of those in conflict.
