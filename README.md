# unraid-template

Official Twingate Connector template for Unraid app support

## Testing Setup

1. SSH into your unraid instance. 
2. Run the following command: `touch /boot/config/plugins/dockerMan/templates-user/twingate-connector.xml`
3. Use a text editor program to open this new file.
4. Copy past the `twingate-connector.xml` into the new file.
5. Save and exit.
6. Navigate to the Docker settings page: `http://<serverIP>/Settings/DockerSettings`.
7. Verify that the Docker service is enabled.
8. Navigate to the Docker page: `http://<serverIP>/Docker`.
9. Click `Add Container`.
10. Use the `Template` drop down to find `twingate-connector`. This will be under the `[User templates]` section.
11. Fill out the `Access Token`, `Refresh Token`, and `Network Name` sections.
12. Click `Apply`.
