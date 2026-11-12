# PMVHavenDownloader-Firefox
Firefox extension to download videos from PMVhaven.com

Download individual videos from PMVHaven.com as MP4, choose resolution, and auto-name files with title, creator and uploader.

**FEATURES:**
- Automatically identifies the video's title, creator and uploader and estimates file sizes.
- Option to download the original, non-transcoded file or specific resolutions.
- Remuxes the download video file to preserve metadata if downloading transcoded files.
- Resolutions can be selected individually or all at once.
- File names can be edited manually.
- Resolution, creator and uploader can be individually selected to appear in the name of saved files.
- Download status and progress is shown.
- Downloads can be paused or canceled individually.
- Automatically retries the download 10 times in case of failure.
- Toolbar icon shows when a download has finished or failed.
- Dark and light mode available (dark is default).
- No data is ever collected or transmitted, all processing is done locally.

**INSTALLATION:**
The extension can be installed from Mozilla at https://addons.mozilla.org/en-US/firefox/addon/pmvhaven-downloader. That will make the installation permanent and allow automatic updates, while a manual installation with the file in this repository only works until Firefox is restarted. For a manual installation, follow the steps below:

- On Firefox, type about:debugging in the address bar.
- Click on _This Firefox_ on the left.
- Click on _Load Temporary Add-on..._
- Locate the .zip file with the extension.
- Click the extension's button on the toolbar or type about:extensions in the address bar and click on the extension's card to pin the icon to the toolbar or allow the extension in incognito windows as desired.

**DISCLAIMERS:**
- I am not affiliated with or otherwise represent PMVHaven.com.
- This extension was coded using Claude AI.
- Neither PMVHaven or I am responsible for any damage or loss that may occur due to the use of this extension.
- This extension is licensed under the Unlicense.
