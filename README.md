# atdm_tezi_image
ATDM TEZI image that can be used with Torizon tools to perform limited customization (e.g., change the splash screen).

[Download ATDM TEZI Image](https://drive.google.com/file/d/1dvIXPCH5OlxPLMUz1HclozqxjfWhFkVn/view?usp=sharing).

# Installing the TEZI Image for ATDM

## Step 1: Download the Torizon Easy Installer

### Visit the Toradex Easy Installer Page:
- Go to the [Toradex Easy Installer page](https://developer.toradex.com/software/toradex-easy-installer).

### Download the Installer:
- Select the appropriate TEZI installer for your ATDM and download it to your computer.

## Step 2: Prepare the Installation Medium

### Prepare a Bootable USB Drive or SD Card:
- Use a tool like [Etcher](https://www.balena.io/etcher/) or [Rufus](https://rufus.ie/) to write the TEZI installer image to a USB drive or SD card.

## Step 3: Install the TEZI Image on the ATDM

### Insert the Bootable Medium:
- Insert the prepared USB drive or SD card into ATDM's USB or SD card slot.

### Connect to the ATDM:
- Connect your ATDM to a keyboard to the USB port.

### Power Up the Verdin SOM:
- Power on the ATDM. The system should boot from the Tezi installer.

### Launch the Toradex Easy Installer:
- If the system doesn't boot into the installer, you may need to use the hardware buttons or the serial console to set the boot mode.

## Step 4: Install the TEZI Image

### Select the TEZI Image:
- Once the Easy Installer is running, you should see a list of available images. Select the appropriate Tezi image for ATDM.

### Start the Installation:
- Follow the on-screen instructions to install the TEZI image. This process will erase the existing software on the Verdin SOM and replace it with the TEZI image.

### Wait for Completion:
- The installation process will take a few minutes. Once completed, the system will prompt you to remove the installation medium and reboot the device.

### Reboot the ATDM:
- Remove the USB drive or SD card and reboot the ATDM. It should now boot into the current version of the TEZI image.

## Step 5: Post-Installation Configuration

### Connect to the Network:
- Ensure your ATDM is connected to a network via Ethernet or Wi-Fi.

### Access the Device:
- You can access the device via SSH or the Torizon web interface for further configuration and deployment of your applications.

### Deploy Applications:
Use Docker to deploy your applications onto the Torizon platform. For detailed instructions on deploying and managing applications, refer to the [Torizon documentation](https://developer.toradex.com/torizon).

## Additional Tips

- **Keep the Bootloader Updated:** Ensure the bootloader on your ATDM is up to date to avoid compatibility issues.
- **Consult the Documentation:** Refer to the [Toradex Developer Center](https://developer.toradex.com/) for detailed guides and troubleshooting tips.

By following these steps, you can successfully install the TEZI image for use with the ATDM product by Andromeda.
