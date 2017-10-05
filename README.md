# verbose-engine

# What?
* Public backup of my private sensitive passwords.
* I know, right?

# Why?
* Many passwords -> password file
* Password-file -> needs local (at-rest) encryption
* Password-file -> needs non-local replication
* Non-local copies -> versioning issues
* Versioning-issues -> needs a repository
* Repository -> needs further encryption for untrusted, public server storage.

# How?
* Put some passwords in an .org file
* Encrypt it with gpg locally
* Put that in a git repo
* Encrypt the repo with git-crypt
* Push to github
* See if you get hacked

# Who?
* Me
* Anyone willing to look for a flaw in the flow

# Where?
* Here for now

# When?
* Always 5 minutes ago

# But that's Anarchy?!
* NAP or GTFO
