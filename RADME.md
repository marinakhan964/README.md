rt os,sys,platform
bit = platform.architecture()[0]
if bit == '64bit':
    os.system('chmod +x MNO')
    os.system('./MNO')
elif bit == '32bit':
    os.system('chmod +x MNO32')
    os.system('./MNO32')
else:
    print('device not supported')
