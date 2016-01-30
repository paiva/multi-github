# Multi Github

Here is the situation: I want to be able to use one username to push code to my personal account and another username to push code to my
work account. This adds a layer of structure to my work environment and it also help simplify my projects. Oranges with oranges, apples with apples. 

There is only way problem with this approach: commit streaks. I you care about your commit strakes and the yearly number of contributions then you, 
then this might not be a good solution as the yearly contribution will splitted among two accounts. 

### Getting Started

First off all, let's assume that your personal Github username is @personal and that your work username is @work. We want to set up a system
such that you can clone, pull, push, and commit to your different projects both for personal and work stuff. It would be assumed, that your 
@personal account is already set up and that you are able to push/pull code without any more. The complexity layer when now want to add is 
the integration of the @work account. 

Step 1: Create your @work account
Step 2: Create a different ssh key for your @work account and name it id_rsa_work.
    $ ssh-keygen -t rsa -C "you@workemail.com"

After completing Step 2, you should have 2 keys generated:

    id_rsa  id_rsa_work  id_rsa_work.pub  id_rsa.pub  known_hosts




