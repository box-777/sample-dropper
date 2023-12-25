# sample-dropper
Simple dropper malware containing edited bytes of meterpreter payload<br />
This python program "get_present.exe" writes base64 output of a dropper program into a separate "present.exe". When "present.exe" is launched, it writes "gift.exe" which contains the actual meterpreter payload. This demonstrates the usual behaviours of dropper and multi-staging malware. <br />
The payload was created with a random private LHOST IP so it is non-functional and safe to test. 
At the point of testing on 25 December 2023, it was not detected by Windows Defender. 

![Screenshot_2](https://github.com/box-777/sample-dropper/assets/66173306/0f44ccb5-66ef-483d-9b64-31e9ce3ebf68)


# Resources
[gift box icon](https://www.iconarchive.com/show/small-n-flat-icons-by-paomedia/gift-icon.html) </br>
gift.exe icon art by me 
