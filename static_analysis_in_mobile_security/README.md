# Static Analysis in Mobile Security

## Overview
Android APK reverse engineering and static analysis challenges focused on mobile security assessment techniques.

## Challenges

### Task 0: Android App Security
- **Objective**: Extract hidden flag from APK using static analysis
- **Tools**: JADX, APKTool
- **Target**: APK0
- **Output**: `0-flag.txt`

### Task 1: Device-Backend Communication
- **Objective**: Analyze HTTP communication between mobile app and backend
- **Tools**: OkHttp, Android Logcat, JSON Formatter
- **Target**: APK1
- **Output**: `1-flag.txt`

### Task 2: Reverse Engineering & Optimization
- **Objective**: Reverse engineer compiled code and optimize algorithms
- **Tools**: Ghidra, JADX, Frida, Python, NumPy
- **Target**: APK2
- **Output**: `2-flag.txt`

### Task 3: Native Libraries Analysis
- **Objective**: Analyze JNI integration and native library (.so file) functionality
- **Tools**: JADX, Ghidra, IDA Pro, APKTool, Frida
- **Target**: APK3
- **Output**: `3-flag.txt`

## Environment
- **Platform**: Kali Linux or compatible analysis environment
- **Requirement**: Android emulator or physical device in controlled environment
- **Note**: Local execution only - no online tools permitted

## Key Skills
- APK decompilation and analysis
- Native library reverse engineering
- JNI communication analysis
- Obfuscation detection and bypass
- Network communication analysis
- Performance optimization techniques