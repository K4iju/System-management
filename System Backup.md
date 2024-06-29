<h1>Back up the computer</h1>

<h2>Scenario</h2>
You have recently completed a major project that is vital to your company's success. To ensure that this and all future data is protected, you have decided to implement Windows 10 backups.

# Windows Backup Instructions

Follow these steps to add a drive for backups and configure backup settings on Windows:

## Add a Drive for Backups

![image](https://github.com/K4iju/System-management/assets/159083256/40b4edb8-c651-4956-8fb9-d768ce1b921d)


1. Right-click **Start** and select **Settings**.
2. Select **Update & Security**.
3. From the left pane, select **Backup**.
4. Select **Add a drive**.
5. Select **Backup (E:)**.
6. Notice that **Automatically back up my files** is automatically set to **ON**.

## Configure Backup Settings

### Configure When Backups Will Happen and How Long to Keep Them

![image](https://github.com/K4iju/System-management/assets/159083256/f4365ad5-b3c6-4bf0-afc0-f564eaa13d6b)


1. Select **More options**.
2. Under **Back up my files**, use the drop-down menu to select **Daily**.
3. Under **Keep my backups**, use the drop-down menu to select **6 months**.

### Configure Which Folders to Back Up and Run a Backup

![image](https://github.com/K4iju/System-management/assets/159083256/deb33c4a-fe2d-4b0c-a458-811a60c5288b)


1. Under **Back up these folders**, select **Add a folder**.
2. Expand and select **This PC > Data (D:)**.
3. Select **Choose this folder**.
4. Scroll to the top and select **Back up now**.

<h1>Configure File History</h1>

<h2>Scenario</h2>
Zoey is responsible for developing an important new advertising campaign. To protect her data, you have decided to enable File History on her Windows 10 system and configure it to take frequent snapshots of her files.

1. **Select Start**:
    - Click on the **Start** button on your Windows desktop.

2. **Open Control Panel**:

   ![image](https://github.com/K4iju/System-management/assets/159083256/ef0dad5f-6145-4a73-8114-b14e3a733cf0)

    - Scroll down and expand **Windows System**.
    - Select **Control Panel**.

4. **Access File History**

    ![image](https://github.com/K4iju/System-management/assets/159083256/7c0aed30-3db8-41ea-a07f-bf1396f6e2d7)

    - Select **System and Security**.
    - Select **File History**.

6. **Verify Disk Selection**:
    - Ensure that disk **Data (D:)** is selected for storing File History information.

7. **Turn on File History**:

   ![image](https://github.com/K4iju/System-management/assets/159083256/d9493c29-84a1-462c-9976-741c747609a5)

    - Click on **Turn on** to enable File History.

# Configure File History

1. **Open Advanced Settings**:
    - From the left, select **Advanced settings**.

2. **Set Save Frequency**:

![image](https://github.com/K4iju/System-management/assets/159083256/fd040ebf-e675-4805-afaa-5604437ae2b7)
   
    - Use the **Save copies of files** drop-down menu to select **Every 10 minutes**.

4. **Set Version Retention**:

   ![image](https://github.com/K4iju/System-management/assets/159083256/73474c5a-c980-4006-ab99-34e1971d6e48)

    - Use the **Keep saved versions** drop-down menu to select **3 months**.

6. **Save Changes**:
    - Select **Save changes**.
  


<h1>Restore data from file history</h1>

Scenario: You are the IT administrator for a corporate network. You just received an email from Margarita, who produces your organization's monthly magazine. The email was to notify you that she had created a help desk ticket using Issue Trax, and she hoped that someone could help her straight away. The computer you work from is named ITAdmin.


# Lab Instructions

## Resolving Margarita's Help Desk Ticket

![image](https://github.com/K4iju/System-management/assets/159083256/0e1b5092-e283-4300-8932-ce7cb07d9bd5)

1. From ITAdmin, determine the needs and possible fixes for Margarita's help desk ticket.
2. From the taskbar, select Issue Trax.
3. Maximize the window for better viewing.
4. Select ticket #21.
5. From the open ticket, determine the best course of action to resolve Margarita's issue.
6. Leave the ticket maximized so you can see the details.



## Go to Marketing 6 Department

![image](https://github.com/K4iju/System-management/assets/159083256/265f91b0-b52a-4acc-b7c0-ff654300b221)



8. From the top left, select Floor 1.
9. Under Building A, select Floor 2.
10. Under Marketing Group C, select Marketing6.



## Configure backup


![image](https://github.com/K4iju/System-management/assets/159083256/d3d8e00c-cb18-442b-ab9c-3d8c5117b31f)


11. Right-click Start and then select Settings.
12. Select Update & Security.
13. From the left pane, select Backup.
14. Make sure Automatically back up my files is set to On.
15. Select More options.
16. Scroll to the bottom of the Backup options dialog and, under Related settings, select Restore files from a current backup.

## Restore March2022_Issue.jpg

![image](https://github.com/K4iju/System-management/assets/159083256/424921fd-9ef2-4a86-84fe-25cb820421e1)


17. Maximize the window for better viewing
18. Restore the March2022_Issue.jpg file.
    - From the bottom of the File History dialog, select the Previous version button (left arrow) to navigate to the backups captured on Tuesday, March 15, 2022 11:15 AM.
    - Double-click on the Pictures folder.
    - Double-click on the Layouts folder.
    - Select the March2022_Issue.jpg file.
    - Select Restore to original location (green arrow) located at the bottom center.
    - Select Replace the file in the destination.
    - The Layouts folder, where the file was restored, opens.
    - From the Layouts folder, right-click the March2022_Issue.jpg file and then select Properties.
    - Verify that the file was last modified on March 15, 2022 at 11:15:12 AM.
    - Select OK.
    - Close the Layouts window.

## Restore Coverart.jpg

![image](https://github.com/K4iju/System-management/assets/159083256/8d9ff7c4-0845-493c-929f-ca349fa8c77c)


19. Restore the Coverart.jpg file.
    - In the top left of File History, select the up arrow to navigate to the Home\Pictures folder.
    - Select the Next version button (right arrow) at the bottom to navigate to the backups captured on Monday, March 14, 2022 10:15 AM.
    - Double-click on the Images folder.
    - Select the coverart.jpg file.
    - Select Restore to original location (green arrow) located at the bottom center.
    - Select Replace the file in the destination.
    - Right-click the coverart.jpg file and select Properties.
    - Verify that the file was last modified on Monday, March 14, 2022 10:15:12 AM.
    - Select OK.

## Add Comment
![image](https://github.com/K4iju/System-management/assets/159083256/d06db2da-4a1e-4cd7-8fdf-66204467bad2)


20. Add a comment to the ticket and close the ticket.
    - From the top left, select Floor 2.
    - Under Building A, select Floor 1.
    - Under IT Administration, select ITAdmin.
    - In the New Comment field of the open ticket, enter a comment of your choice to indicate that the files were restored.
    - Select + (the plus sign) to add the comment.
    - From the top of the ticket:
        - Select Closed.
        - Select the left arrow.
        - There are no more tickets to be processed.
21. Close Issue Trax.
