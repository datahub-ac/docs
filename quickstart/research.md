# Setting up a research project

Research projects are often group projects with complex and recurring interactions involving the collection, cleaning, and storage of data, the sharing of data between researchers, the sharing of different versions of code and files, the production and re-production or results, and the exchange of feedback.

DataHub offers an efficient and organized solution for conducting research projects that aim to maximize both research velocity and reproducibility. Different versions of work \(files, data, and applications\) can be packaged together, shared easily with other colleagues who can run the analysis and reproduce the same results. New results can be related to past outcomes with confidence as different components of the research process \(data vintage, pre-processing, analysis approach\) can be separately altered whilst keeping other components fixed. All of these steps are done within DataHub platform.

In this tutorial, you will learn how to set up a research project with multiple collaborators and manage the storing and sharing of different versions of work.

## Step 1: Create a space for the research project.

To start a research, you have to create a space for it. Before creating a space, you have to select the organization where you want the research project to be hosted. Once you log in to DataHub, a dashboard will be displayed where you can see all the organizations of which you are a member. From the dashboard, you can select the organization you want to create the research project in. Once you have chosen the organization, create a space for your project following the steps described [here](../actions/create-a-space.md).

## Step 2: Upload files to your instance.

To start working on your research project, you will need to have files and data that you want to upload to your work environment. To upload files, you should open the current state of your master instance. You can go to the current state by selecting your space, search for the master instance, and below the master instance you will find a button called CURRENT STATE which will take you to the file list where you can upload new files. Alternatively, you can click on the master instance and you can use the button called OPEN CURRENT STATE. Finally, to upload files, follow the steps [here](../actions/upload-new-files.md).

## Step 3: Start a new application.

To work with your files, you will need to create and start an application. Say for example that you want to read a CSV file in Python. To do so, you first have to upload the CSV file to your current state following step 2. After that, you will need to create an application. Steps for creating an application are explained in detail [here](../actions/create-an-application.md). Once you have created an application, make sure that you are still working in the current state, and then follow the steps illustrated [here](../actions/start-an-application.md) for working with your file.

## Step 4: Invite researchers to join the research project.

To add researcher to your project, you need to send an invitation to each researcher to join the space you have created in DataHub. As a space admin, you will be assigned a _Master_ instance which you will use to interact with your collaborators. Collaborators instead will be invited to join DataHub, and a separate instance will be created for each collaborator. 

To invite collaborators, you first have to collect their email addresses to which you want to send the invitation. Once you have collected the student emails, then you have to decide between creating an empty instance for each student, meaning that they will not have files in their work environment when they join DataHub, or you can share files with the instances to be created for each collaborator. To invite collaborators with one of these two options, follow the steps detailed [here](../actions/create-an-instance.md).

## Step 5: Share updates with your collaborators.

If you want to to share a _new file_ \(e.g. assignment, homework,...\) with one or more students, then you need to first upload the file\(s\) to your current state \(step 2\) , then create a snapshot of your current state, and finally distribute the snapshot to  the instances of the students you want to share the files with.   
To do so, upload the files first and then click on DISTRIBUTE CURRENT STATE button which you see at the top of the page next to Current State. Clicking on this button will take you in a two-step operation where you first create a snapshot, then distribute it with the students. For more details on how to distribute a snapshot, read more [here](../actions/distribute-a-snapshot.md).

## Step 6: Check and reproduce your collaborators\` results.

You can ask your collaborators to make snapshots of their work to see and give feedback on their results. The snapshot will become immutable and unaffected by later work of the collaborators. This will give researchers the advantage of tractability and reproducibility of their results. To reproduce the research results obtained at a specific point in time, the researcher can [restore](../actions/restore-a-snapshot.md) the snapshotted state and run the analysis again.



