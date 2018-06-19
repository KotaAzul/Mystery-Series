# Mystery-Series
This project contains the third experimental series to test the use of Git for shared tracing projects.

## Invitation
Every member of the Reconstruct team is encouraged to clone this repository and trace objects according to the "Process" described below.

## Process

* Step 1: **Clone** this project (**git clone https://github.com/KotaAzul/Mystery-Series.git**).

* Step 2: **Pull** from GitHub to your local directory (**git pull origin master**). This will ensure you have the most up to date version, including the traces of whoever worked on the series before you. [You will not have to do this immediately after cloning but you should make a pull before you plan to do any work on a series.]

* Step 3: **Claim** the series by checking it out like a library book. In your local directory or by editing through your browser change the README **Series Status** from "Available" to "Checked Out!" along with your name. [**NOTE**: If you do this locally, you will have to commit and push that change to the master before anybody else on the webpage will see that it is indeed checked out]

* Step 4: **Work** on the series. Trace some shaft and associated spines of dendrites d01 or d02.

* Step 5: **Commit** your changes locally (**git commit -a** or similar alternatives). 

* Step 6: **Finalize** your work by editing your local README file. Change the **Series Status** back to "Available" and add an entry into the **Section Log**. Commit this change locally as well.

* Step 7: **Push** all of your changes to GitHub (**git push origin master**).

* Step 8: **Go back** to Step 2 whenever you plan to work on the series again.

## Series Status
You can also add emojis to better indicate availability. Just add either heavy_check_mark :heavy_check_mark: or no_entry_sign :no_entry_sign: contained within two : marks when editing the README.  

* Available :heavy_check_mark:
<!--- * Checked Out! :no_entry_sign: (Bob) --->

## Series Log
Keep track of your additions or changes to the series with a simple log entry.

* 06.09.2018 Bob First use of Java Reconstruct for RGB_100 and RGB_010 on ss 46,47
* 06.08.2018 DDH traced d02 on s1-10
* 06.08.2018 Bob traced bob001? over ss 48-50
* 06.08.2018 DCH traced d01 over ss 1-10
* 06.07.2018 DCH uploaded series repository.

## Discussion

This is our third experiment in building a collaborative tracing environment using GitHub. We are modifying the protocol slightly to include checking out the series as a whole each time someone wants to work on it. This is similar to the normal workflow of the lab. One of the main issues we have encountered is when two separate tracers make different changes on the same sections at the same time. **It is extremely important that you check the Series Status and make a pull before doing any work on a series!!!!** 

This next phase is also a chance to get more people involved and up to speed with the basics of this versioning system. In the future, we hope to be able to use pyRecon or other tools to more easily merge .xml file changes, which could open up the possibility for real simultaneous tracing. In the meantime, if users do need to make traces on a series at the same time, they will have to "check out" specific sections to work on. This will lock any other tracers out of making changes to those sections, which is certainly restictive, but it is the best methology we have for that situation at this time. 


## Animation
This section will be periodically updated to show 3D renderings of tracing progress.

### d01
![d01_initial](animations/d01_initial.gif?raw=true "d01_initial")

### d02
![d02_initial](animations/d02_initial.gif?raw=true "d02_initial")
