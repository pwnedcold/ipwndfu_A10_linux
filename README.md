## How to ?

use the fork

```bash
1.download linux mint 19.1 iso and make usb with it
boot to live booting and open the terminal and run *sudo apt update* then sudo apt install ca-certificates*

the reason installing the latest ca-certificates is for checkra1n repo , i use checkra1n to enter dfu and exit it immediately exit when it says device on dfu  why not its just easier
dont update the liveboot tho

2.download the fork and extract it , open the extracted folder on terminal and run python2 ipwndfu -p or sudo python2 ipwndfu -p  whichever works , if device pwnedfu worked then run python2 rmsigchks.python2


it can take few tries but it works
if doesent work try also execute the ipwndfu command immediately when device on dfu 






if it still doesent work , then try the ipwndfu fork from Hack Different https://github.com/hack-different/ipwndfu
```
    

credits to LinusHenze,Cryptic,Nyuszika7h(the one who made the gist on downgrading and has the fork) idk anyone else to credit
