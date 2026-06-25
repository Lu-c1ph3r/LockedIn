# Brute Force Investigation

## Situation

Investigation into a sequence of failed logins followed by a successful authentication.

## Observation
- Four failed logins
- one successful login 
- password changed 
- added to domain admins
- large file download 

## assessment

Potential account compromise
Further investigation required before confirmation 

## risk
High

## Recommended actions

- investigate the source ip
- review login location
- verify password change
- examine downloaded files
]
## lesson learnt
- multiple IOCs together increase confidence that a suspicious activity may have occured. 
 
## Timeline
00:41 Failed Login

00:42 Failed Login

00:43 Failed Login

00:44 Failed Login

00:45 Successful Login

00:46 Password Changed

00:47 Added to Domain Admins

00:49 15GB Download

00:50 Logoff

## Indicators of Attack (IOA)

- Multiple failed logins
- Possible password guessing

## Indicators of Compromise (IOC)

- Successful login after repeated failures
- Password changed
- Added to Domain Admins
- Large file download

## Additional Evidence Needed
- Source IP
- Login location
- Device used
- Previous user behaviour
- File contents
