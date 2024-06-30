# Booting windows

## Configure the Boot Order

## Scenario 
You are the IT administrator for a small corporate network. You have just changed the SATA hard disk in the workstation in the Executive Office. You need to edit the boot order to make it consistent with office standards.

1. **Access the BIOS settings:**
![image](https://github.com/K4iju/System-management/assets/159083256/c3a0b34f-5438-4eae-815f-9a49f5759f28)

   - Select the power button on the computer.
   - As the computer begins to boot, press the Delete key (or F2 key) to enter the computer's BIOS settings.

2. **Disable booting from the diskette drive:**
![image](https://github.com/K4iju/System-management/assets/159083256/0e9544f8-0220-4e7f-89e3-a3e30de07fa1)

   - From the left pane, under General, select Boot Sequence.
   - Under Boot Sequence, unmark Diskette Drive to disable the ability to boot from the diskette.

3. **Change the boot sequence order:**
![image](https://github.com/K4iju/System-management/assets/159083256/844f5fe5-2067-44d4-adb2-c136a41db71e)

   - From the right pane, select a device field that needs to be moved to a different boot order location.
   - Move the selected device up or down using the arrows to the right of the device list.
   - Repeat this step to modify additional device priorities as required.

4. **Apply changes and exit BIOS:**
![image](https://github.com/K4iju/System-management/assets/159083256/75566ef2-0759-489e-99f6-7800bd9dcb74)

   - Select Apply and then select Exit.
   - The computer will automatically boot to Windows according to the new boot sequence.

<h1>Troubleshooting system startup</h1>

<h2>Scenario</h2>
You work at a computer repair store. A customer brought in a computer and asked you to upgrade the motherboard. You replaced the motherboard with a newer model, but now the computer will not boot. In addition to the new motherboard, the computer currently contains the following:


## Replicate the problem described in the scenario.
![image](https://github.com/K4iju/System-management/assets/159083256/93718c3d-3afe-4b96-a494-48f896bbcc8c)

-  On the computer, select the power button.
- Select OK to close the prompt indicating that the computer failed to run.
- This is most likely due to the computer not getting power.


## Provide power to the computer.

![image](https://github.com/K4iju/System-management/assets/159083256/4878a605-69df-471e-ae77-eec0d262a7ba)


![image](https://github.com/K4iju/System-management/assets/159083256/e3769bd1-a128-43e7-9b90-cc28fe701f1d)


- Above the computer, select Back.
-Select the AC Power Connector (Female) that is currently plugged into the power supply.
- Notice that the other end is not connected.
- From the Selected Component pane, drag the AC Power - Connector (Male) to an open outlet on the wall plate.
- Above the computer, select Front and then select the power button.
- The computer still won't start.
- Select OK to close the prompt.


## Connect the case's power switch to the motherboard header.

![image](https://github.com/K4iju/System-management/assets/159083256/41c0c1f4-0d42-4512-96ce-2364fca261f0)


![image](https://github.com/K4iju/System-management/assets/159083256/f1d261f8-6b8e-4c07-b1b0-39d311761063)


- Above the computer, select Motherboard.
- Notice that under Partial Connections for the computer, the system case is shown.
- Under Partial Connections for the computer, select the system case.
- From the Selected Component pane, drag the Connector, Case, Power Switch to the motherboard header (bottom right).
- If needed, view the motherboard details to find the connection areas.
- Above the computer, select Front and then select the power button.
- The computer boots to Windows, but soon powers off. This is typically caused by the computer overheating.
Select OK to close the prompt.

## Provide power to the heat sink and fan to prevent the computer from overheating.

![image](https://github.com/K4iju/System-management/assets/159083256/b77f5bd6-f382-456d-b467-b04d7231512c)

- Above the computer, select Motherboard.
- Notice that, under Partial Connections for the computer, the heat sink and fan is shown.
- Under Partial Connections for the computer, select the heat sink and fan.
- From the Selected Component pane, drag the Connector, Fan, CPU 4-pin that is connected to the motherboard (top center).
- Above the computer, select Front.
- On the computer, select the power button.
- The computer powers on and stays on.
![image](https://github.com/K4iju/System-management/assets/159083256/5995fe18-5667-481a-93e3-2975a4f2447f)

## Verify that the memory (12 GB), two hard drives, and an optical drive are recognized.
- Right-click Start.
- Select Shut down or sign out > Restart.
- When you see the TestOut splash screen, press F2 (or delete) to enter the BIOS settings.
![image](https://github.com/K4iju/System-management/assets/159083256/dade2dea-7bf2-47eb-b9c6-6988778b5ed1)

- Verify that the memory (12 GB) and the two hard drives are recognized.
- Select Exit to boot to the operating system.
![image](https://github.com/K4iju/System-management/assets/159083256/7232d6f3-0ee6-4713-b572-79fec0ff2a05)

- From the taskbar, select File Explorer.
- From the left pane, select This PC.
- Verify that the optical drive is shown.
