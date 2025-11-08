## Intune Company Portal

Follow these instructions to install the Company Portal on Windows using the EXE package. For organization-wide deployments, you may run the `msiexec` command from the terminal to perform a silent installation.

1. Download the version of the Company Portal installer suitable for your system:

* [Windows 64-bit](https://github.com/shieldcp/Company-Portal/releases/tag/11.2.1393)  *(most common)*
* [Windows 32-bit](*)
* [Windows ARM64](*)

2. Launch the installer by double-clicking the downloaded file.

3. On the welcome screen, select **Next**.

4. To accept the license terms, check **I accept the terms in the License Agreement**, then click **Next**.

5. At the Installation Scope step, choose one of the options:

* **Install only for you**: Installs the Company Portal in a user-specific folder, making it accessible only to your account. Administrator rights are not required.

* **Install for all users on this machine**: Installs the Company Portal system-wide so all accounts on the device can use it. Administrator privileges are required.

6. Click **Install** to start the setup.

7. When installation finishes, select **Finish**.

8. If **Launch Company Portal when setup exits** is checked, the app will start automatically. Otherwise, launch it manually via the Start menu by searching for **Company Portal**.

Before connecting to your devices or applications on Windows, ensure the following prerequisites are met:

* Active internet connection

* Supported Windows version:

  * Windows 11
  * Windows 10
  * Windows Server 2022
  * Windows Server 2019
  * Windows Server 2016

* .NET Framework 4.6.2 or later. Certain builds of Windows 10 and Windows Server 2016 may require manual installation. Visit the official .NET Framework download page for the latest release.

### Android

To install Company Portal on Android, use one of these app stores:

* [Portal AppStore](*)
* [Google Play](*)
* [Amazon Appstore for Android](*)

If these stores are unavailable, or your device does not support Google Mobile Services, you can [download Microsoft Intune Company Portal for Android](*) and install it manually. Note that side-loaded apps will not receive automatic updates or security patches, requiring updates.

The Google Play Store is blocked in the People's Republic of China. In that case, install the Company Portal from a supported Chinese app store.

### iOS

For iOS, download the Company Portal from the [Apple App Store](*) to install it on your device.

### macOS

On macOS, install the Company Portal by visiting [Enroll my Mac](*). The download of the installer package will start automatically.

## Sign in to app

There are three methods to sign in to the Company Portal app:

* Using your work or school email and password.
* Using certificate-based authentication.
* We noticed a sign-in from a new device.

For optimal experience, follow the sign-in method recommended or required by your organization.

### Sign in with school or work account

1. Launch the app and select **Sign In**.
2. Enter your work or school email and select **Next**.
3. Enter your password and click **Sign In**.
4. Your credentials are being verified. You will be granted access to the application and your organization's resources upon successful validation.
