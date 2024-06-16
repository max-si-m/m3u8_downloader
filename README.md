### m3u8 Downloader

#### Requirements
- FFmpeg installed and added to the system's PATH

#### Usage

To use the `m3u8_downloader` file, follow these steps:

1. Make sure you have FFmpeg installed and added to the system's PATH. If not, refer to the FFmpeg documentation for installation instructions.

2. Open a terminal or command prompt.

3. Navigate to the directory where the `m3u8_downloader` file is located or make it executable globally.

4. Run the `m3u8_downloader` script by executing the following command:

  ```
  m3u8_downloader <URL> <out file name>
  ```

  This will start the m3u8 downloader with the URL of the m3u8 file you want to download.

  The script will then download the video segments specified in the m3u8 file and merge them into a single video file using FFmpeg.

6. Once the download and merging process is complete, you will find the downloaded video file in current directory.

That's it! You have successfully used the `m3u8_downloader` file to download and merge m3u8 video files.

##### Note

- Please note that this script has been tested on macOS only.
- Output file is in MP4 with compression with intent to save place, if you need you can change that.
