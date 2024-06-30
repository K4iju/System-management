# File Management

# Folder Permissions Setup

This repository contains instructions for configuring share and NTFS permissions for folders on the D:\ drive.

## Access the Folders on the D:\ Drive
![image](https://github.com/K4iju/System-management/assets/159083256/a1af71f4-cef0-4285-88e8-67606a61b9ec)

1. From the taskbar, select File Explorer.
2. From the left pane, select This PC.
3. From the right pane, double-click Data (D:).

## Configure Share Permissions for the D:\Finances Folder
![image](https://github.com/K4iju/System-management/assets/159083256/b529eab6-ef4f-4d66-ba56-8c21127da2c3)

1. Right-click Finances and then select Show more options.
2. Select Give access to > Specific people.
3. Using the drop-down menu, select the Everyone group and then select Add.
4. Select the Everyone group and then select Read/Write.
5. Using the drop-down list, select Find People.
6. In the Enter the object names to select field, type Accounting and then select OK.
7. Select Accounting and then select Read/Write.
8. Select Share.
9. Select Done.

## Configure Share Permissions for the D:\Graphics Folder
![image](https://github.com/K4iju/System-management/assets/159083256/a42ec042-32ac-4313-9b2b-0c300c845661)

1. Right-click Graphics and then select Show more options.
2. Select Give access to > Specific people.
3. Using the drop-down list, select the Everyone group and then select Add.
4. Select Everyone and then select Read/Write.
5. Select Share.
6. Select Done.

## Configure NTFS Permissions for the D:\Finances Folder
![image](https://github.com/K4iju/System-management/assets/159083256/31e35f9b-a027-455b-9b70-d2c65b57f046)

1. Right-click Finances and then select Properties.
2. Select the Security tab.
3. Select Advanced to modify inherited permissions.
4. Select Disable inheritance.
5. Select Convert inherited permissions into explicit permissions on this object.
![image](https://github.com/K4iju/System-management/assets/159083256/1fb913cb-5d8d-4b9b-9059-9c6b593e7831)

6. Select the Everyone group and then select Remove to remove the group from the access control list.
7. Select Users and then select Remove.
8. Select OK to close the Advanced Security Settings for Finances dialog.
9. Select OK to close the Finances Properties dialog.

Because the Give access to > Specific people option was used to add Accounting to the share, that group is already in the ACL and has the Allow Full Control NTFS permission.

## Configure NTFS Permissions for the D:\Graphics Folder
![image](https://github.com/K4iju/System-management/assets/159083256/b0de0de8-1b31-4770-9ed4-2bbe2871e61a)

1. Right-click Graphics and then select Properties.
2. Select the Security tab.
3. Select Edit to change permissions for a group.
4. Select the Everyone group.
5. Under Permissions for Everyone, clear Full control, Modify, and Write.
![image](https://github.com/K4iju/System-management/assets/159083256/37c45d8c-a5d4-41d7-b942-96b8fafce505)

6. Select Add to add a group.
7. In the Enter the object names to select field, enter Marketing and then select OK.
8. With Marketing selected, select Modify. (Leave all other existing permissions as-is.)
9. Select OK to close the Permissions for Graphics dialog.
10. Select OK to close the Graphics Properties dialog.


# Configure NTFS permissions

## Scenario

You are the IT administrator for a small corporate network. There are two groups of users who access the computer in Office 1, which are called DayGroup and NightGroup. Each group has a corresponding folder (D:​\​Day Data and D:​\​Night Data) on the computer respectively.

You have been asked to help configure appropriate access to each folder for each group.

# Folder Permissions Setup

This repository contains instructions to modify folder permissions by turning off permissions inheritance and assigning full control to specific groups.

## Instructions

### Turn off permissions inheritance
![image](https://github.com/K4iju/System-management/assets/159083256/73b76e7d-7dc0-4734-b7fb-22786eb7ec1b)

1. Open File Explorer from the taskbar.
2. Maximize the window for better viewing.
3. In the left pane, expand and select `This PC > Data (D:)`.
4. Right-click the folder you want to modify (`D:\Day Data` or `D:\Night Data`) and select `Properties`.
5. Select the `Security` tab.
6. Click on `Advanced`.
7. Click on `Disable inheritance`.
8. Select `Convert inherited permissions into explicit permissions on this object`.

### Remove the Users group from the Permission entries list (ACL)
![image](https://github.com/K4iju/System-management/assets/159083256/ca401441-fa94-46ab-a43e-c094ccaddd72)

1. In the `Permission entries` list, select `Users`.
2. Click on `Remove`.
3. Click `OK`.

### Add the appropriate group to the folder's security (ACL)
![image](https://github.com/K4iju/System-management/assets/159083256/b2929fa5-2bbd-4fc0-8209-30f36987c42c)
 (For the Day Data folder)
![image](https://github.com/K4iju/System-management/assets/159083256/9784dc66-9220-482c-b89c-58c2ee74ef71)
 (For the NightGroup folder)
1. In the `Properties` dialog, select `Edit`.
2. Click on `Add`.
3. Enter the name of the group you want to add (`DayGroup` for `D:\Day Data` or `NightGroup` for `D:\Night Data`).
4. Click `OK`.

### Assign Full Control over each folder to the appropriate group
![image](https://github.com/K4iju/System-management/assets/159083256/e29abb0f-3d27-4a37-a34d-4214c43feaca)

![image](https://github.com/K4iju/System-management/assets/159083256/da9b6661-8a6c-482f-84ff-b4975c80fd83)

1. With the group highlighted, under the `Allow` column, select `Full Control`.
2. Click `OK` to close the Permissions window.
3. Click `OK` to close the Properties window.

### Repeat steps

Repeat steps 1-4 to modify the permissions for the other folder.

## Notes

- Ensure you have the necessary administrative privileges to modify folder permissions.
- Double-check group names before adding them to the security settings.

# Configure File Encryption

##  Scenario

You share a computer with other users at work. You want to secure the contents of the Finances folder so that unauthorized users cannot view its contents.



### Encrypt the Finances folder

1. Open the D:\ drive:
![image](https://github.com/K4iju/System-management/assets/159083256/edda688d-4a7a-4bb8-a8c6-0a1e07cc654a)

    - From the Windows taskbar, select File Explorer.
    - From the left pane, select This PC.
    - From the right pane, double-click Local Disk (D:).

2. Encrypt the Finances folder:
![image](https://github.com/K4iju/System-management/assets/159083256/0297e8e4-7d13-4bb6-9199-5adba12b8e8b)

![image](https://github.com/K4iju/System-management/assets/159083256/83218c87-5b1c-407c-9372-7b4c43bed4de)

    - Right-click Finances and then select Properties.
    - Select Advanced.
    - Select Encrypt contents to secure data and then select OK.
    - Select OK to close the properties dialog.
    - Select OK to confirm the attribute changes.

### Give John authorization to modify the encrypted 2022report.xls file
![image](https://github.com/K4iju/System-management/assets/159083256/65c385b2-b7a6-457e-b84d-4444c2ce0e93)

1. Double-click Finances.
2. Right-click 2022report.xls and then select Properties.
3. Select Advanced.
4. Select Details.
5. Select Add.
6. Select John and then select OK.
7. Select OK as many times as needed to close all remaining dialogs.


