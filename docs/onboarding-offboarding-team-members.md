# On-boarding & Off-boarding Infrastructure Team Members

How to onboard new Infrastructure team members, and remove their access if needs be.

This procedure can only be performed by a team lead. The reasoning for onboarding and offboarding is beyond the scope of this document,
although we will note that off-boarding can be performed for suspicious activity.

## On-boarding

1. Create a new Zoho email for the team member, with the name of their choosing. Aliases can be used. The password should be randomly generated and
shall be changed on first login.
2. Add the Zoho account to the "Infrastructure" department, and assign the "Cloudflare Access" application in Zoho Directory.
3. Send the email and password to the team member. Cleartext sharing is allowed.
4. Send a Cloudflare invite with the "Administrator" permission.
5. Send a BetterUptime invite.

## Off-boarding

The off-boarding is done in two steps, removing permissions and removing accounts. The first step doesn't require the second one to be performed.

### Removing permissions

Due to the sensitive access granted to team members, the following tasks will have to be performed immediately:

1. Remove access from Cloudflare
2. Unlink the "Cloudflare Access" application in Zoho Directory.
3. Disable the Zoho email.
4. Remove access from BetterUptime.

### Removing accounts

The accounts shall be removed no more than 7 days after the permissions have been removed. 

1. Reset the Zoho password.
2. Log into the Zoho email and transfer any email needing to be saved to a team lead account.
3. Delete the Zoho account.

---

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
