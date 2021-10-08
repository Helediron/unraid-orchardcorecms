# unraid-orchardcorecms

## Template description

This app installs Orchard Core CMS official docker image to Unraid.
You can use the app as a blog engine as-is. Developers should visit the github. Orchard Core is fully extensible .net core C# framework.
Documentation: https://docs.orchardcore.net/en/latest/ 
Quick-start: After installing the container, open the WebUI to finalize the setup.
- Give any name to the site.
- Select e.g. Agency recipe to get some sample content loaded.
- Fill admin username, email and password. The password has to be complex enough. When the bar under it turns green it's okay.
- Save and let it create the site.
- Append /Admin to your URL to access admin dashboard .

If you want to start over, stop the container, go to /mnt/user/appdata/orchardcorecms in Unraid server and remove folder App_Data and everything under it.
