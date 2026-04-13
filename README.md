# DaVinci Resolve Server Guide
## Requirements
- VPN-Client like Sophos
- Server VM with postgres installed, 4 GB RAM, min 50 GB of storage
- postgres user with DB write permission 
- Davinci resolve studio (all the editors need to have the newest software)

## Connecting to the Server
### 1. Connect to the VPN using your VPN-Client (e.g., Sophos).
Enter your credentials and your password plus the 2FA code:

**USER**: `<your_username>`

**PWD**: `<your_password>` + `<2FA_code>`

### 2. Open DaVinci Resolve Software and connect to the server.
Once you have successfully connected to the VPN, open DaVinci Resolve. You should see an option to connect to an existing project or create a new one. Use the credentials provided to connect to the DaVinci Resolve server.



## Create and managing Projects
Projects are stored on the server, allowing multiple users to collaborate. To access a project, simply open it from the server within DaVinci Resolve.
If you create a new project, make sure you switch from `Single User Project` to `Multiple User Collaboration`.  
Make sure to save your work frequently to avoid any data loss.

### File References
**Most importantly, every user needs to ensure that they have the correct file paths set up for the project.** This is crucial for media management and project organization. If the file paths are not correctly set, you may encounter issues with missing media or project files.

Thus, every user should store the data on an external SSD drive and ensure that the file paths are correct like:

**'E:/Projects/Project_Name/Media/...'**

When working on projects, ensure that all media files are properly linked to the server. If you move or rename files, you may need to relink them within DaVinci Resolve.

# Troubleshooting
If you encounter any issues or problems while connecting to the server or working on projects, please contact the server provider.

## Common Problems
- **VPN Connection Issues**: Ensure that your VPN client is properly configured and that you have a stable internet connection. If you continue to experience issues, contact your IT support for assistance.
- **Wrong Password:** Double-check your username and password. Remember to include the 2FA code if required.
- **File Path Issues:** Ensure that all users have the correct file paths set up for the project.
- **Software Updates:** Make sure you are using the *latest* version of DaVinci Resolve, as older versions may have compatibility issues with the server.
