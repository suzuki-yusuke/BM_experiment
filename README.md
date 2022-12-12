# BM_measurement-control

## Requirement
* The codes were developed and tested on LabVIEW 2013 for BM1 and LabVIEW 2017 for BM3 on Windows 7.
* Because the codes contain plugins of [IDS SOFTWARE SUITE](https://jp.ids-imaging.com/ids-software-suite.html), [download](https://en.ids-imaging.com/download-details/AB00430.html), install and integrate the olugins into your LabVIEW environment. we confirmed uEye-Full-4401-64-WHQL was compatible.


## Usage
0. Create a project folder with the structure of the ***demo*** folder.
1. Open main function, ***160505-BM.vi*** for BM1, ***170731-BM.vi*** for BM3.
2. Input ***Project Path*** in main function, as ```<<path to the project folder>>\habituation``` or ```<<path to the project folder>>\training``` or ```<<path to the project folder>>\probe_test```
3. Set ***Day***, ***Trial***, ***ID***. if Day 1, Trial 2, animal ID 3, set 1, 2, 3, respectively.
4, Choose ***Phase***.
5. Run. A popup window will appear, Confirm ***State*** becomes ***Ready***
6. Push ***START***, confirm that the lift rises. If the lift stopped to rise, push ***UP2TOP***. Recording begins.
7. In the training phase, You have to srop the recording by pushing ***STOP*** button in the popup window. Otherwise, recording will be automatically stopped if recording time exceed certain duration.
8. Push ***End*** button in main function. The trial is ended. 
9. Confirm that positional data in .txt or movie data in .avi is saved at the folder ~/d*/t*/#*. In the habituation phase, no movie data were saved.

 
## Author

* name
* affiliation
* e-mail
 
## License

