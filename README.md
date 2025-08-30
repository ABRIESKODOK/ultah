import time
import sys
import os

def loading(text, delay=0.1):
    for char in text:
        sys.stdout.write(char)
        sys.stdout.flush()
        time.sleep(delay)
    print()

os.system("cls" if os.name == "nt" else "clear")

loading("Menghubungkan ke server rahasia...", 0.05)
time.sleep(1)
loading("Mengakses file pribadi...", 0.05)
time.sleep(1)
loading("Mendapatkan password...", 0.05)
time.sleep(1)
loading("⚠️ PASSWORD DITEMUKAN ⚠️", 0.05)
time.sleep(1)
loading("Mengirim ke server... 10%", 0.05)
time.sleep(0.5)
loading("Mengirim ke server... 50%", 0.05)
time.sleep(0.5)
loading("Mengirim ke server... 100%", 0.05)
time.sleep(0.5)
loading("🤣 PRANK!!! Santai aja bro, ini cuma program lucu.", 0.05)
