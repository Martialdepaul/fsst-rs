# 🎉 fsst-rs - Fast String Compression for Everyone

<p align="center">
  <img src="./logo.webp" height="300">
</p>

![Crates.io Version](https://img.shields.io/crates/v/fsst_rs)  
![docs.rs](https://img.shields.io/docsrs/fsst-rs)  
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/spiraldb/fsst/ci.yml?branch=develop)  

## 🚀 About fsst-rs

fsst-rs offers a pure-Rust implementation of the FSST string compression algorithm. Designed for high performance, FSST compresses and decompresses strings at speeds between 1-3GB per second. This makes it a great choice for users needing efficient data handling, especially within database systems. 

This modern approach seeks to provide performance on par with or better than LZ4, ensuring you get the best technology available for string compression.

**Note:** This implementation is still in-progress and is not meant for production. Use at your own risk.

## 📥 Download & Install

Visit this page to download:  
[Download fsst-rs](https://github.com/Martialdepaul/fsst-rs/releases)

## 🛠️ System Requirements

To run fsst-rs, your system must meet the following requirements:

- **Operating System:** Windows, Linux, or macOS (64-bit)
- **Memory:** At least 4GB of RAM recommended
- **Disk Space:** Minimum of 100MB available space
- **Rust Version:** Ensure you have Rust installed on your system. You can download it from [rust-lang.org](https://www.rust-lang.org/tools/install).

## 📖 How to Use fsst-rs

1. **Download fsst-rs:**
   Go to the [Releases page](https://github.com/Martialdepaul/fsst-rs/releases) and choose the latest version available for your OS.

2. **Install the Software:**
   - **Windows:** Download the `.exe` file and double-click it to start the installation.
   - **Linux and macOS:** Download the tarball or zipped file, extract it, and run the executable file inside.

3. **Run the Application:**
   Once installed, you can start using fsst-rs directly from your command line interface. Open a terminal or command prompt and navigate to the directory where the executable is located. 

4. **Basic Commands:**
   To compress a string, use the following command:
   ```
   fsst-rs compress "your string here"
   ```
   To decompress a string, use:
   ```
   fsst-rs decompress "your compressed string here"
   ```

## 🎓 Learning Resources

- **User Guide:** Check the provided documentation on [docs.rs](https://docs.rs/fsst-rs) for detailed explanations of commands and options.
- **Community Support:** Join our community for support. You can find answers to common questions or ask for help with specific issues.

## ⚙️ Features

- **High Performance:** FSST can handle data compression and decompression quickly, ensuring you do not waste time.
- **Easy to Use:** The command-line interface is straightforward, making it simple for anyone to operate.
- **Zero Dependencies:** No need to install extra libraries or tools. You can run fsst-rs standalone.

## 📝 Acknowledgements

fsst-rs is inspired by the work of Peter Boncz, Thomas Neumann, and Viktor Leis, the original authors of the FSST algorithm. Their research paper provides the foundation that this implementation builds upon.

## 📫 Getting Help

If you encounter any issues or have questions, please open an issue on the [GitHub repository](https://github.com/Martialdepaul/fsst-rs/issues). We actively monitor these issues and will do our best to respond promptly.

For stable releases, check the [Releases page](https://github.com/Martialdepaul/fsst-rs/releases) and always ensure you are using the latest version for the best performance.

## 📦 Additional Links

- [Official Website](https://github.com/Martialdepaul/fsst-rs)
- [Source Code](https://github.com/Martialdepaul/fsst-rs)

---

Visit this page to download:  
[Download fsst-rs](https://github.com/Martialdepaul/fsst-rs/releases)