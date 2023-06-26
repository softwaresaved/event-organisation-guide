.. _cw23-eps-infrastructure:

CW23 Infrastructure
====================

As this was the Institute’s first hybrid CW, we kept the majority of the infrastructure the same from CW21 (see :ref:`cw21-eps-infrastructure`) and CW22 to reduce the number of moving parts and focus on adding in-person elements to our existing online setup.

For a future hybrid CW, looking into an all-encompassing virtual events platform that integrates registration, video conferencing, chat and more (such as Zoom Events) could be a natural next step.

Platforms
-------------

We used the following platforms to help us organise and run the event.

Event management
^^^^^^^^^^^^^^^^^^^

- `GitHub <https://github.com/>`_: We used a private GitHub repository to project manage the event, using `Issues <https://docs.github.com/en/issues/tracking-your-work-with-issues>`_ to keep track of what needed to be done and our progress.
- `SSI website  <https://software.ac.uk/cw23>`_: The CW23 event page was hosted on the Institute website.
- `Mailchimp <https://mailchimp.com/>`_: We used Mailchimp to notify our audience of CW23 updates and when event registration opened.
- `Eventbrite <https://www.eventbrite.com/>`_: We created a `CW23 Eventbrite page <https://www.eventbrite.co.uk/e/collaborations-workshop-2023-cw23-collabw23-tickets-483692767087?aff=SSIWebsite>`_ to manage registrations, fee processing and send email notifications to registrants.
- `Bit.ly <https://bitly.com/>`_: We generate a lot of links during a CW and we used Bit.ly to manage them, make them more user-friendly and monitor engagement/clicks.
- `Google Forms <https://docs.google.com/forms>`_: We conducted the calls for sponsorship, financial assistance, lightning talks and mini-workshop and demo sessions using Google Forms.
- `Figshare <https://figshare.com>`_: Through our partnership with Figshare, we were once again able to manage conference outputs such as lightning talk slides through a `Figshare conference portal <https://ssi-cw.figshare.com/>`_.

  - Lightning talk presenters, mini-workshop facilitators, and participants who wanted to generate DOIs for their CW23 outputs were able to submit directly to the portal using `this form <https://ssi-cw.figshare.com/submit>`_.

- `uCONFLY <http://uconfly.org/>`_: We used the SSI’s unconference resource management system uCONFLY to manage collaborative Google documents for the interactive sessions.

  - Following `our procedure from CW20 <https://event-organisation-guide.readthedocs.io/en/latest/eog/eog-in-practice/cw20/infrastructure.html>`_, we used uCONFLY purely as an admin tool by creating the templates for the Discussion Session, Collaborative Ideas session, Mini-workshop and demo sessions, and Hack Day ideas, and generated all of the needed instances ahead of time ourselves.

- `Google Sheets <https://docs.google.com/spreadsheets>`_: We collated the uCONFLY generated documents via Google Sheets (see this `example spreadsheet <https://doi.org/10.6084/m9.figshare.12498278>`_) which we linked to in each day’s collaborative note-taking document/agenda (see section on Collaborative Documenting below for details).


Video conferencing
^^^^^^^^^^^^^^^^^^^

- `Zoom <https://zoom.us/>`_: We used Zoom as our primary video conferencing and management platform, as we had the most experience with it and it had the best performance, scalability and functionality out of the many platforms we tested.

  - The ability to create and manage breakout rooms is essential for our interactive sessions such as the Discussion session, Collaborative Ideas session and Hack Day.
  - The `added functionality of live transcription and captioning in Zoom <https://support.zoom.us/hc/en-us/articles/4403492514829-Viewing-captions-in-a-meeting-or-webinar>`_ was a game changer, as it allowed participants to access transcription and captioning within the breakout rooms during the interactive activities.
  - We had six professional/education Zoom Host accounts in total to accommodate parallel sessions: one for the main/plenary room (where the Discussion session, Collaborative Ideas session and Hack Day were managed in breakout rooms), plus four for the mini-workshop sessions which took place in parallel outside of the plenary room, plus one for backup.

- `YouTube <https://www.youtube.com/>`_: Following CW21 and CW22, we live streamed the `keynote panel presentations and Q&A <https://software.ac.uk/cw23/live-streams>`_ via the `SSI YouTube channel <https://www.youtube.com/user/SoftwareSaved>`_.

  - YouTube was also used to share the session recordings after the event.

- `Restream <https://restream.io/>`_: We needed to stream from Zoom to both YouTube and our live transcription service Otter.ai (see Accessibility section below) simultaneously, which required the use of a third party streaming application (as Zoom could only stream to one service at a time).

  - We followed `this guide on Captioned video calls AND YouTube streaming by Open Life Science <https://openlifesci.org/posts/2020/12/16/streaming-to-youtube-and-to-otter-at-once/>`_ to get the three platforms to work together (and practiced the procedure many times ahead of the event).


Accessibility
^^^^^^^^^^^^^^

- `Otter.ai <https://otter.ai/>`_: We used Otter.ai for live transcription and captioning during the event.

  - This required Otter.ai Business subscriptions for each Zoom Host account used in running the event.
  - Some feedback we received during the event, was that participants appreciated the live transcription because it meant that they were able to focus on the presentations without having to take their own notes. It also captured what was said at times when the internet was unstable for people to catch up with.


Chat system
^^^^^^^^^^^^

- `Slack <https://slack.com/>`_: We used Slack as our primary chat platform, as it persists outside the meeting room which is helpful for maintaining access to resources shared, referencing discussions and facilitating community engagement.

  - We created practical channels for event organisation and communication, such as a ``#help-desk`` channel for participants to direct their technical issues to, an ``#organiser-announcements`` channel for organisers to communicate event and session information to participants, and ``#introductions`` for participants to introduce themselves.
  - Private backchannels were created for the Code of Conduct Committee, SSI staff, and Hack Day judges.
  - Participants were able to create their own channels for their own use such as for their Discussion session groups and Hack Day teams, and also  created more informal channels such as ``#pets`` for sharing photos of pets.

- `Sli.do <https://www.sli.do/>`_: We used a professional subscription of Sli.do for audience Q&A and engagement during the keynote session. We also set up instances for use by the mini-workshop and demo session facilitators.


Collaborative documenting
^^^^^^^^^^^^^^^^^^^^^^^^^^

- `Google Docs <https://docs.google.com/>`_: We used Google Docs as our primary platform for collaborative note-taking and keeping everyone synchronised.

  - We created a main document for each day which contained that day's agenda (which linked to other sections of the doc with information and space for note-taking and questions for each session), connection details and other important links, participation guidelines, guidance and instructions, roll call, space for feedback, and a disclaimer in the header asking participants not to share any links publicly during the event (see `the collaborative document for CW23 Day 1 here <http://bit.ly/ssi-cw23-day1-notes>`_).
  - We added a license (`CC BY 4.0 <https://creativecommons.org/licenses/by/4.0/>`_) to all of the Google Docs generated for CW23 so that participants would know how they could be used going forward.
  - Although we chose Google Docs because it has a low barrier to accessibility (no need to log in or register and you do not need to know specific syntax or markdown language), participants using screen readers or voice control had difficulty using it (we empowered them to use any platform that worked best for their needs, and `HackMD <https://hackmd.io>`_ seemed to work better for these cases).


Resources
----------

We created the following infrastructure resources to help us manage the event.

Organiser-facing
^^^^^^^^^^^^^^^^^^^^^^^^^^

- A spreadsheet for planning the event and keeping track of registrations and `budget <https://doi.org/10.5281/zenodo.4071895>`_.
- An index of links to documentation and event resources for organisers to easily navigate on the day.
- A duties roster with assignments, lists and descriptions of the roles and responsibilities in both document and spreadsheet formats.
- A spreadsheet for the mini-workshop and demo sessions assignments with links to the Zoom rooms, notes documents, and event role assignments for the parallel sessions.
- Zoom instructions for the hosts and co-hosts of the parallel sessions.
- A checklist for the event chair of what tasks need to be done before and at the start of the event (such as a reminder to send the connection details, assign co-hosts, record the event and take a group photo).
- A checklist for the event chair of how to set up the live stream during the event (a complicated procedure involving steps in Zoom, YouTube, Otter, and Restream).
- A table for the event chair of which breakout rooms needed to be opened when.
- A speaker guide to help the demo speakers with their recordings.
- A list of Tweets and social media posts to be shared throughout the event.
- A spreadsheet to facilitate Hack Day judging and scoring.
- A spreadsheet for keeping track of prizes and winners.
- Instructions for processing the session recordings, generating subtitles and publishing the videos on YouTube.
- A spreadsheet to facilitate and track processing the session recordings (for example, with information on the start and end times for splitting recordings, locations of cover and subtitle files, session information, and YouTube metadata).
- Binders for the Event Chair and Logistical Supporters at the help desk containing the duties roster, full programme, information about the venue and audio/visual services, information relating to catering and the workshop dinner (such as participants' dietary requirements), information about accommodation, and a list of participants for registration.

Participant-facing
^^^^^^^^^^^^^^^^^^^^^^^^^^

- Collaborative notes documents for each day of the event (with agenda) to guide participants through the event, provide another pathway to engagement and compile questions, notes and outputs from the event:

  - `CW23 Day 1 Notes <http://bit.ly/ssi-cw23-day1-notes>`_
  - `CW23 Day 2 Notes <http://bit.ly/ssi-cw23-day2-notes>`_
  - `CW23 Hack Day Notes <http://bit.ly/ssi-cw23-hack-day-notes>`_

- A template document for the Discussion group session and 26 instances generated in uCONFLY.
- A template document for the Collaborative Ideas session and 26 instances generated in uCONFLY.
- A template document for the Mini-workshop and demo sessions and 15 instances generated in uCONFLY.
- A template document for the Hack Day pitches and 26 instances generated in uCONFLY.
- A spreadsheet to collate the Discussion group session topics and documents, and facilitate group sign-up.

  - We adapted this for a hybrid event by pre-assigning Group IDs to spaces, each with an in-person location and an associated Zoom breakout room. We asked remote participants to include "(R)" at the end of their names when they signed up to discussion topics. We assessed the groups as they formed, and assigned larger hybrid groups to in-person spaces that had Meeting OWLs. 

- A spreadsheet to collate the Collaborative Ideas session documents and group assignments.
- A spreadsheet to collate the Hack Day pitch documents.
- A spreadsheet to facilitate Hack Day teams registration and sign-up.
- A form to facilitate voting for Collaborative Ideas.
- A form to facilitate submissions to the COVID-19 daily self-testing raffle.
- A form to collect feedback.
