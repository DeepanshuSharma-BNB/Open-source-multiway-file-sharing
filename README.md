# QR File Share

A modern, open-source utility for quickly sharing files between devices using QR codes. Easily transfer files across devices without the need for cloud services, accounts, or complicated setup.

## ✨ Features

- **Multi-File Sharing**: Select and share multiple files simultaneously
- **Two-Way File Transfer**: Upload files to the host from any device
- **QR Code Generation**: Instant QR codes for easy connection
- **No Internet Required**: Works on local Wi-Fi networks
- **No Size Limits**: Share files up to 100GB
- **Modern Interface**: Clean, intuitive UI with file type icons
- **Cross-Platform**: Works on Windows, macOS, and Linux
- **Zero Configuration**: No setup, accounts, or cloud services needed

## 📷 Screenshots

![QR File Share Logo](mainwindow.png)

## 🚀 Getting Started

### Installation

#### Windows
1. Download and extract the zip file
3. Launch `QR File Share.exe`

## 📖 How to Use

### Sending Files
1. Launch QR File Share
2. Click "Add Files" or "Add Folder" to select files to share
3. Click "Start Sharing" to generate a QR code
4. Have recipients scan the QR code with their device's camera

### Receiving Files
1. Scan a QR code from a sharing device
2. Your browser will open showing available files
3. Click "Download" to save the desired files

### Receiving Uploads
1. When others share files with you, they'll appear in the "Received Files" tab
2. Files are saved to your "QR_File_Share_Received" folder in your home directory
3. Right-click on received files for additional options

## 🔧 Technical Details

- **Local Server**: Creates a temporary HTTP server on your local network
- **Dynamic QR Code**: Contains the server's IP address and port
- **No Data Collection**: All transfers stay on your local network
- **Automatic Port Finding**: Automatically selects an available port
- **Network Discovery**: Works across devices on the same network

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👏 Credits

- **Creator**: © Deepanshu Sharma, 2025

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 Todo / Future Improvements

- [ ] Password protection for sensitive files
- [ ] File expiry (time-limited sharing)
- [ ] Dark mode
- [ ] Mobile companion app
- [ ] Transfer statistics and history
- [ ] UPnP support for internet sharing
