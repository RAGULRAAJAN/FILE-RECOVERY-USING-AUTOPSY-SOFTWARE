# Using-the-Autopsy-retrieve-the-deleted-files
## AIM:
To use Autopsy in Kali Linux to retrieve and analyze deleted files from a disk image.

## DESIGN STEPS:
### Step 1:
Open Autopsy and create a new case with appropriate case details.

### Step 2:
Add a disk image as a data source and let Autopsy analyze the content.

### Step 3:
Navigate to the "Deleted Files" section in Autopsy and examine or recover the deleted files.

## PROGRAM:
Autopsy Deleted File Recovery Steps

# Step 1: Launch Autopsy
autopsy
It opens your browser at: http://localhost:9999
 
# Step 2: Create a New Case
Click "Create New Case".

Enter a Case Name (e.g., FileRecoveryTest).

Enter any optional details (e.g., Examiner name).

Choose a Case Directory (e.g., /home/kali/Documents/AutopsyCases).

Click "Finish".

# Step 3: Add Data Source (Your Disk Image)
Select "Add Data Source".

Choose "Disk Image or VM File".

Browse and select your image file: e.g., /home/kali/Downloads/disk.dd

Choose the Time Zone (e.g., UTC or your local time).

Click Next, then Finish.

Autopsy will now ingest and analyze the image file.

# Step 4: Navigate to Deleted Files
After analysis completes:

Go to the left pane → File Types or Data Artifacts.

Navigate to:

Views → Deleted Files
Or:

File Types → Unallocated Space / Deleted
Autopsy will list deleted files that were found in unallocated space.

# Step 5: Recover the Deleted Files
Click on a deleted file you want to recover.

View the file preview on the right (if supported, e.g., images or text).

Right-click on the file → Extract File.
Choose a location to save the recovered file (e.g., /home/kali/Recovered/).

Repeat for other files.

## OUTPUT:

# Recovered Deleted File List and Details 

![Screenshot 2025-04-25 135455](https://github.com/user-attachments/assets/3878b201-26a3-4880-9b0a-a377cde136ce)

![Screenshot 2025-04-25 135514](https://github.com/user-attachments/assets/6db6f9fb-122a-4a8e-b01b-85faa7ab447f)

![Screenshot 2025-04-25 135523](https://github.com/user-attachments/assets/a6060578-6446-4130-b8f0-f3d8f0760f29)


# MD5 Current And Orginal = Not Pass

![Screenshot 2025-04-25 135532](https://github.com/user-attachments/assets/f52d1e23-c738-495d-b5d2-408d4796a7da)

# MD5 Current And Orginal = Pass

![Screenshot 2025-04-25 135544](https://github.com/user-attachments/assets/536cca1c-f8d2-4e0d-a843-c795b2fd28c8)


## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
