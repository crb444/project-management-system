
## Project Management System

### Project Background
<p>The University of Melbourne runs software engineering projects every year, which are allocated to subjects in the CIS Department. These projects are
sourced either from internal staff or external clients, with the primary aim being to provide students with experience building a sizeable piece of
software solving a real-life business problem. Thus, these projects are never business critical. Projects are allocated to different subjects depending
on the nature of the project, and there can be more than one student team working simultaneously on a particular project. These teams range in size:
they can be as small as four students but can go up to twelve. Each team will also be assigned a supervisor to oversee the project progress and liase
with the client if necessary. When successful, these projects are deployed and actively used by the clients. </p>
<p>
Currently, the process of receiving, evaluating and managing university projects is adhoc, manual and uses several data sources and tools. As the
entire project management involves several aspects and there is no central tool or repository to manage these processes, each subject coordinator
has their own process.
</p>
<p>
The processes are the following:
</p>
<ul>
  <li>Submission of Proposals</li>
  <ul><li>Clients currently hear about the university's project by word-of-mouth and submits it either using an online Microsoft form or via
email. At the beginning of the year, subject coordinators will meet to discuss the received proposals and allocate the accepted ones
to a subject. Rejected proposals will be notified via email by the subject coordinator who received it. Accepted project proposals will
be followed-up either by the subject coordinator who received it or the subject coordinator who is in now in charge of that project.
Ongoing communication after that relies on obtaining updated information from several emails and spreadsheets (possibly from
other subject coordinators). </li></ul>
<li>
Management of Projects
<ul><li>
This would involve supervisors and coordinators of a particular subject meeting to receive feedback on the groups. Although
meeting notes were recorded, there is no central repository to track how projects were going and to also determine the reasons for
their failure and success.</li></ul>
<li>
Exploring past proposals and projects
<ul><li>
Currently, a subject coordinator who is interested in getting metrics about his subject will have to use his own tracking spreadsheet
to do so.
</ul></li>
<li>
Communication
<ul><li>
Mainly through email, but there were usually more than one channel of communication between the supervisors/coordinators and
their clients. Additionally, When there is an upcoming event, the administrators would approach subject coordinators for a list of
clients they would like to invite. More often than not, subject coordinators would have to trawl through their email inboxes to find
clients they remember having a good relationship with, compile their contact details into a spreadsheet and send them to the
administrator via email.
</li></ul>
</ul>  

### Proposed Solution - The Project Management System 

<p>
This system serves as a central repository for the management of the project pipeline from proposal to product deployment. The key features of the
application include: </p>
<ul>
<li>Receiving and evaluating proposals</li>
<li>managing projects and student teams</li>
<li>communicating with clients and student teams</li>
<li>managing client profiles</li>
<li>querying data of past proposals and projects </li>
</ul>

### Key Features of the System 

<ul>
<li>Part 1: Recieving Proposals 
<ul>
<li>Client can reach external-facing landing page for the platform and read what the University offers. From there, they will able to submit a proposal which follows a set of guidelines that they can clearly see</li></ul></li>
<li>Part 2: Evaluating Proposals
<ul>
<li>
Coordinators/supervisors can view submitted proposals and be able to modify them before evaluating. They can view the answers from the questionnaire, client details and the organisation that they are apart of. Upon evaluating, the coordinator/supervisor is invited to indicate their reason for the decision. 
</li>
</ul>
</li>
<li>Part 3: Managing Projects</li>
<ul><li>
All accepted proposals become a project and appear on the 'View projects' tab. They are categorised either: new, in progress or complete. Users can assign a supervisor to project and can create multiple student teams. Users can also update the teams page by updating artefact links (ie. links to conlfuence, dropbox, google drive etc), metrics about the project (ie. currently deployed or not) and information about the technology used </li></ul>
<li>Part 4: Communicating with student teams and clients </li>
<ul><li>Users can email student teams and clients from the platform itself. They also have the ability to create and utilise their own templates</li></ul>
<li>Part 5: Managing client profiles</li>
<ul><li>Users have the ability to modify client profiles, which are created automatically from the initial proposal submission. Client profile's also contain notes, which are notes that a user can add manually and also notes that summarise all outgoing communications in the form of emails</ul></li>
<li>Part 6: Querying data for generating reports</li>
<ul><li>Users can query all projects/proposals in the system through various filters and metrics</li></ul>
</ul>

### Technology utilised

<ul>
  <li>React.js</li>
  <li>Node.js</li>
  <li>MongoDB</li>
  <li>Docker</li>
  </ul>
  
  ### Screenshots 
  
  
  ![alt text](https://github.com/crb444/projects/blob/master/Project%20Management%20System/imgs/1.png?raw=true)
  
  >Proposal submission page
  
  ![alt text](https://github.com/crb444/projects/blob/master/Project%20Management%20System/imgs/2.png?raw=true)
    
  >View Proposals page 
    
    
   ![alt text](https://github.com/crb444/projects/blob/master/Project%20Management%20System/imgs/3.png?raw=true)
    
  >View Proposal Details
    
    
   ![alt text](https://github.com/crb444/projects/blob/master/Project%20Management%20System/imgs/4.png?raw=true)
    
  >View Project Details
    
    
   ![alt text](https://github.com/crb444/projects/blob/master/Project%20Management%20System/imgs/5.png?raw=true)
    
  >Edit Student Team Details
