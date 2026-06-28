import os
import time

def simple_virus():
    print("=======================================")
    print("🚨 🦠 VIRUS INITIATED! 🦠 🚨")
    print("=======================================")
    time.sleep(1) # چەند چرکەیەک وەستە
    
    # ڕەشکردنی شاشەکە (بۆ زۆرینەی سیستەمەکان کار دەکات)
    os.system('color 0A') # 0=ڕەش، A=پاستیل/شەهیمی گەرم
    time.sleep(1)
    
    print("\n\n*** YOU HAVE BEEN INFECTED! ***")
    print("This is a simple demonstration virus.")
    print("Run this file again to see it spread!")
    print("=======================================")

if __name__ == "__main__":
    simple_virus()
