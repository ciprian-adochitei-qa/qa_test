# qa-test
Just a repository for testing purposes

* Before you start, request access to this git repo. You'll be added as a collaborator.

* PRIMARY GOALS
  * Clone the repository locally.
  * Create a working branch that will hold your work.
  * Create a plain old text file in a separate directory called "cron" containing a crontab that should schedule a QA job, in the CI tool of your choice, to run weekly, every Wednesday and Friday at 1:00 AM.
  * Initialize a SerenityBDD maven project inside the repository using the method of your choice. The project should build whithout any maven failures.
  * Create a file containing a **Page Object** of the https://www.arnia.com **/contact** page. 
    * *This can be done in any programming language you're familiar with or even pseudocode. It isn't meant to work, just prove the concept.*
  * Create a file containing a functional test for the https://www.arnia.com **/contact** page. The test should:
    * Identify the **Name**, **Email**, **Phone** and **Project** fileds.
    * Fill the identified fields with some test data (valid).
    * Tick the *"I'm not a robot"* checkbox.
    * Click the Send button.
    * *The test can be written in any programming language you're familiar with or even pseudocode. It isn't meant to work, just prove the concept.*
  * Commit and push your work to the git repository and create a pull-request that will be assigned to **ciprian-adochitei-qa**

* STRETCH GOALS
  * Implement the mock test files into the Serenity project you initialized.

* Delivery time is 4h max.

Good luck!