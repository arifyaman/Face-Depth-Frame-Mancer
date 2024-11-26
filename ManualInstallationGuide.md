# Manual Installation Guide

Thank you for downloading the plugin! If you downloaded the plugin from a source other than the Fab Marketplace, follow the steps below to manually install it into the Unreal Engine so that it can be used with any project:

## Installation Steps
1. **Unzip the Plugin File**  
   Extract the contents of the downloaded `.zip` file. You will find the `FDFMancer` folder in the extracted folder.  
   ![Extract Frames](images/1i1.png)

2. **Paste into the Unreal Plugins Marketplace Directory**  
   Navigate to your Unreal Engine installation directory and paste the extracted folder into:  
   e.g., `Epic Games/<Version>/Engine/Plugins/Marketplace/`  

   ![Extract Frames](images/1i3.png)

    ### Notes
    - If the `Marketplace` folder does not exist in the `Plugins` directory, you can create it manually.
    - Ensure you have the correct permissions to modify files in the Unreal Engine installation directory.  
    - Alternatively, if you prefer to use the plugin on a per-project basis, you can create a `Plugins` folder in your project directory and paste the extracted folder there.

3. **Continue to Usage**  
   For further instructions on how to use the plugin, refer to the [README](README.md) file under the "Installation" tab.

---

## Manual Update Steps

To manually update the plugin to a newer version, follow these steps:

1. **Backup Existing Plugin**  
   - Navigate to the directory where the plugin is installed:
     - **Engine-wide Installation**: `Epic Games/<Version>/Engine/Plugins/Marketplace/`
     - **Per-project Installation**: `<YourProjectFolder>/Plugins/`
   - Make a copy of the existing `FDFMancer` folder as a backup.

2. **Download the Updated Plugin**  
   - Obtain the updated `.zip` file from the appropriate source.

3. **Uninstall the Old Plugin**  
   - Delete the existing `FDFMancer` folder from the plugin installation directory.

4. **Install the New Plugin**  
   - Follow the same steps as in the [Installation Steps](#installation-steps) section to unzip and paste the new plugin version into the desired directory.

5. **Verify the Update**  
   - Launch Unreal Engine and confirm the plugin is loaded successfully.
   - Check the plugin version in the Unreal Engine Plugin Manager to ensure it reflects the updated version.

### Notes
- Always back up your project and plugin folder before updating to avoid data loss.
- Ensure compatibility between the plugin version and your Unreal Engine version.
- If issues arise, refer to the troubleshooting guide in the [README](README.md).

---

For any additional help, feel free to contact support or consult the [README](README.md) file.
