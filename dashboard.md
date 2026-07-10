# The Editorial Dashboard

The Dashboard is where users manage their assignments and submissions. Understanding the Dashboard will allow you to quickly understand what tasks are outstanding and ongoing in your journal. Familiarizing yourself with this area of OJS is essential.

When you log in and access the Dashboard from your user menu, you can view your assignments either from your Tasks, or from the Assigned to Me Dashboard view. You can also access different Dashboard views that filter assignments by stage and status. The counter on the left will provide an overview of how many total items are in each view.

![The expanded Dashboards menu with a list of various dashboard views on the left, with the Active Submissions dashboard view visible in the main window.](./assets/dashboard-active-3.5.png)

You will also see the “Start a New Submission” button under the list of Dashboard views. You can use this to make a new submission as an author. Learn about making a submission in [⇲Learning OJS for Authors](https://docs.pkp.sfu.ca/learning-ojs/author/en/).


## Get to Know the Dashboard Layout {#dashboard}

When you open the Editor Dashboard menu, you will automatically be taken to the “Assigned to Me” Dashboard view. Let’s look at this example of a Dashboard to understand how it is organized.

![The Assigned to Me Editor Dashboard view, showing 19 submissions in various stages](./assets/dashboard-assigned-3.5.png)

The list of submissions on this Dashboard are displayed by **ID**, **Submission** (a short version of the author(s) and title), **Stage**, **Days** (representing how many days the submission has been in its current stage), **Editorial Activity**, and **Actions** (containing a View button).

The dashboard allows you to see where submissions are in the Editorial workflow and sort your tasks accordingly.

### Understand Submission Stages {#understand-stages}

Each submission will be marked with a colored dot and a status in the “Stage” column. A brief explanation of each stage status is as follows:

**Incomplete**: The author has not completed the submission. *New in 3.5*: Journal Managers and Journal Editors can remove submissions with the Incomplete status by pressing the three dots next to the “Filter” button and choosing “Delete Incomplete Submissions”. 

![The Active Submissions dashboard displaying the option to Delete Incomplete Submissions](./assets/delete-incomplete-3.5.png)


**Submission**: The submission either requires an editor to be assigned, or requires the assigned editor to review and make a decision (i.e., reject [desktop rejection], discuss with other editors or forward for review).

**Review**: The submission is currently undergoing review. The review round will be indicated in the stage. Submissions in this stage will either contain a button directing the assigned Editor to assign reviewers, icons indicating the status of the review, a prompt to enter an editorial decision, or the final editorial decision.

**Copyediting**: The submission is ready to undergo or is currently undergoing copyediting.

**Production**: The submission is ready to be prepared for or is currently being prepared for publication.

**Scheduled for Publication**: The submission has been finalized and added to an issue for future publication.

**Published**: The submission is published in an issue and available to readers.

**Declined**: The submission was declined. Note that this status is only viewable to Journal Managers and Journal Editor roles. 

You can use the various views under the Dashboards menu to filter submissions by these statuses.

> Note: The “Needs Editor” and “Declined” Dashboard views are only accessible to roles with the Journal Manager permission level. Section Editors see the rejected manuscripts that were assigned to them, Journal Managers see all manuscripts.


## Search and Refine Your Results With Filters {#search-filters}
You can use the Search and Filters options to further refine the submissions you see in a given dashboard view. 

![A sample partial search of the Assigned to me dashboard returning two results.](./assets/sample-search-3.5.png)

Use the **Search** tool to search by submission ID, partial or full title, or partial or full author name.

Use **Filters** to further narrow down your search.

![The Filters menu of the Dashboard with options to filter by section, assigned editor, issue, category, and/or date since last activity.](./assets/filters-menu-3.5.png)

- __Sections:__ Narrow your search to submissions made to a specific section or multiple specific sections.

- __Assigned to Editor:__ only roles with the Journal Manager permission level have this filter option. Begin typing the name of a Section Editor, Journal Editor, or Guest Editor's name and choose the correct name from the suggestion to display all articles assigned to the editor.

- __Issues:__ Only Journal Manager level roles can filter by unpublished issues, but other editors will be able to filter by published issues. This field is case-sensitive and requires an exact match. For best results, search by year or title, rather than volume or number. 

- __Categories:__ Choose a submission assigned to a specific category. This option is only available if the Journal Manager has set up at least one customized [category](https://docs.pkp.sfu.ca/learning-ojs/journal-managers/en/policies.md#categories).

- __Days Since Last Activity:__ Specify the number of days since the last activity using the slider or the textbox.


## View Your Assigned Tasks {#view-tasks}

In addition to the Assigned to Me Dashboard view, you can also access your Tasks from the Bell icon in the upper right corner, next to your user menu. The number beside the bell icon represents the number of unread tasks.

Click the bell to open your Assigned Tasks window.

![The expanded Assigned Tasks menu in OJS.](./assets/tasks-3.5.png)

Click the text of the task to jump to the relevant submission. Use the checkbox to mark tasks as new (unread), read, or to delete tasks.

Editors receive a weekly email summary of submissions which require editorial actions, including notifications for:

* Items in the submission stage
* Submissions in the review stage with no reviewer assigned
* Submissions with one or more reviews overdue
* Submissions for which all reviews are completed
* Newly submitted revisions
* Submissions in the copyediting or production stages which have been inactive for 30 or more days

An editor can opt out of email notifications by changing [notification settings in their profile](https://docs.pkp.sfu.ca/learning-ojs/about-ojs/en/#edit-profile) or clicking on the unsubscribe link.

## Get to Know the Submission Record {#submission-record}

When you’re ready to take a look at a specific submission, select the **View** button. This will take you to the submission record. In our example, the submission is in the Submission stage (i.e. it has not yet been sent to review).

![A sample submission record.](./assets/sample-record-3.6.png)

In addition to the author(s) and title at the top of the window, you will see a three column layout. The actions available to you will change at each stage, but the general layout will remain the same. Below, you’ll get to know each of the columns.

### The Left Sidebar Menus: View Stages and Prepare for Publication {#left-sidebar}

On the left side of the Submission Record, you will see:

The **Workflow menu**: This where you can view the work for this Submission in each of the four stages of Submission, Review, Copyediting, and Production. You can click “Workflow” to expand or collapse these options.

> Note: Depending on your role, you may only have access to a limited number of workflow stages. For example, Copyeditors typically only have access to the Copyediting stage. 

The **Publication menu**: This where you will make edits to information and files related to the final published version of a submission. For example, you can edit the title and abstract, list of contributors, keywords and other metadata, as well as schedule the issue for publication. This menu is covered in depth in the [Publication section of this guide](./#publication.md). You can click “Publication” to expand or collapse these options.

### The Central Panel: Files, Tasks, and Discussions {#central-panel}

In the central panel of the Submission Record, you will see:

**Workflow Stage**: The name of the workflow stage you are currently looking at. In our case, the submission is in the Submission stage.

**Current Submission Language**: Indicates the current language of the submission. Useful for multilingual journals to ensure they are working in the right language.

**Submission Status**: A notice of the current status of the submission. You can generally view stages that the submission has not entered or has already completed, but this will always show the current status of the submission.

**Files**: This panel lists the files associated with the stage. The title of this panel will change between stages—for example, in the Submission stage, it will include any files uploaded with the submission, while in the Copyediting stage, there will be two panels: one for draft files needing copyediting, and one for files that have been fully copyedited.

**Tasks & Discussions**: This panel allows participants in a stage to create tasks and communicate with the author, or with others on the editorial team. Using discussions and tasks to collaborate with authors, reviewers, and other members of your editorial team will be an important part of using OJS effectively, so we will cover them in-depth in [a dedicated section further below](/#tasks-discussions).

The content of the central panel will change between stages. Please consult the chapter for your current stage for further information.

### The Right Sidebar Menu: Make Decisions and Assign Participants {#right-sidebar}

On the right side of the Submission Record, you will see:

**Action Buttons**: If there are decisions to make in a stage, you’ll find your options here. This might include recording an editorial decision after reviews are sent in, advancing to the Copyediting or Production stages, or even moving the submission back to a previous stage. In our example, as an Editor in the Submission stage, we have the option Send to Review, Accept and Skip Review, and Decline Submission.

**Participants**: This panel is where you will see the list of participants involved in the submission, for example, any Editors and Authors. Other roles and participants (e.g. copyeditors, layout editors, etc.) will appear here as they are added in subsequent steps. 

If your role allows, you can use the “Assign” button to assign a participant and notify them of their assignment. This option will be explained in detail for each stage.

You can also click the three dots next to a participant's name to access options to Edit, Notify, Login As (this option is only accessible to Journal Managers), or Remove them. 

> Note: All actions taken when logged in as another user will be logged.
{:.warning}

![The three dots menu expanded beside a participant, showing options to Edit, Notify, Login As, and Remove.](./assets/participants-list-3.5.png)

Clicking Edit will allow you to change the participant’s privileges related to the submissions. For example, you can disallow or allow Editors and Authors to make changes to the publication, such as the title, abstract, or other information.

![The Edit Assignment window showing the option to allow the participant to make changes to publication details.](./assets/edit-assignment-3.5.png)

Enabling this option and clicking OK will allow the author to make edits to the following sections in the Publication tab: Title & Abstract, Contributors, and Metadata.

Using the “Notify” option in the Participants menu allows you to send a user an email about the submission. You can choose to write your own email or select from relevant email templates. 

#### The Top Right: View the Activity Log and File Storage Library {#top-right}

The **Activity Log** is accessible to Editors on the top right of the submission record. The Activity Log keeps a record of all decisions and actions taken during the editorial workflow, including any sent emails.

![A sample activity log for a submission.](./assets/activity-log-3.5.png)

The **Notes** tab of the Activity Log can be used to add editorial notes. These notes are only visible to assigned Section Editors, Journal Editors, Journal Managers, and Site Administrators.

![The Notes tab of the Activity log.](./assets/log-notes-3.5.png)

**Library**: The Library is accessible to Authors and Editors from the top right of every submission page. It is a general file storage for documents that may include conflict-of-interest forms, galley approval forms, etc. 

This submission-specific Library is distinct from the journal-wide [Publisher Library](https://docs.pkp.sfu.ca/learning-ojs/journal-managers/en/other-tools.md#publisher-library), which can generate public links for uploaded content.

Users throughout the editorial workflow can access all the files in the Publisher Library by opening the submission-specific Library and clicking "View Document Library".

![The location of the View Document Library button in the upper right corner of the Submission Library panel.](./assets/submission-lib-3.5.png)

You can select these files as attachments when sending notification emails as the submission moves through each stage.

## Use Tasks and Discussions to Communicate {#tasks-discussions}

OJS allows participants in each stage to communicate using discussions and tasks. 

Discussions support ongoing communication and file sharing. 

Tasks are actionable to-do items that can be assigned to specific users and tracked with due dates. Use tasks to identify, track, and share related files to action items that need to be completed during specific submission stages. For example, you may create a “Review ethics compliance” task during Submission or a “Translate abstract” task during Production. These may be created by editors as needed, generated from templates defined by the Journal Manager, or automatically opened at specific workflow stages based on journal settings. 

All roles should understand how to effectively use tasks and discussions.

### Create a Task or Discussion {#create-discussion}

The ORE platform uses tasks extensively to manage the various checks that must be completed with each stage of the submission. You will find that tasks are automatically added to the Tasks & Discussions panel. These will be reviewed more closely in subsequent chapters. For now, take the time to get familiar with this panel and how tasks and discussions are managed.

![The Desk Review Tasks & Discussion panel of the Submission stage with a cursor hovering over the Add button.](./assets/task-disc-panel-ore.png)

In addition to the tasks automatically associated with the stage (i.e. “Pre-check management”), you can click the “Add” button in the stage’s tasks & discussion panel to begin a new task or discussion. Be sure to use the panel corresponding to the current stage to ensure that communications are relevant.

This opens the slide-out window for adding a task/discussion.

Enter a title. Alternatively, you can search for an existing template by its title.
![The slide-out window with field to enter the task/discussion name and a list of selectable participants. On the left is a search bar for searching templates and a list of available task templates.](./assets/task-disc-panel-3.6.png)
Then choose the participants you would like to include in the task and/or discussion.

> **Who can access discussions?**
> As a general rule, roles with Journal Manager level permissions (Journal Manager, Journal Editor) can see all discussions in a stage. 
> Other roles, such as Section Editors, Reviewers, Authors, Copyeditors, etc., will *only see discussions where they have been selected as participants*.
> Authors and Reviewers will not be able to use discussions to communicate with each other in Anonymous review.

Click “Enter task information” to identify this as a task. You can select an appropriate due date from the calendar, assign a participant as being responsible for the task, and choose whether the task should start immediately. You can skip this section if you only want to start a discussion thread.
![In this example, “Enter Task Information” has been checked off, and a due date has been entered.](./assets/task-info-3.6.png)
In the Discussion area, you can enter a message. For a task, this might include an overview of the task and specific instructions on how to complete it. For a discussion, this may simply be questions or information you wish to share with the participants.

You can also attach a file to the message.
To attach a file:
1. Click Attach File and select Upload File to upload a file independent from the workflow, or Workflow Files to choose a file that is already included with the submission.
2. Select the file you wish to upload from your computer, or the relevant file from the list of Workflow Files. Click Attach File.

![A sample discussion field populated with instructions. A file has been attached with the option to remove directly beside it.](./assets/task-disc-attach-3.6.png)

You can edit or delete any attached files by clicking “Remove” next to the file.
Click Save to add your task or discussion. 
> Editors can edit and delete tasks/discussions by pressing the three dots next to the task/discussion and clicking the Edit or Delete links. Note that deleted discussions will **still be logged in the Activity Log**. This means the content of deleted discussion will still be accessible to Editors.
{:.notice}

### Read and Reply to a Task or Discussion {#read-reply}

Created tasks and discussions will be added to the Tasks & Discussions panel for the relevant stage. 
![The list of tasks and discussions showing a single task in progress marked “started”.](./assets/task-list-3.6.png)
You can easily see due dates, the owner and status of the task/discussion, as well as who sent the most recent reply, when the reply was sent, and the number of replies. 

To open a task/discussion, click the subject of in the Tasks & Discussions panel.

![An example discussion between the author and Editors, including an attachment and an option to Add New Message.](./assets/add-disc-message-3.6.png)

All participants as well as all messages will be displayed in the window. Attached files are displayed below their messages. You can download the file by clicking the filename.

To reply, click the Add New Message button. You can include an attachment in a reply just as you would when starting a discussion/task.

When you are ready to send the message and any attachments, click OK at the bottom of the Add discussion window.

> Creating tasks and discussions will send an email containing the message and attachment to participants. However, replying to this email from your inbox *will NOT log the communication in OJS*. If you wish to have a complete log of communication in OJS, users should be encouraged to use the Tasks & Discussions panel to reply.
{:.tip}

If you have completed a task assigned to you, click the name of the task and check the box next to “Complete this task” under “Task Information”. You can also close a task/discussion by clicking the checkbox in the “Close” column from the list of tasks.
> Note that while discussions can be reopened by Editors once closed, **tasks can never be reopened**. Be cautious when closing tasks. New messages can still be added to the task or discussion even after it is closed.
{:.warning}

![A task that has been closed using the close checkbox. The task is now in the “Closed” list.](./assets/task-closed-3.6.png)

