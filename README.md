Create a command-line application that dynamically generates a PDF profile from a GitHub username. The application will be invoked with the following command:
node index.js
The user will be prompted for a favorite color, which will be used as the background color for cards.
The PDF will be populated with the following:

Profile image
user name
Links to the following:

User location via Google Maps
User GitHub profile
User blog


User bio
Number of public repositories
Number of followers
Number of GitHub stars
Number of users following

Refer to the design mockup.

User Story
AS A product manager
I WANT a developer profile generator
SO THAT I can easily prepare reports for stakeholders

Business Context
When preparing a report for stakeholders, it is important to have up-to-date information about members of the development team. Rather than navigating to each team member's GitHub profile, a command-line application will allow for quick and easy generation of profiles in PDF format.

Acceptance Criteria
GIVEN the developer has a GitHub profile
WHEN prompted for the developer's GitHub username and favorite color
THEN a PDF profile is generated


Commit Early and Often
One of the most important skills to master as a web developer is version control. Building the habit of committing via Git is important for two reasons:


Your commit history is a signal to employers that you are actively working on projects and learning new skills.


Your commit history allows you to revert your code base in the event that you need to return to a previous state.


Follow these guidelines for committing:


Make single-purpose commits for related changes to ensure a clean, manageable history. If you are fixing two issues, make two commits.


Write descriptive, meaningful commit messages so that you and anyone else looking at your repository can easily understand its history.


Don't commit half-done work, for the sake of your collaborators (and your future self!).


Test your application before you commit to ensure functionality at every step in the development process.


We would like you to have more than 200 commits by graduation, so commit early and often!

Submission on BCS
You are required to submit the following:


An animated GIF demonstrating the app functionality


A generated PDF of your GitHub profile


The URL of the GitHub repository


