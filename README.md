# Rails Bug 05

## Setup

* `bundle`
* `rake db:create db:migrate db:seed`
* `rails s`

You can run specs with:

* `rspec`

Note: email/password combinations for existing users populated by `rake db:seed` can be found in the db/seeds.rb file.

## Stories

### I'm pulling my hair out!!!

<img src="http://bracketgeek.com/system/avatars/451/original/RageFaceBlackSS.png" />

**You can only edit _certain_ tasks**
```
OK, bear with me here.

As a user, when I login, I can edit the first task that is there.
If I add a new task, it works fine.
If I try to edit the new task I created, IT UPDATES THE OTHER TASK!!
Every time I add a new task, then update it, the updates are applied to the original task

HELP!
```
