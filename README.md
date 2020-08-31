# toupcam

Python interface to ToupCam cameras.

DLLs & .so files where put in the same x64 floder.
These newer files where brought from the toupcam SDK on Touptek official site.

Changes were made to camera.py :
Changed the way of Getting a camera from 
lib.Toupcam_Open to lib.Toupcam_OpenByIndex
No more multi-camera problems.

Size was already fixed by the main author of the repo. 

    cam0 = ToupCamCamera(cid=0,size=(2560,1922))  #L3CMOS05100KPA
    cam1 = ToupCamCamera(cid=1,size=(1280,960))   #UCMOS05100KPA

[ToupCam documentation](docs.md)
