# config
CodeLingo config files

Feel free to add new files for new purposes.

Prefer *not* to reuse files for new purposes.

Always add an explanation of what your file is for.

## Files

### adminAccessRepos.json

List of `{owner, name}` objects identifying repos we always want CodeLingo employees to
have access to, whether or not the repos have CodeLingo installed.

### privateRepoUsers.json

List of `owner` strings for whom we will (1) show private repos in the dashboard and
(2) attempt to run reviews against private repos. (Note that those reviews won't *work*
just because they're on this list; we'd also need them to add the bot as a contributor.)

### supportAdminAccounts.json

List of `owner` strings identifying groups of repos where we always want CodeLingo
employees to have access, so long as the repos have CodeLingo installed.

### priorityUsers.json

List of `owner` strings identifying users where we always want to be pinged on
slack about there activity.
