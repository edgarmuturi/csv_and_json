# csv_and_json

## Step-by-Step Collaboration Guide

1. **Group Leader: Create Your Own Copy**

   - Fork or clone this repository to your personal GitHub account.
   - Go to "Settings" → "Manage access" → "Invite a collaborator".
   - Add both collaborators (by their GitHub usernames or emails).

2. **First Collaborator: Add CSV File**

   1. In VS Code, clone or pull the latest changes from the group leader’s forked repository.
   2. Create a new branch (e.g., `csv-feature`):
      ```bash
      git checkout -b csv-feature
      ```
   3. Open `students.ipynb` and run Section **1.3** to generate the CSV file.
   4. Add and commit the CSV file to your new branch:
      ```bash
      git add .
      git commit -m "Add CSV output"
      ```
   5. Push your branch:
      ```bash
      git push -u origin csv-feature
      ```
   6. Tell the team you are going to merge your changes from `csv-feature` into the `main` branch.

3. **Second Collaborator: Add JSON File**

   1. In VS Code, clone or pull the latest changes from the group leader’s forked repository.
   2. Create a new branch (e.g., `json-feature`):
      ```bash
      git checkout -b json-feature
      ```
   3. Open `students.ipynb` and run Section **2.2** to generate the JSON file.
   4. Add and commit the JSON file to your new branch:
      ```bash
      git add .
      git commit -m "Add JSON output"
      ```
   5. Push your branch:
      ```bash
      git push -u origin json-feature
      ```
   6. Tell the team you are going to merge your JSON file changes from `json-feature` into the `main` branch in VS Code.

4. **Syncing and Avoiding Errors**

   - Always pull the latest changes from `main` before creating a new branch:
     ```bash
     git checkout main
     git pull origin main
     git checkout -b <new-branch>
     ```
   - If conflicts occur when merging, resolve them in VS Code, commit the resolved files, and then push again.

5. **Communication**

   - Communicate the entire time during the discussion to avoid conflicts.
   - Coordinate merges with the group leader so everyone’s changes are included.
