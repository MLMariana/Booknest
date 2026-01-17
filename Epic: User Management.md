Epic: User Management

User Story 1 – User Registration

As a new user
I want to create an account
So that I can access and interact with the Booknest library

Acceptance Criteria:

The user can register using:

Name

Email

Password

Email must be unique

Password must meet minimum security requirements

The system confirms successful registration

The user is redirected to the login page or logged in automatically

User Story 2 – User Login

As a registered user
I want to log into my account
So that I can access my personal features

Acceptance Criteria:

User can log in using email and password

Invalid credentials display an error message

Successful login redirects the user to the main library page

User session is maintained securely

User Story 3 – User Logout

As a logged-in user
I want to log out
So that my account remains secure when I stop using the app

Acceptance Criteria:

User can log out with a single action

Session is terminated

User is redirected to the login or home page

User Story 4 – View User Profile

As a user
I want to view my profile
So that I can see my personal information and activity

Acceptance Criteria:

User can view:

Name

Email

Joined date

Profile information is read-only by default

User Story 5 – Edit User Profile

As a user
I want to edit my profile information
So that I can keep my details up to date

Acceptance Criteria:

User can update name and password

Email cannot be changed (or requires verification)

Changes are saved successfully

Confirmation message is displayed

User Story 6 – User Permissions

As a system administrator
I want to manage user permissions
So that I can control access to sensitive actions

Acceptance Criteria:

Roles supported:

Admin

Regular User

Admin can:

Add, edit, or remove books

Manage users

Regular users can:

Browse books

Add reviews and comments

