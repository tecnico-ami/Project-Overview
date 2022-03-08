Instituto Superior Técnico, Universidade de Lisboa

**Ambient Intelligence**

# Project Overview

This document describes the organization of the project for the Ambient Intelligence / Ambientes Inteligentes (AmI) course.

The document concludes with a calendar containing all the deadlines.

For any questions regarding this document, please contact:  
[meic-ami@disciplinas.tecnico.ulisboa.pt](mailto:meic-ami@disciplinas.tecnico.ulisboa.pt)

# 1. Introduction

The AmI (Ambient Intelligence) course requires a practical project dealing with so called "smart" technologies.  
The whole process is organized in 10 sequential stages:

| **Stage**                                                       |
| ----------------------------------------------------------------|
| [1. Assemble team](#21-assemble-team)                           |
| [2. Pick topic](#22-pick-topic)                                 |
| [3. Write proposal](#23-write-proposal)                         |
| [4. Await approval](#24-await-approval)                         |
| [5. Develop project](#25-develop-project)                       |
| [6. Prepare demonstration](#26-prepare-demonstration)           |
| [7. Write report](#27-write-report)                             |
| [8. Submit code and report](#28-submit-code-and-report)         |
| [9. Check presentation session](#29-check-presentation-session) |
| [10. Present and defend](#210-present-and-defend)               |  

<br />

# 2. Stages

Each stage is described in the following sections.

## 2.1. Assemble team

Assemble a team of 3 students, committed to work together.  
Inform the lab professor of the group members.

## 2.2. Pick topic

The topics for the project are described in another document, which will be posted on the web site.

Read the scenarios descriptions and, as a group, sort the topics by preference for doing your work.
Apply for a topic when the selection page opens.
Each group should be represented by one student only.

In the selection form, identify your group as `CXX`, where `C` is replaced by A(lameda) or T(aguspark) and `XX` is replaced by the two digits of your group number, as assigned by Fénix.
For example, group 22 of Taguspark is T22 and group 7 of Alameda is A07.

Also in the form, sort all the topics by order of preference.
Number 1 will be your most preferred topic.

There are limited vacancies per project topic and slots will be assigned on a _first-come-first-served_ basis.

IMPORTANT: check the deadlines table for the topic selection opening and closing dates.

The official topic selection list will be posted after the process is concluded, to confirm the topic assigned to each group.

## 2.3. Write proposal

After having a topic assigned, your group should prepare a proposal document.
The project proposal should describe the problem and the proposed solution.

Please bring a draft of the proposal to your lab session to present it and receive feedback.  
Groups without any member present in person on that week should schedule a teleconference with the lab professor.

IMPORTANT: the proposal document must be submitted on that same week, on the day following the lab session.

### 2.3.1. Technical requirements

The planned project will need to have, _at least_:

- sensors;
- actuators;
- network communication.

### 2.3.2. Document requirements

- PDF format;
- Mandatory file name `CXX_WWW_HHMM_L_proposal.pdf` 
(where `C` is A for Alameda, T for Tagus, `XX` is the Fenix group number with two digits, `WWW` is the weekday of the lab shift – Mon, Tue, Wed, Thu, Fri – `HHMM` is the time – Hours and Minutes – and `L` is the lab room number);
- Report cover: Project title. Headed by course name, group campus, group number.
In the next row: group members sorted by ascending student number.
For each student, include the number, name and a professional photo.
All photos should be framed so that the faces are approximately of the same size;
- Report body: The font should be no smaller than 11pt, with standard line and character spacing;
- Limit 5 pages (excluding cover);
- Pages should be numbered (preferably with a label like `Page X of Y`);
- The use of diagrams (such as UML or SysML) is recommended for clear and concise communication.

### 2.3.4. Document structure (mandatory)

1. Problem  
_Given the chosen scenario, what is the problem being solved?_  
Use around 200 words.  
  1.1. Assumptions  
  _Which conditions are assumed to be true for the solution to operate as intended?_  
  1.2. Requirements  
  _Which requirements were identified for the solution?_  
  Present as a list.  
2. Proposed solution  
  2.1. Overview  
  Diagram and explanation with at most 200 words.  
  2.2 Platform  
  Identify the main development platform (e.g. Arduino IDE, Android Studio, etc.)
  2.3. Functionalities to develop  
  Identify communicating entities and the messages they exchange with a sequence or collaboration diagram.  
  Choose language for implementation.  
  2.4. Communication channel(s)
  Identify communicating entities.  
  2.5. Deployment  
  Describe distinct devices and how they will be interconnected.  
3. Plan  
  3.1. Tasks  
  Describe tasks required to gradually develop the work.  
  3.2. Schedule  
  Calendar of the tasks, assignment of group members to tasks.  
4. References  
Tools, libraries, and other references that will be used in the project.  

## 2.4. Await approval

The proposal document will need to be approved by the course faculty.

IMPORTANT: the approval decision is communicated during the week following the proposal submission.

## 2.5. Develop project

Develop basic, intermediate and advanced versions over the project weeks.

Attend the lab sessions to present your ongoing development and receive early feedback from the professor.
A project that receives regular feedback can be improved earlier and is more likely to get a better grade.

## 2.6. Prepare demonstration

IMPORTANT: once your team achieves the intermediate version of the work, start preparing the demonstration.

Write a `README` file with step-by-step instructions on how to run your project.
Record photos, videos or similar artifacts showing the project in action.

## 2.7. Write report

The project final report should describe the problem and the implemented solution, along with a presentation of the results.
The report document should update and extend the proposal document to reflect what was actually achieved.

### 2.7.1. Document requirements

- PDF format;
- Mandatory file name `CXX_WWW_HHMM_L_report.pdf`;
- Report cover;
- Report body: The font should be no smaller than 11pt, with standard line and character spacing;
- Target size of 10 pages (excluding cover), with a limit of 15 pages including Appendixes for reference materials;
- Pages must be numbered (preferably with a label like `Page X of Y`).

### 2.7.2. Document structure (mandatory)

Same as the proposal, with the following differences:

- All sections must be revised and updated;
- Replace _Plan_ with _Results_: state what was actually achieved, with mention of strengths and weaknesses, and justification of implementation choices.

## 2.8. Submit code and report

Before the final deadline of the project, as stated in Section 3 of this document, submit an archive with all the developed code and resources, and the report document.

IMPORTANT: the code archive and the report are submitted separately on the Fénix system.

### 2.8.1. Code archive requirements

- ZIP format - without compiled code, only source and build scripts;
- The mandatory file name is `CXX_WWW_HHMM_L_solution.zip`;
- README file, describing the required platform (e.g. Linux 64-bit, Ubuntu 18.04.1 LTS, Java 8u181) and setup instructions;
- All configuration files and scripts required to configure the solution on the specified platform;
- All developed source code;
- Existing tests and example files.

## 2.9. Check presentation session

The project presentations will occur on the dates following the submission deadline.  
The presentation session calendar will be made available during the final days of the project.

Each group is assigned to a session, in their respective campus, preferably in the time-slot of laboratory they are enrolled to.  
If your group requires a change in the proposed slot, please contact faculty.

## 2.10. Present and defend

Each group will have to attend the full presentation session where they will present.  
The presentation slides must be in English and the presenters should also present in English.  
For the discussion questions, students can answer in Portuguese.

### 2.10.1. Presentation outline

The presentations will be organized as follows:

- 10 minutes for presentation of the work done, supported by slides, including a mandatory live demo  
(also prepare a video of the demo, as backup, just in case there is a technical problem);
- 10 minutes for questions and answers.

It is highly recommended that each presentation includes:

- a slide with the general architecture;
- a slide with the setup process;
- a slide with the operation process.

Each group member must participate and talk in the presentation, and be prepared to answer individual questions.

If necessary, a more detailed discussion will be scheduled with each group.

### 2.10.2. Presence

The presentations are done by the whole group, in person, on campus.
Each group must attend from the beginning of their assigned session and remain for the duration of it.

Presenters need to be physically present in the lecture room.
Each student is expected to attend one full session beyond the one where s/he will present.

### 2.10.3. Presentation archive requirements

IMPORTANT: after making the presentation, you will have to submit the presentation and video on Fénix.

- ZIP format;
- The mandatory file name is `CXX_WWW_HHMM_L_presentation.zip`;
- Presentation in PDF and also in source format (e.g. PowerPoint);
- Text file containing link(s) to download video, photos, screenshots and other media of the solution in action. 
The links must be valid for one month, at least.
The video can also be published in YouTube or a similar platform.

### 2.10.4 Grading

The project grade will take into account:

- Project Design/rational (30%);
- Project implementation (30%);
- Report (20%);
- Presentation (20%).

# 3. Calendar

The relevant dates for the project are shown in the following calendar (all dates are in 2022).

| **Stage**                  | **Deadline**                                                                      |
| ---------------------------|-----------------------------------------------------------------------------------|
| 1. Assemble team           | Week of March 7th, 2022. Opens on Wednesday, March 9th, 2022, 11:30 |
| 2. Pick topic              | Until Friday, March 11th, 2022, 17:00 |
| 3. Write proposal          | Until Thursday, March 17th, 2022, 17:00 |
| 4. Await approval          | In the next lab session, after the submission |
| 5. Develop project         | Until Friday, April 8th, 2022, 17:00 |
| 6. Prepare demonstration   | Start preparing before submission |
| 7. Write report            | Update document as you go |
| 8. Submit code and report  | **Code**: Friday, April 8th, 2022, 17:00. **Report:** Tuesday, April 12th, 2002, 17:00 |
| 9. Check presentation session | Until Tuesday, April 12th, 2022, 17:00 |
| 10. Present and defend     | Sessions start Monday, April 18th, 2022. |

----

## 3.1. Updates

IMPORTANT: keep track of the course [web site](https://fenix.tecnico.ulisboa.pt/disciplinas/AI/2021-2022/2-semestre) for updates and links to online forms.

If there are changes to this document, they can be consulted in the _Git Commit History_.

## 3.2. Final words

We wish you all the best in this technical venture.
Make the most of it!

----

[AmI Faculty](mailto:meic-ami@disciplinas.tecnico.ulisboa.pt)
