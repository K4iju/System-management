# File Management

# Folder Permissions Setup

This repository contains instructions for configuring share and NTFS permissions for folders on the D:\ drive.

## Access the Folders on the D:\ Drive
![alt text](image-66.png)
1. From the taskbar, select File Explorer.
2. From the left pane, select This PC.
3. From the right pane, double-click Data (D:).

## Configure Share Permissions for the D:\Finances Folder
![alt text](image-74.png)
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
![alt text](image-75.png)
1. Right-click Graphics and then select Show more options.
2. Select Give access to > Specific people.
3. Using the drop-down list, select the Everyone group and then select Add.
4. Select Everyone and then select Read/Write.
5. Select Share.
6. Select Done.

## Configure NTFS Permissions for the D:\Finances Folder
![alt text](image-76.png)
1. Right-click Finances and then select Properties.
2. Select the Security tab.
3. Select Advanced to modify inherited permissions.
4. Select Disable inheritance.
5. Select Convert inherited permissions into explicit permissions on this object.
![alt text](image-77.png)
6. Select the Everyone group and then select Remove to remove the group from the access control list.
7. Select Users and then select Remove.
8. Select OK to close the Advanced Security Settings for Finances dialog.
9. Select OK to close the Finances Properties dialog.

Because the Give access to > Specific people option was used to add Accounting to the share, that group is already in the ACL and has the Allow Full Control NTFS permission.

## Configure NTFS Permissions for the D:\Graphics Folder
![alt text](image-82.png)
1. Right-click Graphics and then select Properties.
2. Select the Security tab.
3. Select Edit to change permissions for a group.
4. Select the Everyone group.
5. Under Permissions for Everyone, clear Full control, Modify, and Write.
![alt text](image-83.png)
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
![alt text](image-84.png)
1. Open File Explorer from the taskbar.
2. Maximize the window for better viewing.
3. In the left pane, expand and select `This PC > Data (D:)`.
4. Right-click the folder you want to modify (`D:\Day Data` or `D:\Night Data`) and select `Properties`.
5. Select the `Security` tab.
6. Click on `Advanced`.
7. Click on `Disable inheritance`.
8. Select `Convert inherited permissions into explicit permissions on this object`.

### Remove the Users group from the Permission entries list (ACL)
![alt text](image-85.png)
1. In the `Permission entries` list, select `Users`.
2. Click on `Remove`.
3. Click `OK`.

### Add the appropriate group to the folder's security (ACL)
![alt text](image-86.png) (For the Day Data folder)
![alt text](image-87.png) (For the NightGroup folder)
1. In the `Properties` dialog, select `Edit`.
2. Click on `Add`.
3. Enter the name of the group you want to add (`DayGroup` for `D:\Day Data` or `NightGroup` for `D:\Night Data`).
4. Click `OK`.

### Assign Full Control over each folder to the appropriate group
![alt text](image-89.png)
![alt text](image-88.png)
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
![alt text](image-90.png)
    - From the Windows taskbar, select File Explorer.
    - From the left pane, select This PC.
    - From the right pane, double-click Local Disk (D:).

2. Encrypt the Finances folder:
![alt text](image-91.png)
![alt text](image-92.png)
    - Right-click Finances and then select Properties.
    - Select Advanced.
    - Select Encrypt contents to secure data and then select OK.
    - Select OK to close the properties dialog.
    - Select OK to confirm the attribute changes.

### Give John authorization to modify the encrypted 2022report.xls file
![alt text](image-93.png)
1. Double-click Finances.
2. Right-click 2022report.xls and then select Properties.
3. Select Advanced.
4. Select Details.
5. Select Add.
6. Select John and then select OK.
7. Select OK as many times as needed to close all remaining dialogs.


