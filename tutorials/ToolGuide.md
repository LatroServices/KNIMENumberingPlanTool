# Written Tutorial

## Prerequisites
1. Ensure you're connected to your **iNOC VPN**.
2. Install **KNIME Analytics Platform** on your PC.  
   If not installed, you can download it from the [KNIME official website](https://www.knime.com/downloads).
3. Download the **KNIME Numbering Plan** flow from the shared folder:  
   [Download KNIME Flow](https://latroservices962.sharepoint.com/:u:/r/sites/rafm/Training%20Library/KNIME%20Numbering%20Plan/Qualify%20Numbers.knwf?csf=1&web=1&e=h4LJbq)

--- 

## Running the Tool
1. Connect to your **iNOC VPN**.
2. Launch the **KNIME Analytics Platform**.
3. Create a **CSV file** with all MSISDN values in a single column titled `MSISDN`.
4. From the menu bar, go to **File > Import KNIME Workflow**.
5. Click **Browse**, select the downloaded *KNIME Numbering Plan* flow, then click **Finish**.
6. Open the flow via **KNIME Explorer**.
7. Double-click the **CSV Reader** component. In the popup window:
   - Go to the **Settings** tab → **File** section
   - Browse and select your MSISDN input file
   - Click **OK** (acknowledge any warning messages)
8. Double-click the **CSV Writer** component. In the popup window:
   - Go to **Settings** → **File**
   - Choose the output file location where the qualified numbers will be saved
9. From the menu bar, click the **green execute icon** (![Execute All](https://github.com/user-attachments/assets/1fbf1f52-3698-4940-a556-b3a592699b74)) to run all nodes in the workflow.

--- 

## Helpul Notes
1. The next time you want to run the tool, **you don’t need to re-import the flow**. It will be available under your **KNIME Explorer**.
