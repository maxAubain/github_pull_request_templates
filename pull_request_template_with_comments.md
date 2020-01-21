[comments]: # "Pull Request documentation can be a self-enclosed document
to provide all the necessary information for a reviewer to undertand the 
merged code in its entirety.  This can be of use for many roles, such as 
developers new to the project, partner groups with parallel requirements, 
project managers to evaluate quality and progress, and product owners to 
understand specific functionality. This type of documentation can make a 
code review seemless and a good use of developers' time."

[comment]: # "Remove this Title section and insert Title information in 
PR Title form field above"
# Title
[{Initiative}] [{Epic}] [{Type}] [{User Story ref num}.{version}] [{'merge into' branch}]

[comments]: # "The Title can hold small identifiers that provide context
to the PR in relation to the application as a whole and that allow simple 
comparison to other PRs in the Pull Request tab. The identifiers become 
more useful if consistent across PRs and can serve as search terms. custom
'label' tags can also be added to PR with Github options and will show next 
to the Title."

## Owners
- Role: Name, contact information...

[comments]: # "The Owners list can include anyone who is involved with the PR.
Encouraging leaving name and contact info upfront encourages communication
with those who have done the heavy lifting and foster personal ownership of
the entire feature. The contact information can be, for example, an email 
address, or a github username tag. Roles can be 'developer', 'reviewer', 
'designer', etc."

## Summary
User Story Ref. Num.: [{user story ref num}]
```
{User story}
```
Implementation of version: [{{User Story ref num}.{version}}]
- [Sprint-plan / Kanban-design link...]()
- [Link to related PR...]()
- Summary description 1...

[comments]: # "The Summary can include the bulk of the description of the 
coding content and functionality.  This can include the User Story, 
descriptions on how the User Story was implemented in practice, and links 
to other project tracker tools, such as an Agile Scrum sprint plan or an 
Agile Kanban board item."

## Libraries / Dependencies / Frameworks Modified
- [ADD / REMOVE / UPDATE] {Lib name} : {Lib function} : {Reason for change}

[comments]: # "Listing changes in dependency or library can contextualize the 
use or removal of helper methods, or aid in tracking down an unexpected bug 
concurrent with an update."

## Challenges and Solutions
**{Category of development} (e.g. CSS, DB, etc.)**
- **Challenge 1**: ... **Solution 1**: ...

[comments]: # "Developers can directly benefit from the debugging processes 
of others, both in learning new unblocking flows and in understanding the 
nuances of the subject matter. Listing challenges in PRs can also be used 
to justify departures from schedule and be useful in cataloging items for later 
retrospectives."

## User Interface
- UI update description 1 {screenshot image}...

[comments]: # "A picture speaks one thousand words.  Screenshots of changes 
in UI can efficiently explain and document the progress made on the front end."

## References
- [Reference link 1...]()

[comments]: # "Putting external links in-line is often more useful than in 
a separate section, but it can be easy to forget to use reference links 
altogether when using new documentation.  The References section can serve 
as a reminder to link to supporting docs, or be an all-in-one location for 
useful links."

## Closing Comments
- Comment 1...

[comments]: # "Sometimes something needs to be said but does not fit into 
any other category. Those comments can be left here."

## Checklist
**Before Merge**
- [ ] Merge latest upstream remote.
- [ ] Commit history is clean.
- [ ] Code compiles / passes checks.
- [ ] Local and global tests pass.
- [ ] Code review.

**After Merge**
- [ ] Pull merged-into upstream branch to local branch.
- [ ] Delete merged-from local and remote branch.
- [ ] Verify deployment and make new PR for unforeseen bugs.
- [ ] Update project board and leave comments.

[comments]: # "A checklist can be a low investment tool to prevent simple,
but sometimes, costly mistakes."