# Chat GPT Prompts for the Activities
The following prompts were created as example for the content-first activities at the workshop. 

## 1. Prime the AI with Jacob's persona.
```
INTRODUCTION:
I am creating a prototype for a fictitious job search engine to showcase the accessibility and user requirements for a candidate like Jacob. 

NOTE:
- Do NOT react to this request just yet.
- I will give you specific tasks in the next prompt.
- Just reply with an acknowledgement "Jobs for Jacobs!" 

USER PERSONA:
Here's the persona I'd like to use as a reference for making sure the solution is accessible:

Jacob, Blind, a bit of a geek
"The right technology lets me do anything."

Overview on Jacob
- Jacob is a paralegal in a large law firm. He reviews cases and writes summaries, cross-referencing them to the firm’s own cases and clients. He’s building expertise in his area of law and is hoping to go to law school in a year or so.
- As far as Jacob is concerned, it’s the technology that’s handicapped, not him. When everything is in place, he can work just as fast and just as effectively as anyone in his office.
- He’s a bit of a gadget geek, always trying out new tools, looking for a little edge and something new. The last few years have been a lot of fun with all the new apps, and VoiceOver on his Mac and phone lets him use most of them pretty well. He likes the challenge of learning new tools.
- His other challenge is running. He’s training for a 10K run, running with a club in his neighborhood and using an app to plan his routes and track his distance.
- He’s just started to use The iPhone app, Passbook, and uses it to get train tickets and other travel. The regional rail system has an app, so he can just pull up the barcode and scan it at the ticket office. No fumbling for the right printed card—total independence. Same phone as everyone. Same app as everyone, and it all just works.

Snapshot of Jacob
- 32 years old
- College graduate, legal training courses
- Shares an apartment with a friend
- Paralegal, reviews cases and writes case summaries
- Laptop, braille display, iPhone

The A’s
- Ability: Blind since birth with some light perception
- Aptitude: Skilled technology user
- Attitude: Digital native, early adopter, persists until he gets it

Assistive Technology
- Screen reader (JAWS on his laptop, VoiceOver on his phone)
- Audio recorder (to take notes)
- Braille display
```

## 2. Create User Journey Map

```
TASK: USER JOURNEY MAP
Create a high-level user journey map outlining the steps Jacob might take on the website to find his next job opportunity using the following stages. Breakdown the stages in steps for this journey: 
- Stage 1: Job Searching
- Stage 2: Reviewing Job Descriptions
- Stage 3: Applying for a Job
Include headline and description for each step of the journey.
```
### Results

#### Stage 1: Job Searching
Actions:
- **Navigating to the Job Search Page** – Jacob lands on the website's homepage using his screen reader and navigates to the job search page using keyboard shortcuts or screen reader commands.
- **Setting Search Criteria** – Jacob sets his search criteria, including job title, location, and specific accessibility requirements, using the website's accessible form fields.
- **Browsing Search Results** – After submitting his search, Jacob reviews the search results presented in a clear and organized format, utilizing screen reader navigation commands.

#### Stage 2: Reviewing Job Descriptions
Actions:
- **Selecting a Job Listing** – Jacob selects a job listing from the search results, which opens the job description page for that position.
- **Exploring Job Details** – Jacob explores the job details, including responsibilities, qualifications, and company information, using his screen reader to read the content.
- **Checking for Accessibility Information** – Jacob checks for accessibility-related information, such as workplace accommodations or inclusive hiring practices, within the job description.

#### Stage 3: Applying for a Job
Actions:
 1. **Initiating the Application Process** – Jacob initiates the job application process by clicking on the "Apply Now" button or similar, which opens the application form.
 2. **Completing the Application Form** – Jacob completes the application form, entering his personal information, uploading his resume, and providing additional details as required. The form is designed to be accessible, with proper labels and error messages.
 3. **Submitting the Application** – Jacob reviews his application details, ensures everything is accurate, and submits his application for the job opportunity. He receives a confirmation message on submission.

This user journey map outlines the steps Jacob might take on the website to find and apply for his next job opportunity, taking into consideration his blind condition and tech-savvy nature, ensuring a seamless and accessible experience throughout the process.

### User Journey mapping diagram
You may create a flow diagram from these results.
<img width="792" alt="image" src="https://github.com/WeissCenter/public/assets/135261167/00fe3a67-068a-4e67-9331-b88a089ad12c">


## 3. Create Priority Guides
For each step of the user journey mapping, create each priority guide using the tool of your choice (e.g. Paper/Pencil, Trello or Figma).
The goal is to have a good understanding of the end-user's motives and expectation.

### Example:
<img width="806" alt="priority guides take a step further from user journeys, by adding a description of the intent and outcomes expected from the user." src="https://github.com/WeissCenter/public/assets/135261167/06174649-58fa-4188-82b8-a3f64223eea2">

## 4. Intent Framing: Designing with Words
Intent framing is about designing an interface using words alone, without relying on visual elements. It's a way to guide users through a digital experience using clear, descriptive language. This approach lays out the user's path, explaining what actions they are taking, why, and what the outcomes will be, all through well-chosen words. 

### Priming the AI for the content creation
We can use the following prompt to prime teh AI with the next set of tasks: 

`I am ready to start building the layout page. I will ask you repetitively to perform the same task, so do not react right now. Instead, asked me to enter the action. Your task will be to provide detail content for the actions, jut so that I can copy and paste into my layout.`

### Result
_Understood! I'm here to provide detailed content for your layout actions when you're ready. Please go ahead and enter the action for the first task, and I'll provide the content accordingly._

### Next step: Create content for each action
Simple take each User Journey action and add as a prompt:

`Navigating to the Job Search Page – Jacob lands on the website's homepage using his screen reader and navigates to the job search page using keyboard shortcuts or screen reader commands.`

### Result:

_Certainly! Here's detailed content for the action "Navigating to the Job Search Page" to be included in your layout:_

_**Action:** Navigating to the Job Search Page_
_**Description:** Jacob, a tech-savvy user who is blind, relies on a screen reader to access the website. To begin his job search journey, he needs to navigate from the homepage to the job search page. This process should be smooth and efficient, catering to his specific needs._

_**Content:**_
- _**Heading**: Job Search_
- _**Description**: Welcome to the job search page. Begin your search for the perfect job opportunity here._
- _**Screen Reader Command**: Use your screen reader's navigation commands to find and select the "Job Search" heading._
- _**Search Criteria Form**: Below the heading, you'll find an accessible form with the following fields:_
  - _**Job Title**: Enter the job title you're looking for._
  - _**Location**: Specify the desired location._
  - _**Accessibility Requirements**: Check this box if you have specific accessibility requirements._
- _**Button**: Click the "Search" button to initiate your job search._

### Taking a step further
You may organize this output in an artifact like the one below using your diagraming tool of choice:
<img width="953" alt="A screen capture of a priority guide for job search, job listing and job details" src="https://github.com/WeissCenter/public/assets/135261167/78465c69-daf7-4a59-9760-c85a8785eaf5">


