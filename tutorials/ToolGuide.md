# Written Tutorial

## Prerequisites
1. Ensure you're connected to your **iNOC VPN**.
2. Install **KNIME Analytics Platform** on your PC.  
   If not installed, you can download it from the [KNIME official website](https://www.knime.com/downloads).
3. Download the **KNIME Numbering Plan** flow from the shared folder:  
   [Download KNIME Flow](https://latroservices962.sharepoint.com/sites/rafm/Training%20Library/Forms/AllItems.aspx?id=%2Fsites%2Frafm%2FTraining%20Library%2FKNIME%20Numbering%20Plan&viewid=a1915b24%2D33c6%2D479e%2Da7ae%2Dfcfc8d2fecc5)

--- 

## Running the Tool
1. Connect to your **iNOC VPN**.
2. Launch the **KNIME Analytics Platform**.
3. Create a **CSV file** with all MSISDN values in a single column titled `MSISDN`.
4. From the menu bar, go to **File > Import KNIME Workflow**.
5. Click **Browse**, select the downloaded *KNIME Numbering Plan* flow, then click **Finish**.
6. Open the flow via **KNIME Explorer**.
7. Double-click the **CSV Reader** component. In the popup window:
   a) Go to the **Settings** tab → **File** section
   b) Browse and select your MSISDN input file
   c) Click "Transformation" tab and ensure the column "MSISDN" type is set to "Number Long"
   d) Click "Encoding" tab and select type "UTF-8"
   e) Click **OK** (acknowledge any warning messages)
8. Double-click the **CSV Writer** component. In the popup window:
   - Go to **Settings** → **File**
   - Choose the output file location where the qualified numbers will be saved
9. From the menu bar, click the **green execute icon** (![Execute All](https://github.com/user-attachments/assets/1fbf1f52-3698-4940-a556-b3a592699b74)) to run all nodes in the workflow.
10. Once all nodes have turned green, go to the file location (from step 8) to access the output file. 
11. The output file is expected to include the following fields:
   - MSISDN
   - Country
   - Operator
   - TOS

--- 

## Helpul Notes
1. The next time you want to run the tool, **you don’t need to re-import the flow**. It will be available under your **KNIME Explorer**.
