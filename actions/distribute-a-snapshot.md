---
description: >-
  By distributing objects (files, tables, or applications) to another instance,
  the objects being distributed will be added and merged with the content of the
  current state of the target instance.
---

# Distribute objects

![](../.gitbook/assets/info_simple.svg.png)DataHub allows you to distribute the entire contents of your current state or a snapshot, otherwise you can distribute a few selected objects.

![](../.gitbook/assets/info_simple.svg.png)Whether you choose to distribute the entire contents of a snapshot \(or current state\) or selected objects, a backup snapshot of the current state of the target instance will automatically be created before the merge.

![](../.gitbook/assets/info_simple.svg.png)After the distribution request is submitted, the operation will start in the backend and upon completion, you will receive a summary email detailing the outcome.

## **There are two options to distribute objects:**

### **- Option 1: Distribute all/selected objects to existing instances.**

![](../.gitbook/assets/info_simple.svg.png)**This option assumes that the instances with which you want to share the objects exist already.**

1. Navigate to the instance view where the list of mutable and immutable states are displayed.This can be done by clicking on level 3 \(Instance\) from the side bar, or by selecting an organization from the dashboard, then a space, and then an instance. 
2. Click OPEN CURRENT STATE or select one of the snapshots listed under Immutable States. 
3. If you want to distribute specific files, then from the file list select all files and click the STAGE button from the menu above. There are three types of files you can select, workplace, personal, and application files. Only one type of files can be added to stage at a time. 
4. If you want to distribute everything in your current state/snapshot, then go to step 5. 
5. From the sidebar on the left, click on DISTRIBUTE OBJECTS. 
6. Choose whether you want to distribute the staged files or everything. 
7. Select the target organization and space from which to choose your target instances. 
8. Select whether you want to distribute with specific instances or all instances in the selected space. 
9. Select the distribution strategy for each of the three file types. The options are:  - Distribute extra objects \(files and tables\) compared to target **\[TAMAS\]** - Distribute all objects \(overwrite target\) **\[TAMAS\]** - Clean and replace target **\[TAMAS\]** 
10. Click on the **DISTRIBUTE**  button at the bottom. 

### **- Option 2: Distribute all objects to new instances.**

![](../.gitbook/assets/info_simple.svg.png)**With** t**his option, you can only distribute the entire content of your current state/snapshot. For the Current State, this option will be available only if you haven't shared any full snapshot of the current state with other instance in your current space. For immutable states, the option is always available.**

1. Navigate to the instance view where the list of snapshots within an instance is visible. This can be done by clicking on level 3 \(Instance\) from the side bar. 
2. Click either on OPEN CURRENT STATE or select one of the snapshots under immutable states. 
3. According to your choice in step 2, you would see either of two options:

* If your choice was CURRENT STATE, then at the top of the page you will see the following banner and you have to click on INVITE AND SHARE STATE.

![](../.gitbook/assets/distribute.png)

Starting from the CURRENT STATE, this will take you through a two-step operation where you first create a snapshot, and then you create one or more instances. First you need to provide a name and description of the snapshot, as well as a description of the next work phase. The next work phase description will be used to update the description of the current state. If no work is expected in the near future, tick the "No work is expected in the next stage" button. Once you create a snapshot, then you will be asked to choose the instance creation method and provide the necessary information\(see [here](create-an-instance.md) for details\).

* If instead your choice was an immutable snapshot, then at the top of the page you will see the following banner and you have to click on CREATE INSTANCE.

![](../.gitbook/assets/current_state.png)

In this case, all you need to do is to choose the instance creation method and provide the necessary information \(see [here](create-an-instance.md) for details\).

#### 

#### ![](../.gitbook/assets/info_simple.svg.png)If you are encountering a problem distributing a snapshot, refer to the troubleshooting guide [here](../troubleshooting/authorization-issues/i-cant-distribute-a-snapshot.md). 

\*\*\*\*

## 

![This chart illustrates the process of snapshot distribution. A professor is the editor of the Master instance and they have one snapshot \(Snapshot 1\) taken at some point in time. Assume that the professor decides to distribute their snapshot to student 1. Once this snapshot has been distributed, the current state of student 1 will now contain the files, tables, and applications created by the student \(in white\) as well as the files and tables shared by the professor \(in yellow\). A copy of the snapshot distributed by the professor gets automatically stored in the Distributed instance.](../.gitbook/assets/copy-of-datahub-architecture-main-architecture-2.svg)



