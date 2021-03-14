						README!
#Created by Case group NUMBER 47

USER GUIDE 	- 	(Unzip files if not unzipped)
	
	0.	Running SQL Queries requires MySQL Server and Workbench version 8.0. and higher installed.
		
		To install MySQL Server and Workbench, you need to follow steps thoroughly in following videos.

		For installing MySQL Server and Workbench on Windows 10:
		
			https://www.youtube.com/watch?v=OM4aZJW_Ojs	*
	
		For installing MySQL Server and Workbench on macOS:

			https://www.youtube.com/watch?v=-BDbOOY9jsc	*


	1.	Open your MySQL Workbench and connect to your server.

	2.	In the the upper left corner click on File -> Open SQL Script

	3.	Navigate to the folder where you unzipped file named SQL Scripts 

	4.	Open folder DDL Queries and select DDL_Setup

	5.	In the Script window view, navigate to upper left corner and click on Execute
		(Execute - plain yellow lightning icon)

	6.	Open script directory (Repeat 2. and 3. step)

	7.	Open folder DML Queries and select DML_Setup

	8.	Execute the Script (Repeat 5. step)

	9.	Congratulation, the database has been set up.


USER GUIDE 	- 	This next section is for simulating adding a new course, finishing a course
			and creating profile with filled quiz. Finishing a course will link profile to
			course that is said to be finished.
		-	execute = repeat 2. and 3. step, open folder DMl_Queries and select script
			mentioned after

	-	To add a new course, execute DML_insert_NewCourse

	-	To add a new profile with quiz, execute DML_insert_NewProfileQuiz

	-	To finish a course, execute DML_insert_FinishedCourse


		-	This next section is for viewing courses, profiles and areas of interests
		-	execute = repeat 2. and 3. step, open folder DMl_Queries, open folder views
			and select script mentioned after
	
	-	To view all courses, execute DML_view_Courses

	-	To view all profiles, execute DML_view_Profile

	-	To view all profiles with Creative Area of interest, execute DML_view_Area_Creative

	-	To view all profiles with Development Area of interest, execute DML_view_Area_Development

	-	To view all profiles with Digital Marketing Area of interest, execute DML_view_Area_DigitalMarketing


LEGEND

	*	Videos are used with permission of the owner of YouTube Channel Amit Thinks.
		
		Name: 		Amit Diwan
		Designation:	Founder at Studyopedia and Amit Thinks YouTube Channel
		Studyopedia:	https://studyopedia.com/
		YouTube:	https://www.youtube.com/channel/UCgnr2Lkl1LZf0IOKRDAoJ2g
		Email: 		contact@studyopedia.com