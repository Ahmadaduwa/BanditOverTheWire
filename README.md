# OverTheWire Bandit CTF Solutions

This repository contains my complete walkthrough and solutions for the [OverTheWire Bandit](https://overthewire.org/wargames/bandit/) wargame series. Bandit is a beginner-friendly CTF (Capture The Flag) challenge designed to teach Linux command-line skills and basic security concepts.

## 🎯 Overview

The Bandit wargame consists of 34 levels (0-33), each requiring players to find a password to access the next level. This repository documents my journey through all levels, including:

- **Detailed methodologies** for each level
- **Step-by-step solutions** with explanations
- **Screenshots** showing the actual commands and outputs
- **Learning notes** and key concepts discovered

## 📁 Repository Structure

Each level is organized in its own directory following the pattern:
```
Bandit Level X → Level Y/
├── Report.txt          # Detailed solution walkthrough
└── Screenshot.png      # Visual proof of completion
```

## 🚀 Getting Started

### Prerequisites
- SSH client
- Basic Linux command-line knowledge
- Access to the OverTheWire Bandit server

### Connection Details
```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
```

## 📚 Level Progression

| Level | Difficulty | Key Concepts | Status |
|-------|------------|--------------|--------|
| 0→1   | Very Easy  | SSH, File Reading | ✅ Complete |
| 1→2   | Very Easy  | File Reading, Special Characters | ✅ Complete |
| 2→3   | Very Easy  | Hidden Files | ✅ Complete |
| 3→4   | Very Easy  | Hidden Files | ✅ Complete |
| 4→5   | Very Easy  | File Permissions | ✅ Complete |
| 5→6   | Very Easy  | File Permissions | ✅ Complete |
| 6→7   | Very Easy  | File Permissions | ✅ Complete |
| 7→8   | Very Easy  | File Reading, Pipes | ✅ Complete |
| 8→9   | Very Easy  | File Reading, Sorting | ✅ Complete |
| 9→10  | Very Easy  | File Reading, Strings | ✅ Complete |
| 10→11 | Very Easy  | File Reading, Base64 | ✅ Complete |
| 11→12 | Very Easy  | File Reading, ROT13 | ✅ Complete |
| 12→13 | Very Easy  | File Reading, Hexdump | ✅ Complete |
| 13→14 | Very Easy  | SSH Keys | ✅ Complete |
| 14→15 | Very Easy  | SSH Keys | ✅ Complete |
| 15→16 | Very Easy  | SSH Keys | ✅ Complete |
| 16→17 | Very Easy  | SSH Keys, Port Scanning | ✅ Complete |
| 17→18 | Very Easy  | File Comparison | ✅ Complete |
| 18→19 | Very Easy  | SSH Keys, Sticky Bit | ✅ Complete |
| 19→20 | Very Easy  | SUID Binaries | ✅ Complete |
| 20→21 | Very Easy  | SUID Binaries | ✅ Complete |
| 21→22 | Very Easy  | Cron Jobs | ✅ Complete |
| 22→23 | Very Easy  | Cron Jobs | ✅ Complete |
| 23→24 | Very Easy  | Cron Jobs | ✅ Complete |
| 24→25 | Very Easy  | Cron Jobs | ✅ Complete |
| 25→26 | Very Easy  | Shell Escaping | ✅ Complete |
| 26→27 | Very Easy  | Shell Escaping | ✅ Complete |
| 27→28 | Very Easy  | Git | ✅ Complete |
| 28→29 | Very Easy  | Git | ✅ Complete |
| 29→30 | Very Easy  | Git | ✅ Complete |
| 30→31 | Very Easy  | Git | ✅ Complete |
| 31→32 | Very Easy  | Git | ✅ Complete |
| 32→33 | Very Easy  | Shell Escaping | ✅ Complete |
| 33→34 | Very Easy  | Conclusion | ✅ Complete |

## 🛠️ Tools and Techniques Used

Throughout the challenges, I utilized various Linux tools and techniques:

- **File Operations**: `ls`, `cat`, `find`, `grep`, `sort`, `uniq`
- **Text Processing**: `strings`, `base64`, `tr`, `cut`, `awk`, `sed`
- **Network Tools**: `ssh`, `nc`, `nmap`
- **System Administration**: `cron`, `suid`, file permissions
- **Version Control**: `git`
- **Encryption/Encoding**: Base64, ROT13, hexdump

## 🎓 Learning Outcomes

This CTF series taught me:

1. **Linux Command Line Proficiency**: Mastery of essential Unix/Linux commands
2. **File System Navigation**: Understanding of Linux file permissions and structure
3. **Text Processing**: Skills in manipulating and analyzing text data
4. **Network Security**: Basic concepts of SSH, port scanning, and network protocols
5. **System Administration**: Understanding of cron jobs, SUID binaries, and system processes
6. **Version Control**: Practical experience with Git repositories
7. **Problem-Solving**: Systematic approach to debugging and troubleshooting

## 📖 How to Use This Repository

1. **Browse by Level**: Navigate to any specific level directory to see the detailed solution
2. **Read Reports**: Each `Report.txt` contains the complete methodology and solution
3. **View Screenshots**: Screenshots provide visual confirmation of the solutions
4. **Learn Concepts**: Use this as a reference for similar challenges

## 🏆 Completion Status

**✅ COMPLETED**: All 34 levels (0-33) of the main Bandit track have been successfully completed!

The final level (33) contains a congratulatory message from the OverTheWire team, marking the completion of the main Bandit wargame series.

## 🔗 Additional Resources

- [OverTheWire Bandit](https://overthewire.org/wargames/bandit/) - Official challenge page
- [OverTheWire Community](https://overthewire.org/community/) - Community forums and discussions
- [Other OverTheWire Wargames](https://overthewire.org/wargames/) - Additional challenges to try

## 📝 Notes

- All solutions were documented with AI assistance to maintain comprehensive learning records
- Screenshots are included where available to provide visual proof of completion
- This repository serves as both a personal learning log and a reference for others

---

**Happy Hacking!** 🚀

*This repository represents a complete journey through one of the most popular beginner CTF challenges. Whether you're learning cybersecurity concepts or looking for solution references, I hope this documentation proves helpful in your own learning journey.*
