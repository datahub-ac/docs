# Distribute objects in Nuvolos

Object distribution is a building-block feature of Nuvolos. The key concept to remember is that distribution is a _push-_type operation, you have to initiate it from the source and you send to the specified target. Consequently, you need **EDITOR** access on the target instance you want to write to.

The following type of objects \(or a combination of these\) can be distributed:

* Files, sets of files, or entire directories,
* tables or sets of tables,
* applications or sets of applications,
* or entire snapshots.



## Distributing a selected list of items: a worked example

You can distribute a set of items from a single instance using the **stage** feature of Nuvolos.

Let us assume that you want to distribute a file and an application in the following example. In order to do this, the following steps need to be done:

1. Select the file you want to stage and either click **STAGE** or click **STAGE SELECTED** on the following screen:

![Staging a file called example.R](../../.gitbook/assets/screen-shot-2019-12-09-at-10.36.28.png)

     2. Select the application you want to stage by navigating to the application list and staging the appropriate one:

![Staging an application](../../.gitbook/assets/screen-shot-2019-12-09-at-10.36.53.png)

     3. Navigate to the stage area to begin distribution, then click **START**.

![Clicking the distribution button takes you to the initial step of the distribution process.](../../.gitbook/assets/screen-shot-2019-12-09-at-17.51.36.png)

    4. Observe your current set of staged objects. If everything checks out, click **CONTINUE**.   
In our particular example, we have one file and one application \(as selected previously\) in the stage. Using the red cross button, items can be purged from the stage.

![](../../.gitbook/assets/screen-shot-2019-12-09-at-17.55.50.png)



5. The next step selects the target for distribution. It is possible to remain in the current research context,  or distribute into some other space or even organization. In the example, we select a space in the same organization. You can also choose whether to share with all collaborators or just one - this will decide whether you send the selected objects to one instance or all instances. Once you are done finding the target, click **CONTINUE**.

![](../../.gitbook/assets/screen-shot-2019-12-09-at-18.12.25.png)

6. The next steps selects the distribution strategy - more details can be found [here](distribution-strategies.md). For now, we will select overwrite, which will overwrite objects of the same name in the target. 

{% hint style="success" %}
Please note that whenever you distribute, in the target a snapshot gets created, so you should not be concerned about data loss.
{% endhint %}

 Once done, click **CONTINUE.**

![](../../.gitbook/assets/screen-shot-2019-12-09-at-18.14.22.png)

7. Finally, you can send a message along with the distribution to notify the users in the targets about the change being made. In this particular case, we decided _not_ to notify users by emptying the checkbox.

![](../../.gitbook/assets/screen-shot-2019-12-09-at-18.16.36.png)

Once you are done, click **SHARE OBJECTS** and you are done.

