<h1>Active Directory</h1>

<h2>Creating Organizational Units</h2>


Scenario: You are the IT administrator for a small corporate network. You have just installed Active Directory on a new Hyper-V guest server named CorpDC. You need to create an Active Directory organizational structure. The Active Directory structure will be based on the company's departmental structure.

## OUs to be Created in CorpNet.local Domain
- Accounting
- Admins
- Marketing
- Research-Dev
- Sales
- Servers
- Support
- Workstations

## OUs to be Created in Sales Container
- SalesManagers
- TempSales

## Steps to Complete the Lab

1. **Access the CorpDC Server:**
   ![image](https://github.com/K4iju/System-management/assets/159083256/bcd5c7f0-f87e-4a04-9a04-38b0e16ac4d0)

   - Open Hyper-V Manager.
   - Select CORPSERVER.
   - Under Virtual Machines, double-click CorpDC.
    

2. **Create OUs in CorpNet.local Domain:**
   ![image](https://github.com/K4iju/System-management/assets/159083256/5d8c85ab-f2d7-4be3-a286-0596ed18e76d)
   ![image](https://github.com/K4iju/System-management/assets/159083256/45e1c577-c4d8-4cfd-a119-7fe3bcabc216)


   ![image](https://github.com/K4iju/System-management/assets/159083256/35adf071-645b-407c-a02c-36fbe52b2470)



   - Open Server Manager and select Tools > Active Directory Users and Computers.
   - Right-click `CorpNet.local` and select `New > Organizational Unit`.
   - Enter the OU name and ensure `Protect container from accidental deletion` is selected.
   - Click `OK`.
   - Repeat for the remaining OUs.

4. **Create OUs in the Sales Container



<h1>Delete Organizational Unit</h1>

 ![image](https://github.com/K4iju/System-management/assets/159083256/bcd5c7f0-f87e-4a04-9a04-38b0e16ac4d0)
1. From the Hyper-V Manager, select **CORPSERVER**.
2. Under **Virtual Machines**, double-click **CorpDC**.

## Enable Active Directory Users and Computers Advanced Features

 ![image](https://github.com/K4iju/System-management/assets/159083256/5d8c85ab-f2d7-4be3-a286-0596ed18e76d)

 ![image](https://github.com/K4iju/System-management/assets/159083256/c07837ff-807f-4a8f-b9bc-ed31184f5c48)

1. From **Server Manager**, select **Tools > Active Directory Users and Computers**.
2. From the top menu, select **View > Advanced Features**.
3. Maximize the **Active Directory Users and Computers** window.

## Delete the Departmental Workstations OUs

![image](https://github.com/K4iju/System-management/assets/159083256/26dac38c-3801-4597-bbe1-085036379c9f)


![image](https://github.com/K4iju/System-management/assets/159083256/60748cff-82fc-42a8-829f-6761c64121bc)


1. From the left pane, expand **CorpNet.local**.
2. From the left pane, select the OU that you wish to open.
3. From the right pane, right-click **Workstations** and select **Properties**.
4. Select the **Object** tab.
5. Clear **Protect object from accidental deletion**.
6. Select **OK**.
7. Right-click **Workstations** and select **Delete**.
8. Select **Yes** to confirm deletion.
9. Repeat steps 2-8 to delete the additional OUs.

## Disable Active Directory Users and Computers Advanced Features
1. Select **View > Advanced Features** again to turn off the advanced features view.
    - Right-click `Sales` and select `New > Organizational Unit`.
   - Enter the OU name and ensure `Protect container from accidental deletion` is selected.
   - Click `OK`.
   - Repeat for the remaining OUs.
