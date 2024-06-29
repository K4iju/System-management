<h1>System Recovery</h1>



<h1>Boot into the Windows Recovery Environment</h1>

## Scenario
You are the IT administrator for a small corporate network. An employee has just called you saying that when they turn their laptop computer on, it comes up with a funny screen that they don't recognized.

# Lab Instructions

## Evaluating and Repairing the Exec-Laptop Computer

![alt text](image-6.png)

1. Boot the Exec-Laptop computer and evaluate the system.
    - Above the Exec-Laptop, select Top to view the power button.
    - Turn on the desktop computer by selecting the power button.
2. From the top right, select Answer Questions.
    - Answer Question 1.
    - Minimize the question window.
3. Determine which option would most likely fix the issue.
![alt text](image-7.png)
![alt text](image-8.png)
    - Select Advanced options.
    - Select Troubleshoot.
    - Select Advanced options.
    - Determine which option to use.
    - System restore - This would not fix the issue because it would take the user back to a previous restore point and not have access to any current data
    - Command prompt - You could start up from command prompt via startrep.exe, but it would be tedious
    - System image recover would not be a solution because it would lose current data
    - Start up repair - is the correct solution because it is boots the computer and repairs any system file corruptions
4. Use the applicable option to repair the computer.
![alt text](image-9.png)
    - Select Startup Repair.
    - Allow the computer to boot into Windows.
        - On a real computer, the Startup Repair option may take an hour or more.


<h1>Create a restore point</h1>



## Accessing System Protection Options

![alt text](image-49.png)

1. Right-click Start and then select Settings.
2. From the right pane, scroll to the bottom and select **About**.
3. Under **Device specifications**, in the Related links box, select **System protection**.

## Configuring System Protection Settings

### Configuring Local Disk (C:)

![alt text](image-50.png)

1. Make sure the **System Protection** tab is selected.
2. Select **Local Disk (C:)** and then select **Configure**.
3. Under **Restore Settings**, select **Turn on system protection**.
4. Under **Disk Space Usage**, adjust **Max Usage** to **5%** and then select **OK**.

### Configuring Data (D:)

![alt text](image-51.png)

1. Select **Data (D:)** and then select **Configure**.
2. Under **Restore Settings**, select **Turn on system protection**.
3. Under **Disk Space Usage**, adjust **Max Usage** to **7%** and then select **OK**.

## Creating a Restore Point
![alt text](image-52.png)
1. Select **Create** to create a restore point.
2. Enter a name of your choosing for the restore point and then select **Create**.
3. When prompted, select **Close** to acknowledge the completion of the restore point.
4. Select **OK** to close the **System Properties** dialog.
