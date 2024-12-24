## SRS

### 1. User Account Management

#### R.1.1 Link Account for Particular Game

- Description : User can link their gaming account with the platform for a particular game available.
- Input:- User's gaming account UserName.
- Output:- Success message if the account is linked successfully.

#### R.1.2 Fetch Game Stats

- Description :- Fetch Current Game Stats of the user for Linked Gaming account.
- Input:- Click on Fetch Stats Button.
- Output:- Display the Current Game Stats of the user.

#### R.1.3 Update Game Account

- Description :- User can update their linked gaming account.
- Input :- Authentication for the account update and new username.
- Output :- Success message if the account is updated successfully.

#### R.1.4 Remove Game Account

- Description :- User can remove their linked gaming account after Authentication.
- Input :- Authentication for the account removal.
- Output :- Success message if the account is removed successfully.

#### R.1.5 Update Profile Details

- Description :- User can update their profile details.
- Input :- New Profile Details.
- Output :- Success message if the profile is updated successfully.

### 2. Organization Profile Management

#### R.2.1 Create Event

- Description :- Organization can create an event.
- Input :- Event Details with Privacy Settings.
- Output :- Success message if the event is created successfully and listed in Event Page.
- Constraints :- Event Date should be in the future.

#### R.2.2 Past Event

- Description :- Organization can view past events.
- Input :- Click on Past Event Button.
- Output :- Display the list of past events hosted by Organization.

#### R.2.3 Update Organization Details

- Description :- Organization can update their profile details.
- Input :- New Profile Details.
- Output :- Success message if the profile is updated successfully.

#### R.2.4 Delete Organization

- Description :- Organization can delete their profile.
- Input :- Authentication for the profile deletion.
- Output :- Redirect to the Home Page with Success Message.

#### R.2.5 Update Event Details

- Description :- Organization can update the event details.
- Input :- Changes in Event Details.
- Output:- Changes refleced in the Event Page with success message.
- Constraints :- Event Data should be for the future event.

#### R.2.6 Event Analytics

- Description :- Organization can view the analytics of the event.
- Input :- Click on Event Analytics Button with number of past events.
- Output :- Display the analytics of the event.
