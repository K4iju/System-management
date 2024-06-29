<h1>System Recovery</h1>



<h1>Boot into the Windows Recovery Environment</h1>

## Scenario
You are the IT administrator for a small corporate network. An employee has just called you saying that when they turn their laptop computer on, it comes up with a funny screen that they don't recognized.

# Lab Instructions

## Evaluating and Repairing the Exec-Laptop Computer

![image](https://github.com/K4iju/System-management/assets/159083256/2c14ddd1-c420-4de6-abe0-40d8eed76903)


1. Boot the Exec-Laptop computer and evaluate the system.
    - Above the Exec-Laptop, select Top to view the power button.
    - Turn on the desktop computer by selecting the power button.
2. From the top right, select Answer Questions.
    - Answer Question 1.
    - Minimize the question window.
3. Determine which option would most likely fix the issue.
![image](https://github.com/K4iju/System-management/assets/159083256/b7fea4f9-1e4c-4023-9c3d-ef2b523ef62f)

![image](https://github.com/K4iju/System-management/assets/159083256/971a4331-508a-4e1e-bc65-c15ea9f42986)

    - Select Advanced options.
    - Select Troubleshoot.
    - Select Advanced options.
    - Determine which option to use.
    - System restore - This would not fix the issue because it would take the user back to a previous restore point and not have access to any current data
    - Command prompt - You could start up from command prompt via startrep.exe, but it would be tedious
    - System image recover would not be a solution because it would lose current data
    - Start up repair - is the correct solution because it is boots the computer and repairs any system file corruptions
4. Use the applicable option to repair the computer.
![image](https://github.com/K4iju/System-management/assets/159083256/edc8554f-a6cf-4858-ad2b-158fb90fa38a)

    - Select Startup Repair.
    - Allow the computer to boot into Windows.
        - On a real computer, the Startup Repair option may take an hour or more.


<h1>Create a restore point</h1>



## Accessing System Protection Options

![image](https://github.com/K4iju/System-management/assets/159083256/f0ffecb1-35ce-4992-b847-373b56fc2fa3)

1. Right-click Start and then select Settings.
2. From the right pane, scroll to the bottom and select **About**.
3. Under **Device specifications**, in the Related links box, select **System protection**.

## Configuring System Protection Settings

### Configuring Local Disk (C:)

![image](https://github.com/K4iju/System-management/assets/159083256/c945d2de-c25b-493f-bfe3-68b1381cac2b)


1. Make sure the **System Protection** tab is selected.
2. Select **Local Disk (C:)** and then select **Configure**.
3. Under **Restore Settings**, select **Turn on system protection**.
4. Under **Disk Space Usage**, adjust **Max Usage** to **5%** and then select **OK**.

### Configuring Data (D:)

![image](https://github.com/K4iju/System-management/assets/159083256/25d82e7c-f2a6-4bcf-a5c7-2ec35c486d52)




1. Select **Data (D:)** and then select **Configure**.
2. Under **Restore Settings**, select **Turn on system protection**.
3. Under **Disk Space Usage**, adjust **Max Usage** to **7%** and then select **OK**.

## Creating a Restore Point
![image](https://github.com/K4iju/System-management/assets/159083256/081c0390-5050-454b-926f-ff8dc32b2e0f)

1. Select **Create** to create a restore point.
2. Enter a name of your choosing for the restore point and then select **Create**.
3. When prompted, select **Close** to acknowledge the completion of the restore point.
4. Select **OK** to close the **System Properties** dialog.

## Configure the Boot Order

## Scenario 
You are the IT administrator for a small corporate network. You have just changed the SATA hard disk in the workstation in the Executive Office. You need to edit the boot order to make it consistent with office standards.

1. **Access the BIOS settings:**
![alt text](image-53.png)
   - Select the power button on the computer.
   - As the computer begins to boot, press the Delete key (or F2 key) to enter the computer's BIOS settings.

2. **Disable booting from the diskette drive:**
![alt text](image-54.png)
   - From the left pane, under General, select Boot Sequence.
   - Under Boot Sequence, unmark Diskette Drive to disable the ability to boot from the diskette.

3. **Change the boot sequence order:**
![alt text](image-55.png)
   - From the right pane, select a device field that needs to be moved to a different boot order location.
   - Move the selected device up or down using the arrows to the right of the device list.
   - Repeat this step to modify additional device priorities as required.

4. **Apply changes and exit BIOS:**
![alt text](image-56.png)
   - Select Apply and then select Exit.
   - The computer will automatically boot to Windows according to the new boot sequence.

<h1>Troubleshooting system startup</h1>

<h2>Scenario</h2>
You work at a computer repair store. A customer brought in a computer and asked you to upgrade the motherboard. You replaced the motherboard with a newer model, but now the computer will not boot. In addition to the new motherboard, the computer currently contains the following:


## Replicate the problem described in the scenario.
![alt text](image-57.png)
-  On the computer, select the power button.
- Select OK to close the prompt indicating that the computer failed to run.
- This is most likely due to the computer not getting power.


## Provide power to the computer.

![image](https://github.com/K4iju/System-management/assets/159083256/943ad887-bcf0-4706-ac0b-41bab0086639)


![image](https://github.com/K4iju/System-management/assets/159083256/ee56e29a-ce00-4e04-b963-314317f12bec)


- Above the computer, select Back.
-Select the AC Power Connector (Female) that is currently plugged into the power supply.
- Notice that the other end is not connected.
- From the Selected Component pane, drag the AC Power - Connector (Male) to an open outlet on the wall plate.
- Above the computer, select Front and then select the power button.
- The computer still won't start.
- Select OK to close the prompt.


## Connect the case's power switch to the motherboard header.

![image](https://github.com/K4iju/System-management/assets/159083256/9b69fc08-02c1-4028-a00c-32bfd961fe15)

![image](https://github.com/K4iju/System-management/assets/159083256/923d7e04-5cec-45ca-b68c-911a724eeb3e)


- Above the computer, select Motherboard.
- Notice that under Partial Connections for the computer, the system case is shown.
- Under Partial Connections for the computer, select the system case.
- From the Selected Component pane, drag the Connector, Case, Power Switch to the motherboard header (bottom right).
- If needed, view the motherboard details to find the connection areas.
- Above the computer, select Front and then select the power button.
- The computer boots to Windows, but soon powers off. This is typically caused by the computer overheating.
Select OK to close the prompt.

## Provide power to the heat sink and fan to prevent the computer from overheating.

![image](https://github.com/K4iju/System-management/assets/159083256/16108fb2-a71e-41b2-8c98-6e89b393d86d)

- Above the computer, select Motherboard.
- Notice that, under Partial Connections for the computer, the heat sink and fan is shown.
- Under Partial Connections for the computer, select the heat sink and fan.
- From the Selected Component pane, drag the Connector, Fan, CPU 4-pin that is connected to the motherboard (top center).
- Above the computer, select Front.
- On the computer, select the power button.
- The computer powers on and stays on.
![image](https://github.com/K4iju/System-management/assets/159083256/85ebce6a-249b-45f7-bd84-ac76ef0d6904)

## Verify that the memory (12 GB), two hard drives, and an optical drive are recognized.
- Right-click Start.
- Select Shut down or sign out > Restart.
- When you see the TestOut splash screen, press F2 (or delete) to enter the BIOS settings.
![image](https://github.com/K4iju/System-management/assets/159083256/f14d84be-9b5f-4d72-927d-5075ca18c565)

- Verify that the memory (12 GB) and the two hard drives are recognized.
- Select Exit to boot to the operating system.
![image](https://github.com/K4iju/System-management/assets/159083256/8a63d796-52e2-43f5-9085-170fddceb7d1)

- From the taskbar, select File Explorer.
- From the left pane, select This PC.
- Verify that the optical drive is shown.
