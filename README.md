# Coq Platform moved to https://github.com/coq/platform

Dear Coq Platform user,

a while back Coq Platform became the recommended distribution of Coq. Since then the main git repo for Coq Platform is https://github.com/coq/platform.

This fork now only serves as private fork of MSoegtropIMC (the original author of Coq Platform).

If you cloned Coq Platform from here in the past, you might want to run these commands in your git repo:
```
git remote set-url origin https://github.com/coq/platform.git
OR
git remote set-url origin git@github.com:coq/platform.git
AND THEN
git fetch origin
AND POSSIBLY
git checkout main
git reset --hard origin/main
```
