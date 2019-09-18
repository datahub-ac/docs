# Setting up a class

DataHub is an ideal solution for conducting educational activities such as teaching a university class, offering a summer school, organizing hands-on sessions, giving interactive presentations, and other academic training programs.

Classes with a substantial empirical or data-driven component often involve operations such as the collection, preparation and sharing of data, files, assignments and solutions between teachers and students, the installation and configuration of computational tools on various operating systems, the writing, execution, and sharing of code, and finally the production and re-production of analytical results. The more students a class has, the more it will result challenging to organize all these processes reliably and efficiently.

In this tutorial, you will learn how to set up a class with several students and manage the storing and sharing of different versions of files, data, and applications.

## Step 1: Create a space for the class.

To start a class, you have to create a space for it. Before creating a space, you have to select the organization where you want the class to be offered. Once you log in to DataHub, a dashboard will be displayed where you can see all the organizations of which you are a member. From the dashboard, you can select the organization you want to work in. Once you have chosen the organization, create a space for your class following the steps described [here](../actions/create-a-space.md).

## Step 2: Upload files to your instance.

To teach your class, you will need to have files and data that you want to upload to your work environment. To upload files, you should open the current state of your master instance. You can go to the current state by selecting your space, search for the master instance, and below the master instance you will find a button called CURRENT STATE which will take you to the file list where you can upload new files. Alternatively, you can click on the Master instance and you can use the button called OPEN CURRENT STATE. Finally, to upload files, follow the steps [here](../actions/upload-new-files.md).

## Step 3: Start a new application.

To work with your files, you will need to create and start an application. Say for example that you want to read a CSV file in Python. To do so, you first have to upload the CSV file to your current state following step 2. After that, you will need to create an application. Steps for creating an application are explained in detail [here](../actions/create-an-application.md). Once you have created an application, make sure that you are still working in the current state, and then follow the steps illustrated [here](../actions/start-an-application.md) for working with your file.

## Step 4: Invite students to join the class.

To add students to your class, you need to send an invitation to each student to join the space you have created in DataHub. As a space admin, you will be assigned a _Master_ instance which you will use to interact with your students. Students instead will be invited to join DataHub, and a separate instance will be created for each student. To invite students, you first have to collect their email addresses to which you want to send the invitation.   
  
Once you have collected the student emails, then you have to decide between creating an empty instance for each student, meaning that they will not have files in their work environment when they join DataHub, or you can share files with the instances to be created for each student. To invite students with one of these two options, follow the steps detailed [here](../actions/create-an-instance.md).

## Step 5: Share updates with the students.

If you want to to share a _new file_ \(e.g. assignment, homework,...\) with one or more students, then you need to first upload the file\(s\) to your current state \(step 2\) , then create a snapshot of your current state, and finally distribute the snapshot to  the instances of the students you want to share the files with.   
To do so, upload the files first and then click on DISTRIBUTE CURRENT STATE button which you see at the top of the page next to Current State. Clicking on this button will take you in a two-step operation where you first create a snapshot, then distribute it with the students. For more details on how to distribute a snapshot, read more [here](../actions/distribute-a-snapshot.md).

## Step 6: Check students\` progress.

You can ask your students to make snapshots of their work to meet certain deadlines \(e.g for an assignment\). The snapshot will become immutable and unaffected by later work of the students.

As the instructor, it is then possible to open the students\` instances and check the saved work states \(and whether they were saved on-time\) and provide feedback to the students.
