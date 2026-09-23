# ⚡ Cloud to Google Drive Transfer Suite (Google Colab)

A collection of high-speed cloud transfer tools running on Google Colab's high-speed datacenter network (100–250 MB/s), transferring files directly to your Google Drive without using your local internet bandwidth.

---

## 🚀 Available Cloud Transfer Notebooks

| Tool | Source | Speed & Acceleration | Launch in Colab |
| :--- | :--- | :--- | :--- |
| **Google Drive to Google Drive** | Google Drive (Folders & Files) | ⚡ 100–250 MB/s (Google Backbone) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dilipparvee2603-ui/mega-to-gdrive-colab/blob/main/gdrive_to_gdrive_colab.ipynb) |
| **MediaFire & Direct Web Links** | MediaFire, CDN, Direct URLs | ⚡ 16x Multi-Connection `aria2c` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dilipparvee2603-ui/mega-to-gdrive-colab/blob/main/mediafire_to_gdrive_colab.ipynb) |
| **MEGA to Google Drive** | MEGA.nz (Files & Folders) | ⚡ MegaCMD Unlimited Bandwidth Engine | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dilipparvee2603-ui/mega-to-gdrive-colab/blob/main/mega_to_gdrive_colab.ipynb) |
| **Torrent to Google Drive** | BitTorrent / Magnet Links | ⚡ Cloud Torrent Downloader | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dilipparvee2603-ui/mega-to-gdrive-colab/blob/main/torrent_to_gdrive_colab.ipynb) |

---

## 🌟 Key Features Across All Tools

- **Zero Local Data Usage**: Files download directly from cloud servers to your Google Drive.
- **Interactive Batch Queue**: Paste multiple links, manage queued items, and track live status.
- **2-Tier Destination Folder Management**: Pick existing movie folders from a dropdown or create new ones, plus subfolders (e.g. `Dialogue`, `Songs`, `4K Clips`).
- **Auto-Pull Titles**: Automatically detects and names movie folders from links.
- **Live Visual Progress Bars**: Real-time percentage, downloaded/total size, transfer speed, and ETA.
- **Anti-Disconnect Keep-Alive**: Built-in silent audio heartbeat to prevent Google Colab idle timeouts.
- **In-Notebook Drive Explorer**: Inspect downloaded files and folder sizes directly inside Colab.
