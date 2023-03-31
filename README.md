Instituto Superior Técnico, Universidade de Lisboa

**Ambient Intelligence**

# Project Overview

This document describes the organization of the project for the Ambient Intelligence / Ambientes Inteligentes (AmI) course.

The document concludes with a calendar containing all the deadlines.

For any questions regarding this document, please contact:  
[meic-ami@disciplinas.tecnico.ulisboa.pt](mailto:meic-ami@disciplinas.tecnico.ulisboa.pt)

# 1. Introduction

The AmI (Ambient Intelligence) course requires a practical project dealing with so called "smart" technologies.  
The whole process is organized in sequential stages:

| **Stage**                                                                             |
| --------------------------------------------------------------------------------------|
| [1. Assemble team](#21-assemble-team)                                                 |
| [2. Pick topic area](#22-pick-topic-area)                                             |
| [3. Write proposal with literature review](#23-write-proposal-with-literature-review) |
| [4. Submit and await feedback](#24-submit-and-await-feedback)                         |
| [5. Develop project](#25-develop-project)                                             |
| [6. Prepare demonstration](#26-prepare-demonstration)                                 |
| [7. Write report](#27-write-report)                                                   |
| [8. Submit code and report](#28-submit-code-and-report)                               |
| [9. Check presentation session](#29-check-presentation-session)                       |
| [10. Present and defend](#210-present-and-defend)                                     |  

<br />

# 2. Stages

Each stage of the project is described in the following sections.

## 2.1. Assemble team

Assemble a team of 3 students, committed to work together.  
Inform the laboratory professor of the group members.

## 2.2. Pick topic area

The specific topic for the project should be selected by the project team.

We suggest that the team starts by selecting one of the following broad topic areas:

1. Smart Buildings  
2. Industry & Supply Chain  
3. Smart Cities  
4. Assisted Living

See [examples of project topics](https://github.com/tecnico-ami/Project-Topics/blob/main/README.md) for each topic area.
You can adapt one of these ideas or propose a new one.

## 2.3. Write proposal with literature review

After having chosen a topic, your group should prepare a proposal document.
The project proposal should describe the specific problem to address and the proposed solution.

Please bring a draft of the proposal to your next laboratory session to present it and receive feedback.  
IMPORTANT: the proposal document must be submitted on that same week, on the days following the laboratory session.

One of the important parts of the document is the literature review.

### 2.3.1. Literature review

Your proposal must include a (small) literature review, focused on the topic area.
The review will start with a search for relevant scientific papers, where you will learn about the core concepts and solution approaches.
The bibliography should have a minimum of 2 (two) and a maximum of 3 (three) papers.
These papers must have been published in a scientific journal or conference related with ambient intelligence in the last 2 years.

IMPORTANT: see the [list of journals and conferences related with ambient intelligence](https://github.com/tecnico-ami/awesome-ambient-intelligence#publications)

### 2.3.2. Technical requirements

The planned project will need to include:

- sensors;
- actuators;
- network communication.

### 2.3.3. Document structure (mandatory)

1. Introduction  
_Present an overview of the project, with approximately 200 words._  
2. Literature Review  
_Define the main concepts related with your topic area._  
_Summarize and cite the scientific papers assigned to and picked by your group._  
_Size ~ 300 words for each paper._  
3. Problem  
_Given the chosen topic area, what is the specific problem being solved?_  
_What is the value to be added by the proposed solution?_  
  3.1. Assumptions  
  _Which conditions are assumed to be true for the solution to operate as intended?_  
  3.2. Solution Requirements  
  _Which requirements were identified for the solution? Present as a list._  
4. Proposed solution  
  4.1. Overview  
  _Diagram of the architecture and brief explanation of all components._  
  4.2 Logical design  
  _Identify functions that the solution will perform._  
  _Identify communicating entities and the messages they will exchange with a sequence or collaboration diagram._  
  4.3 Technology selection  
  _Identify the main development platform (e.g. Arduino IDE, Android Studio, etc.)._  
  _Choose language(s) for implementation._  
  _Describe the distinct devices and how they will be assembled and interconnected._  
  _Choose protocol(s) for communication._  
  _[See suggestions](https://github.com/tecnico-ami/awesome-ambient-intelligence)._  
5. Bill-of-materials  
  5.1 Hardware  
  _List of hardware components required for the work, and their purpose._  
  5.2 Software  
  _Tools and libraries to use, and their purpose._  
6. Plan  
  _Describe tasks required to gradually develop the work._  
  _Start with the core functionalities, and then more advanced functions._  
  _Assign tasks to team members._  
7. Bibliography  
  _Scientific and technical publications cited in the proposal text._  

### 2.3.4. Additional document requirements

- PDF format;
- Mandatory file name `CXX_proposal.pdf`;
(where `C` is A for Alameda, T for Tagus, `XX` is the Fenix group number with two digits);
- Report cover: Project title. Headed by course name, group campus, group number.
In the next row: group members sorted by ascending student number.
For each student, include the number, name and a professional photo in color.
All photos should be framed so that the faces are approximately of the same size;
- Report body: The font should be no smaller than 11pt, with standard line and character spacing;
- The use of diagrams (such as UML or SysML) is recommended for clear and concise communication;
- Target size of 6 pages (including cover and bibliography);
- Pages must be numbered (preferably with a label like `Page X of Y`).

## 2.4. Submit and await feedback

Before the proposal deadline expires, submit a ZIP archive with the proposal document and the papers included in the literature review.

The proposal document will be read by the course faculty and you will receive feedback.  
Receiving the feedback is essential so that you can consider the proposal as approved, so be sure to attend the next laboratory session.
Meanwhile, get started on the project.

## 2.5. Develop project

Develop basic, intermediate and advanced versions of the project over the available weeks.

Attend the lab sessions to present your ongoing development and receive early feedback from the professor.  
A project that receives regular feedback can avoid mistakes, be improved earlier and is more likely to get a better grade.

## 2.6. Prepare demonstration

IMPORTANT: once your team achieves the intermediate version of the work, start preparing the demonstration.

Write a [`README` file](https://gist.github.com/miguelpardal/dedf25563c37b8fa906fd8cf23b5daae) to include on the project root directory, with step-by-step instructions on how to assemble and run your project.  
Record photos, videos or similar artifacts showing the project in action.

## 2.7. Write report

The project final report should describe the problem and the implemented solution, along with a presentation of the results.
The report document should update and extend the proposal document to reflect what was actually achieved.

### 2.7.1. Document structure (mandatory)

Same as the proposal, with the following differences:

- Replace _Plan_ (Section 6) with _Conclusion_ (new Section 6).
In it, state which requirements (from Section 3.2) were actually satisfied.
Also, write a summary of the achieved results, with mention of strengths and weaknesses of the produced solution;
- All other sections must be revised and updated to match the actual work produced.
In particular, the _Literature Review_ (Section 2) should include mention of and comparison with other projects/products that actually inspired the work.

### 2.7.2. Additional document requirements

The changes to the proposal requirements are the following:

- Mandatory file name `CXX_report.pdf`;
- Target size of 10 pages (excluding cover and bibliography).

## 2.8. Submit code and report

Before the final deadline of the project, as stated in the Calendar (Section 3) of this document, submit an archive with all the developed code and resources, and the report document.

IMPORTANT: the code archive and the report are submitted separately on the Fénix system.

### Code archive requirements

- ZIP format - without compiled code, only source and build scripts;
- The mandatory file name is `CXX_solution.zip`;
- `README` file, describing the required platforms, components, software, and setup instructions;
- All configuration files and scripts required to configure the solution on the specified platform;
- All developed source code;
- Existing tests and example files.

## 2.9. Check presentation session

The project presentations will occur on the dates following the submission deadline.  
The presentation session calendar will be made available during the final days of the project or after the submission.

Each group is assigned to a session, in their respective campus, preferably in the time-slot of laboratory they are enrolled to.  
If your group requires a change in the proposed slot, please contact faculty by email.

## 2.10. Present and defend

Each group will have to attend the full presentation session where they will present.  
The presentation slides must be in English and the presenters should also present in English.  
For the discussion questions, students can answer in Portuguese.

### 2.10.1. Presentation outline

The presentations will be organized as follows:

- 10 minutes for presentation of the work done, supported by slides, including a mandatory live demonstration  
(also prepare a video of the demonstration);
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
Each student is also invited to attend another full session beyond the one where s/he will present.

### 2.10.3. Presentation archive requirements

IMPORTANT: after making the presentation, you will have to submit the presentation and video on Fénix.

- ZIP format;
- The mandatory file name is `CXX_presentation.zip`;
- Presentation in PDF and also in source format (e.g. PowerPoint);
- Text file containing link to download video.
You can also include photos, screenshots, and other media of the solution in action. 
The links must be valid for one month, at least.
The video can also be published in YouTube or a similar platform.

Optionally, the ZIP may also include an updated README and other files modified after the code submission.

### 2.10.4. Grading

The project grade will take into account:

- Literature review (10%);
- Project design/rational (20%);
- Project implementation (30%);
- Report (20%);
- Presentation (15%);
- Live Demonstration (5%).

If the demonstration is not live, then you forfeit that evaluation component.

# 3. Calendar

The relevant dates for the project are shown in the following calendar (all dates are in 2023).

| **Stage**                  | **Deadline**                                                                      |
| ---------------------------|-----------------------------------------------------------------------------------|
| Assemble team              | Week of February 20th. Opens on Monday                                            |
| Write proposal             | Until Thursday, March 2nd, 17:00                                                  |
| Develop project            | Until Friday, March 24th                                                          |
| Prepare demonstration      | Start preparing midway through the development                                    |
| Write report               | Update document as you go                                                         |
| Submit code and report     | **Code**: Monday, March 27th, 17:00. **Report:** Wednesday, March 29th, 17:00     |
| Check presentation session | Until Friday, March 31st                                                          |
| Present and defend         | Sessions start Monday, April 10th.                                                |

## 3.1. Updates

IMPORTANT: keep track of the course [web site](https://fenix.tecnico.ulisboa.pt/disciplinas/AI/2022-2023/2-semestre) for announcements.

If there are changes to this document, they can be consulted in the _Git Commit History_.

## 3.2. Final words

We wish you all the best in this technical venture.
Make the most of it!

----

[AmI Faculty](mailto:meic-ami@disciplinas.tecnico.ulisboa.pt)
