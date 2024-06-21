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
 

   ![image](https://github.com/K4iju/System-management/assets/159083256/d17a8028-d8ac-42a2-9bfd-2b678c03e6b9)
   - Right-click `Sales` and select `New > Organizational Unit`.
   - Enter the OU name and ensure `Protect container from accidental deletion` is selected.
   - Click `OK`.
   - Repeat for the remaining OUs.
