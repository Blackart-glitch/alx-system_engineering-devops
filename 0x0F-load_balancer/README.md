## Load balancer
## Web stack debugging

### Background Context
You have been given 2 additional servers:
```
gc-[STUDENT_ID]-web-02-XXXXXXXXXX
gc-[STUDENT_ID]-lb-01-XXXXXXXXXX
```

we're improve our web stack so that there is redundancy for our web servers. This will allow us to be able to accept more traffic by doubling the number of web servers, and to make our infrastructure more reliable. If one web server fails, we will still have a second one to handle requests.

### Resources
Read or watch:
[Introduction to load-balancing and HAproxy](https://intranet.alxswe.com/rltoken/B7f3oz8i3Xvvom_YQZzLnQ)
[HTTP header](https://intranet.alxswe.com/rltoken/sZ9v3Vq2tgLwN_PWVQketw)
[Debian/Ubuntu HAProxy packages](https://intranet.alxswe.com/rltoken/2VRAgtKKR9g6Xfb0xzGiSg)

## Requirements
General
- Allowed editors: vi, vim, emacs
- All files will be interpreted on Ubuntu 16.04 LTS
- All files should end with a new line
- A README.md file, at the root of the folder of the project
- All your Bash script files must be executable
- The first line of all Bash scripts should be exactly #!/usr/bin/env bash
- The second line of the Bash scripts should be a comment explaining what is the script doing

### Author
Daniel Ajiboye [linkedIn](https://www.linkedin.com/in/daniel-boy%C3%A9-58366a1b4/)