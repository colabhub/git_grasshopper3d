# Working in grasshopper3d in team

We're writing here some sample defitions in order to experiment and propose ways to work colaborativly with grasshopper definitions in teams

Feel free to help, change, ask and suggest

## checkout commits

Creating commits is possible to checkout them and work with both gh and ghx files on the current chechout

```git
git log
```

You'll give the following result


```
commit 8fba8a2db92226c3feb30741ca4204e5df3174db
Author: Fernando Gomes <fernando_gomes@me.com>
Date:   Tue Oct 4 17:05:25 2016 -0300

    Some updates

commit ebf26b97996eec7c37db31a3b76025e1a65d8c0b
Author: Fernando Gomes <fernando_gomes@me.com>
Date:   Tue Oct 4 16:58:00 2016 -0300

    first commit
```

Then, you can change between the commits, for exemple, copyng the "first commit" chechout id

```
git checkout ebf26b97996eec7c37db31a3b76025e1a65d8c0b
```

And now we can open the file, both gh and ghx and

```
Note: checking out 'ebf26b97996eec7c37db31a3b76025e1a65d8c0b'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at ebf26b9... first commit
```

## TODOs

- Create and new branchs and sbmit pull requests
- Plan a tool as a componet inside grasshopper3d in order switch branchs and commits