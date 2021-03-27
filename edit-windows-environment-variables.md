# How to change environment variables on Windows 10

Here is a guide to editing environment variables on Windows 10!

# Steps to add/edit environment variables

- Open the Start Search, type in “env”, and choose **Edit the system environment variables**

  ![start_menu](https://user-images.githubusercontent.com/57333028/112717528-69f8dd80-8f13-11eb-8873-5d97ab9044c7.png)

- Click the **Environment Variables…** button.

  ![system_properties](https://user-images.githubusercontent.com/57333028/112717543-809f3480-8f13-11eb-82ae-485e64148f3a.png)

- Under the **System Variables** section (the lower half), find the row with **Path** in the first column, and click **Edit..**

  ![select_row_and_edit](https://user-images.githubusercontent.com/57333028/112717670-3c606400-8f14-11eb-928f-73dcd006ebda.png)

- The **Edit environment variable** UI will appear. Here, you can click **New** and type in the new path you want to add. From this screen you can also edit or reorder them.

- Set the environment variables as needed.
  - The **New** button adds an additional variable
  - The **Edit** button modifies the selected variable
  - The **Delete** button deletes the selected variable

  ![edit_path_variable](https://user-images.githubusercontent.com/57333028/112717560-957bc800-8f13-11eb-9a6c-e664c37f08ce.png)


- Dismiss all of the dialogs by choosing **OK**. Your changes are saved!

# Applying the change
Due to how Windows applies environment variables, you most likely need to restart apps for them to pick up the change, including explorer.exe. Restarting the machine is reccomended (but not required) and ensures all apps are run with the PATH change.

- To test it, in new PowerShell window, type:
   ```
   $env:PATH
   ```
