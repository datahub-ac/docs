# Distribute a snapshot

* By distributing a snapshot to another instance, the content of the snapshot being distributed will be added and merged with the content of the current state of the target instance. A backup snapshot of the current state of the target instance will automatically be created before the merge. DataHub allows to distribute an existing snapshot, or create a snapshot from the current state and then distribute it to other instances. 
* Upon a successful completion of the operation, a REVIEW button will be available for each of the distributed instances. Clicking on one of the REVIEW buttons, the browser will be redirected to the snapshot view of the associated instance, where you the files, tables and applications will be visible. 

## **There are two options to distribute a snapshot:**

## **Distribute an existing snapshot**

1. Navigate to the **instance view** where the list of snapshots within an instance is visible. This can be done by clicking on level 3 \(Instance\) from the side bar. 
2. From the table of snapshots, choose the snapshot to be distributed and in the corresponding row for that snapshot click on the blue icon contained in the column Distribute. 
3. Alternatively, click on the name of the snapshot in the same table which will illustrate a blue alert message with a button called **DISTRIBUTE SNAPSHOT:** click on that button. 
4. The browser will be redirected to a view where the possible target instances will be listed.  
5. Select the target instances to which you want distribute the snapshot. 
6. Decide whether to distribute _only files_ or _files and packages_ by ticking the **Distribute only files** field. Distributing only files is faster, however in case new packages were installed, these will be not pushed to the target instances. This might result in some applications showing different behaviour in the source and target instances. 
7. Click on the **DISTRIBUTE SNAPSHOT** button at the bottom. 

## **Create and distribute a snapshot**

1. Navigate to the instance view where the list of snapshots within an instance is visible. This can be done by clicking on level 3 \(Instance\) from the side bar. 
2. Click on **WORK IN \[INSTANCE NAME\] INSTANCE** button. 
3. There is a multi-option button in the top toolbar. Select **Create and Distribute Snapshot** and click on the button. 
4. Provide a description of the new snapshot. Notice that there is an automatic suggestion that is the description of the current state. 
5. Provide a description of the next work phase: this will be used to update the description of the current state. If no work is expected in the near future, tick the "No work is expected in the next stage" button. 
6. Click on the **Add Snapshot** button. 
7. The browser will be redirected to a view where the target instances to distribute the snapshot to can be selected. 
8. Select the target instances to distribute the snapshot to. 
9. Decide whether to distribute _only files_ or _files and packages_ by ticking the **Distribute only files** field. Distributing only files is faster, however in case new packages were installed, these will be not pushed to the target instances. This might result in some applications showing different behaviour in the source and target instances.

10. Click on the **DISTRIBUTE SNAPSHOT** button at the bottom.



#### If you are encountering a problem distributing a snapshot, refer to the troubleshooting guide [here](../troubleshooting/authorization-issues/i-cant-distribute-a-snapshot.md). 

\*\*\*\*

## 

![This chart illustrates the process of snapshot distribution. A professor is the editor of the Master instance and they have one snapshot \(Snapshot 1\) taken at some point in time. Assume that the professor decides to distribute their snapshot to student 1. Once this snapshot has been distributed, the current state of student 1 will now contain the files, tables, and applications created by the student \(in white\) as well as the files and tables shared by the professor \(in yellow\). A copy of the snapshot distributed by the professor gets automatically stored in the Distributed instance.](../.gitbook/assets/copy-of-datahub-architecture-main-architecture-2.svg)



