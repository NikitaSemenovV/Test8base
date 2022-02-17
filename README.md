8base test-task

Wishes and comments
1. Create a video instruction, since at the moment people perceive video information better than text information
2. Describe step 3.4 in more detail
3. Write what OS is used in the instructions. Used by Linux, this can confuse most users
Сheck-list
OC: Windows 10 1909 (64-bit)
Date: 02/16/22 – 02/18/22
Author: Semenov Nikita
ID	Description	Result	Comments
1	Start an 8base Account	Positive	
2	creating a simple table	Positive	
3	establish relationships between tables	Positive	
4	adding records using mutations	Negative	
5	adding entries manually	Positive	
6	Roles and Permissions	Positive	
7	Authentication Profiles	Positive	
8	Getting the Workspace API Endpoint	Positive	
9	Create a directory	Positive	In the command line example, there is no mention of OC being used (For Windows it is not true)
10	Install the 8base CLI and Authenticate	Positive	
11	Deploy a Serverless Function	Positive	Since I used Windows, I had to correct the example (8base init . --functions=resolver:myCustomResolver cmd does not accept .)
12	Choose a Starter App / Framework for the Frontend	Positive	The check-out Framework Vue and Framework React
13	Setting up the client	Positive	Create more detailed instructions (where/how to find)
14	Application launch	Positive	
15	create multiple branches	Positive	
16	implement a cycle of making changes to the Master using the mechanism for generating and committing migrations	Positive	
 
Bug-report

Project: 8base Quick Start
Component: https://docs.8base.com/docs/getting-started/quick-start/
OC: Windows 10 1909 (64-bit)
Date: 02/16/22 – 02/18/22
Author: Semenov Nikita
Status: New
ID	Description	Steps	Actual result	Expected Result	Severity	Priority
1	Error in description 2.1. Building a Data Model	1.	Go to site: https://docs.8base.com/docs/getting-started/quick-start/
2.	Go down a step: 2.1. Building a Data Model
3.	See description	 	 

	Minor	Medium
2	Mouse stuck when copying commands	1.	Go to site: https://docs.8base.com/docs/getting-started/quick-start/
2.	We look at the description with examples from the command line.
3.	Trying to copy commands	Mouse stuck when selecting a command	The mouse should not get stuck when highlighting commands	Minor	Low
3	The example of the given mutation outputs errors	1.	Go to site: https://docs.8base.com/docs/getting-started/quick-start/
2.	Go down a step: 2.1. Building a Data Model
3.	We execute the instruction (API Explorer)	{
  "errors": [
    {
      "message": "Expected value of type \"User_NoteCreateInput\", found [{title: \"New favorite food\", body: \"My new favorite food is the impossible burger\"}, {title: \"This weeks todos\", body: \"Buy milk, cookies, and walk the dog.\"}].",
      "locations": [
        {
          "line": 2,
          "column": 82
        }
      ]
    },
    {
      "message": "Cannot query field \"count\" on type \"Note\".",
      "locations": [
        {
          "line": 4,
          "column": 7
        }
      ]
    }
  ]
}	The mutation should work from the example	Critical	Hith

Test results: 3 bugs were found. Recommendations were given to improve the page Quick Start.

