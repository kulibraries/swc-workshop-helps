# Read Me

## Carpentries Workshop Helps

This repository includes files that can be helpful to administering and running  Carpentries workshops. Most templates are specific to workshops hosted at the University of Kansas but can be modified for different workshop hosts.

### Files to include as resources for learners in a workshop etherpad
* command-handout.[docx|md]
	* Basic commands and their actions for the Bash Shell and Git lessons. Useful for learners as a cheat sheet during a workshop and a reminder afterward.
* directory-map.pdf
	* Visualizes the directory structure of the Software Carpentry Bash Shell lesson. Useful for orienting learners to their file system and the directories used during the lesson.
* git_collaboration.txt
    * The outline of steps that learners will work through on the *Countries Git/GitHub Collaboration* exercise.
* git_editors.txt
    * A list of 3rd party editors and how to configure Git to use them
* Resources_for_Continued_Learning.[md|txt|pdf]
    * A list of links to addition resources that learners can access after workshops. This can be sent out via Eventbrite or other email systems

### Workshop administrative files
* template_email_catering_request.txt
    * Text for contacting KU catering services for workshop refreshments
* template_email_helper_online_reminder.txt
	* Text for contacting workshop helpers one week prior to an online workshop date
* template_email_helper_reminder.txt
	* Text for contacting workshop helpers one week prior to an in-person workshop date
* template_email_helper_thanks.txt
	* Text for thanking workshop helpers after the workshop
* template_email_learner_followup.txt
	* Text for contacting learners no more than one week after after the workshop
* template_email_learner_online_connection.txt
	* Text for distributing connection information for online workshops. Schedule send for the day before the first day of an online workshop.
* template_email_learner_online_reminder.txt
	* Text for reminding learners of an upcoming online workshop and need for installing appropriate software in advance. Send out approximately one week prior to the workshop or include in registration confirmation.
* template_email_learner_reminder.txt
	* Text for reminding learners of an upcoming in-person workshop and need for installing appropriate software in advance. Send out approximately one week prior to the workshop or include in registration confirmation.
* template_ku_etherpad.etherpad
    * This template file is uploaded prior to an in-person workshop to the workshop's etherpad. Modify the etherpad to include correct information for that workshop.
* template_ku_online_etherpad.etherpad
    * This template file is uploaded prior to an online workshop to the workshop's etherpad. Modify the etherpad to include correct information for that workshop.
* template_ku_swc_report.md
    * A markdown template file for use in preparing the final workshop report after a workshop has been hosted. The report is useful for institutional Carpentries memberships, sponsors, and administrators.
* template_slides_swc_intro.pptx
    * An introductory slide show that includes sponsor names, instructors, helpers, and housekeeping details, e.g.: restroom and restaurant locations, links to workshop website and etherpad. Asks learners to complete pre- and post-workshop surveys.
* template_transcript_stickies.txt
	* This template can be used after an in-person workshop for transcribing minute card feedback submitted on physical sticky notes.
* template_workshop_data_collection.csv
	* This template contains headers for recording data about a workshop, including attendance, instruction, and help. Use with the codebook `workshop_data_collection_codebook.pdf` for most consistent data collection.
* wayfinding.docx
	* Signage templates for directing learners to a room for an in-person workshop.
* workshop_data_collection_codebook.pdf
	* This codebook documents the data fields and codes used in `template_workshop_data_collection.csv`.
	
### Scripts

* mk_attend_list.py
    * A very beta version of a python script that takes a list of learners names from the etherpad and the Eventbrite sign-up file that builds a simple cvs file of learner names, emails and domains/departments.
