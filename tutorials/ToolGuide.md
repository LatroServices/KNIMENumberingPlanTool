# Written Tutorial

## Prerequisites
1. Ensure that your connected to your iNOC VPN first.
2. Make sure you have KNIME Analytics Platform installed on your PC, If you don't you can Download it from the web. 
4. Download the KNIME Numbering Plan flow from shared folder (https://latroservices962.sharepoint.com/:u:/s/tbu/EWmEkwouuUNMvsIhf3_xYDkBsspuiq5nmDv4ARRSW3xtiA?e=JUAXDG)](https://latroservices962.sharepoint.com/:u:/r/sites/rafm/Training%20Library/KNIME%20Numbering%20Plan/Qualify%20Numbers.knwf?csf=1&web=1&e=cnAeCK)


## Running the Tool
1. Connect to your iNOC VPN
2. Open your KNIME Analytics Platform tool.
3. Create a CSV file and enter all MSISDN values that you would like to qulaify in one coloumn called MSISDN.
4. Go to file and click on *Import KNIME Flow*
5. Click on Brwse, select the NIME Numbering Plan flow you've downloaded and click on Finish.
6. Go to KNIME explorer and open it.
7. Double click on CSV Reader component in the flow, from the popup window go to settings, File, and browse your desired file to add it.
8. Click on Ok, you;; see a popup warning window, click on Ok as well.
9. Double click on CSV writer component in the flow, from the popup window go to settings, File, and browse your desiredplace to upload the outpot filr to.
10. from the menu bar click on ![image](https://github.com/user-attachments/assets/1fbf1f52-3698-4940-a556-b3a592699b74) , all nodes will be executed.

 
## Helpul Notes
1. in next tume you want to run this flow no need to import it as you will find it in KNIME Explorer.
