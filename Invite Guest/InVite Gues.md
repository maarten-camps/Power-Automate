## Invite Guest 

makes it possible to invite a guest via a HTTP request. this requires the HTTP connector in Power Automate.

Method: Post 
URI: https://graph.microsoft.com/v1.0/invitations

Body: 
{
  "invitedUserEmailAddress": "ADD VARIABLE EMAIL T INVITE,
  "invitedUserDisplayName": "ADD NAME WHICH Shoudl APPEAR IN ENTRA",
  "SendinvitationMessage": true,
  "inviteRedirectUrl": "ADD REDIRECT URL AFTER SUCCESFULL ACCEPING THE INVITE"
}

Requires a App Registration which has the 
Permission: User.invite.all