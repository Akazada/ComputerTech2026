# Unit 2

### 🔍 Lab 1: OS Fingerprint Detector
import platform, os, sys
print("🔍 OS Fingerprint Report OS 指紋報告")
print("=" * 50)
print(f"System 系統: {platform.system()}")
print(f"Release 版本: {platform.release()}")
print(f"Machine 架構: {platform.machine()}")
print(f"Processor 處理器: {platform.processor()}")
print(f"Python: {sys.version}")
print(f"User 使用者: {os.getenv('USER', 'unknown')}")
print(f"\n💡 Colab runs Linux! 你正在用 Linux!")
print(f" Most servers in the world run Linux 全球大部分伺服器都跑 Linux")
