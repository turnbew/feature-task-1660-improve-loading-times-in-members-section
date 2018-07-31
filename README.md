FOR PRIVACY AND CODE PROTECTING REASONS THIS IS A SIMPLIFIED VERSION OF CHANGES AND NEW FEATURES

TASK DATE: 21.06.2018 - FINISHED: 31.07.2018

TASK LEVEL: ADVANCED (HIGH)

TASK SHORT DESCRIPTION: [
	For continuously test the new members edit page
	- code cleaning
	- using new code rules
	- using AJAX techniques to save data
	- cut super-complex form smaller parts
	- faster data catch 
]

GITHUB REPOSITORY CODE: feature/task-1660-improve-loading-times-in-members-section

CHANGES

	NEW FILES:	
		....work_settings\controllers\members_new\ajax.php
		....work_settings\controllers\members_new\common.php
		....work_settings\controllers\members_new\modal.php
		....work_settings\controllers\members_new\page.php
		....work_settings\controllers\members_new\tab.php
		....work_settings\js\members_new\modals\activity_add.js
		....work_settings\js\members_new\modals\activity_add_setup.js
		....work_settings\js\members_new\modals\address.js
		....work_settings\js\members_new\modals\address_setup.js
		....work_settings\js\members_new\modals\consent_option.js
		....work_settings\js\members_new\modals\consent_option_setup.js
		....work_settings\js\members_new\modals\education.js
		....work_settings\js\members_new\modals\education_setup.js
		....work_settings\js\members_new\modals\email.js
		....work_settings\js\members_new\modals\email_setup.js
		....work_settings\js\members_new\modals\gift_aid_declaration.js
		....work_settings\js\members_new\modals\gift_aid_declaration_setup.js
		....work_settings\js\members_new\modals\group_questions.js
		....work_settings\js\members_new\modals\group_questions_setup.js
		....work_settings\js\members_new\modals\name.js
		....work_settings\js\members_new\modals\name_setup.js
		....work_settings\js\members_new\modals\note.js
		....work_settings\js\members_new\modals\note_setup.js
		....work_settings\js\members_new\modals\phone.js
		....work_settings\js\members_new\modals\phone_setup.js
		....work_settings\js\members_new\modals\pipeline_add.js
		....work_settings\js\members_new\modals\pipeline_add_setup.js
		....work_settings\js\members_new\modals\pipeline_stages.js
		....work_settings\js\members_new\modals\pipeline_stages_setup.js
		....work_settings\js\members_new\modals\postal_label.js
		....work_settings\js\members_new\modals\postal_label_setup.js
		....work_settings\js\members_new\modals\question_answer.js
		....work_settings\js\members_new\modals\question_answer_setup.js
		....work_settings\js\members_new\modals\send_email.js
		....work_settings\js\members_new\modals\send_email_setup.js
		....work_settings\js\members_new\modals\upload_doc.js
		....work_settings\js\members_new\modals\upload_doc_setup.js
		....work_settings\js\members_new\modals\vine_add.js
		....work_settings\js\members_new\modals\vine_add_setup.js
		....work_settings\js\members_new\modals\vine_edit.js
		....work_settings\js\members_new\modals\vine_edit_setup.js
		....work_settings\js\members_new\modals\work.js
		....work_settings\js\members_new\modals\work_setup.js
		....work_settings\js\members_new\tabs\activity_tracker_setup.js
		....work_settings\js\members_new\tabs\docs.js
		....work_settings\js\members_new\tabs\docs_setup.js
		....work_settings\js\members_new\tabs\fundraising.js
		....work_settings\js\members_new\tabs\fundraising_functions.js
		....work_settings\js\members_new\tabs\fundraising_setup.js
		....work_settings\js\members_new\tabs\offline_profile.js
		....work_settings\js\members_new\tabs\offline_profile_setup.js
		....work_settings\js\members_new\tabs\online_profile.js
		....work_settings\js\members_new\tabs\online_profile_setup.js
		....work_settings\js\members_new\members.js
		....work_settings\views\members_new\modals\activity_add.php
		....work_settings\views\members_new\tab_contents\activity_tracker.php
		....work_settings\views\members_new\modals\address.php
		....work_settings\views\members_new\snippets\address.php
		....work_settings\views\members_new\modals\consent_option.php
		....work_settings\views\members_new\tab_contents\docs.php
		....work_settings\views\members_new\edit.php
		....work_settings\views\members_new\modals\education.php
		....work_settings\views\members_new\modals\email.php
		....work_settings\views\members_new\snippets\email.php
		....work_settings\views\members_new\tab_contents\family_wine.php
		....work_settings\views\members_new\tab_contents\fundraising.php
		....work_settings\views\members_new\modals\gift_aid_declaration.php
		....work_settings\views\members_new\modals\group_questions.php
		....work_settings\views\members_new\modals\message.php
		....work_settings\views\members_new\modals\name.php
		....work_settings\views\members_new\snippets\name.php
		....work_settings\views\members_new\modals\note.php
		....work_settings\views\members_new\snippets\note.php
		....work_settings\views\members_new\snippets\note_fundraising.php
		....work_settings\views\members_new\tab_contents\offline_profile.php
		....work_settings\views\members_new\tab_contents\online_profile.php
		....work_settings\views\members_new\modals\phone.php
		....work_settings\views\members_new\snippets\phone.php
		....work_settings\views\members_new\modals\pipeline_add.php
		....work_settings\views\members_new\modals\pipeline_stages.php
		....work_settings\views\members_new\modals\postal_label.php
		....work_settings\views\members_new\snippets\postal_label.php
		....work_settings\views\members_new\modals\question_answer.php
		....work_settings\views\members_new\modals\send_email.php
		....work_settings\views\members_new\tab_contents\summary.php
		....work_settings\views\members_new\modals\upload_doc.php
		....work_settings\views\members_new\modals\vine_add.php
		....work_settings\views\members_new\snippets\vine_add.php
		....work_settings\views\members_new\modals\vine_edit.php
		....work_settings\views\members_new\modals\work.php
		
	IN FILES: 
		
		TONS of changes - there's no chance to write down everthing - more than 200 changes in different files
		
