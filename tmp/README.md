# **Pilot Pioneer Operation Guide V10.5**

***

## 1.Install

### 1.1 Operating System

Windows 10 (32/64-bit)/Windows 8 (32/64-bit)/Windows 7 (32/64-bit) is required.

### 1.2 Recommended Configuration

- CPU: Intel i7
- Memory: 16.00 GB or above (recommend to use SSD)
- Display: SVGA; Color quality must be 16 bit or higher
- Resolution: 1366*768
- Hard Disk: 500 GB or more of free space
- At least three USB 3.0 interface
- OS: 64-bit Win 7/Win 10 Ultimate or Professional. Ghost or SP3 system downloaded from third-party website is prohibited

### 1.3 Install and Activate Pilot Pioneer

1. Install by **PioneerDriversSetup.exe**. [Click Here to Download](https://drive.google.com/file/d/1LTesmVq-LMRy6Zpg5XhCJv8bNAuT3ao2/view?usp=sharing);

2. Users must select Dongle Driver, and select a dongle type (<font color=#FF0000>default dongle type is Sense Dongle</font>);

   <p align="left">
       <img src="https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/install_1.png" width="50%"/>
   </p>

3. Activate for sense dongle:

   1. <table><tr><td bgcolor=lightgrey><font color=#008000>For Sense hard dongle</font></td></tr></table>
      
      1. Install license activation tool: **Virbox User License Tool**. [Click Here to Download](https://lm.virbox.com/tools.html);
      2. No need to activate, users can run Pilot Pioneer once Virbox is installed.
   2. <table><tr><td bgcolor=lightgrey><font color=#008000>For Sense Soft dongle</font></td></tr></table>
      
      1. Install license activation tool: **Virbox User License Tool** from this link;
      2. Run Virbox, click Cloud/Soft>Local Soft>License Key Activate Online;
   <p align="left">
       <img src="https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/install_2.png" width="50%"/>
   </p>
   <p align="left">
       <img src="https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/install_3.png" width="50%"/>
   </p>
   <p align="left">
       <img src="https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/install_4.png" width="50%"/>
   </p>
      3. Input the activation code and click 'Activate'.

### 1.4 Migrate Sense Soft License

1. Online Migration
   1. **On original PC**
      1. Run Virbox, Click Cloud/Soft>Local Soft>License-key Activate Online-Online-Unbind;
   2. **On target PC**
      1. Run Virbox, click Cloud/Soft>Local Soft>License Key Activate Online;
      2. Input the activation code and click 'Activate'.

### 1.5 Install PioneerTools on the Phone(Optional)

This step is only required for <font color=#0000FF>data services testing </font>when connecting a external mobile phone, such as FTP, iPerf, HTTP test.

1. Install **PioneerTools.apk** on the phone;
2. Enable the USB debugging function under Settings>System&updates>Developer options page in the phone.

---

## 2.Connect Device

### 2.1Qualcomm Chipset-based Phone

1. <font color=#A67D3D>Install **Qualcomm Driver** on PC. :</font><font color=#FF0000> [Click Here to Download](https://drive.google.com/file/d/1gxuN6QOLefDwnZ0mbpT3XzgVA_Ns_Tz8/view?usp=sharing) </font>

   1. Run Qualcomm Driver setup package as administrator;
   2. Select **ETHERNET-DHCP is used to get IPAddress**,and click **Next**;
   3. Click **Next** and install until finish.

2. <font color=#A67D3D>Phone Settings</font>

   Hereinafter, we take Samsung  S20 as an example to illustrate Qualcomm chipset-based phone settings.

   1. Dial ***#0808#** in the phone;
   2. Select **RMNET+DM+MODEM+ADPL(5G) +ADB** in the USB Settings interface;
   3. Enable **Developer options**>**USB debugging**.

3. <font color=#A67D3D>Configure device on PC</font>

   1. Add device
      1. Automatically Detect Device
      2. Manually Add Device
   2. Connect device
      1. Run PioneerTools on the phone;
      2. Click (Connect) in Pilot Pioneer to connect the device to Pilot Pioneer.

### 2.2 HiSilicon Chipset-based Phone

1. <font color=#A67D3D>Install HiSilicon Driver on PC.</font> [Click Here to Download](https://drive.google.com/file/d/1Vv4cjRqJDFwYuVy27owtZxCSPBQa6wUB/view?usp=sharing)
2. <font color=#A67D3D>Phone Settings</font>
   1. Enable Test Port
      1. Dial **\*#\*#2846579159#\*#\*** on the mobile to enter Project Menu Act window
      2. Select **Background setting**->**Usb ports setting**->**Balong Debug mode**
   2. Enable **Developer options**>**USB debugging**
   3. (Optional) Lock SA and NSA Mode Settings
3. <font color=#A67D3D>Configure device on PC</font>
   1. Add device
      1. Automatically Detect Device
      2. Manually Add Device
   2. Connect device
      1. Run PioneerTools on the phone;
      2. Click **Connect** in Pilot Pioneer to connect the device to Pilot Pioneer.

## 3. Workspace and Scenes

### 	3.1 Load Default Scenes

​		Click **Scene** icon to select and load the default scenes. 

### 	3.2 Windows

### 3.2.1 <font color=#008000>Message Window</font>

---

1. ~~<font color=#38B0DE>Set messages:</font> on the Menu bar, choose **Configuration**>**Message Settings**.~~ 

2. <font color=#38B0DE>View message by table:</font>  click **Data**, and double-click **Message** icon corresponding to the logfile under **Network**. 

3. <font color=#38B0DE>View message details:</font> right click a message, and select **Message Details Windows**

   ![图1]()

4. ~~<font color=#38B0DE>Compare messages:</font>~~

   1.  Right click a message, and select **Message Details Windows**
   2. Drag the next message from the **Message** window to **Message Details Window** to compare the difference.

   ![图2]()

5. <font color=#38B0DE>Export messages:</font> right click a message and select **Export** to export all messages in *.csv format.

### 3.2.2 Event Window</font>

---

1. ~~<font color=#38B0DE>Set default events:</font> on the Menu bar, choose **Configuration**>**Event Settings**.~~  

2. ~~<font color=#38B0DE>Customize events:</font> on the Menu bar, choose **Configuration** > **Custom Event Manager**.~~

3. <font color=#38B0DE>View events by table:</font> click **Data**, and double-click  **Event List** corresponding to the logfile under **Network**.

   ![图3]()

4. <font color=#38B0DE>View events by map:</font> double click **Map** icon under **Network**>**Data** pane.操作错误，还需要把event拖入map。

   ![图4]()

5. <font color=#38B0DE>View event details:</font> double click a an event

   ![图5]()

6. <font color=#38B0DE>Export events:</font> right click an event and select **Export** to export all events in *.csv format.

### 3.2.3 <font color=#008000>Parameter Window</font>

----

1. ~~<font color=#38B0DE>Set default parameters:</font> on the Menu bar, choose **Configuration**>**Parameter Settings**.~~ 

2. ~~<font color=#38B0DE>Customize parameters:</font> on the menu bar, choose **Configuration** > **Custom Parameter Manager**.~~

3. <font color=#38B0DE>View parameters by table:</font> double click **Table** icon under **Network**>**Data** pane.

   ![图6]()

4. <font color=#38B0DE>View parameters by bar chart:</font> double click **Bar Chart** icon under **Network**>**Data** pane.

   ![图7]()

5. <font color=#38B0DE>View parameters by line chart:</font> double click **Line Chart** icon under **Network**>**Data** pane.

   ![图8]() 

6. <font color=#38B0DE>View parameters by map:</font> double click **Map** icon under **Network**>**Data** pane.

   ![图9]()

7. <font color=#38B0DE>Compare parameters:</font> pull down the arrow at the top right corner of map window, select **Parameters Comparison**, and select multiple parameters to compare.

   ![图10]()

8. <font color=#38B0DE>Export parameters:</font> right click the parameter table window and select **Save as Template**.

   ![图11]()

### 3.2.4 <font color=#008000>Map Window</font>

----

Users may view parameter(see section 3.2.3), event (see section3.2.2), cell site and map information in the map window.

**<font color=#A67D3D>The following map file formats are supported:</font>** 

```
·      MapInfo (*.Tab, *.Mif, *.Gst) 

·      Image (*.bmp, *.jpg,*.gif, *.tif,*.png, *.jpeg) 

·      Terrain (*.TMB, *TMD),

·      AutoCAD (*.Dxf) 

·      USGS (*.DEM),

·      ArcInfo (*.Shp)

·      KML (*.kml, *.kmz)

·      ZDF (*.zdf) 

·      iBWave(*.ibwc) 
```



1. <table><tr><td bgcolor=lightgrey><font color=#0000FF>Outdoor test</font></td></tr></table>

   1. Set cell&site information: click the **Cell Settings** icon from the toolbar of the Map window.

   ![图12]()

   2. Display site information: 
      1. Click **Layer**, right-click **Site** to select **Import**, and select site file to import
      2. Select and drag the imported site file on the **Layer** tab page into the **Map** window.

   ![图13]()

   3. Load online map: click the **Open Map Layer** icon on the toolbar on the Map window and select a map type as required. 

   4. Import offline map:

      1. Click **Layer** tab, and then double click the offline map format as required under **Geo Map**.

      2. Select an offline map from local computer.

      3. Drag the imported offline map to the **Map** window.

   5. Display serving cell line: click the **Cell line linking** drop down arrow on the map window and select a corresponding display mode as required.

      ![图14]()

   6. Compare data: click **Lay Control** icon, and set the X or Y axis offset value of one data file to 50.

       ![图15]()

2. <table><tr><td bgcolor=lightgrey><font color=#0000FF>Indoor positioning test</font></td></tr></table>

   1. Start the test and record test data.

   2. Import indoor map: click **Layer** tab, and then double click the offline map format as required under **Indoor Map**.
   3. Drag the imported indoor map from **Layer** tab to the **Map** window.
   4. Click the **Pinpointing** drop-down arrow in **Map** window, and select **Pinpoint**.
   5. Pinpoint a test route on the indoor map.

    ![图16]()

----

## 4.Configure Test Plans

**<font color=#A67D3D>The supported test services include:</font>** 

| <font color=#0000FF>Voice Test</font>                        | <font color=#0000FF>Data Test</font> | <font color=#0000FF>Value Added Test</font> | <font color=#0000FF>Scanner Test</font>                      |
| ------------------------------------------------------------ | ------------------------------------ | ------------------------------------------- | ------------------------------------------------------------ |
| Call                                                         | FTP Download/Upload                  | SMS                                         | Pilot:                                                                              *5G NR Pilot Scan                                                     *NB-IoT Pilot Scan                                                         *LTE Pilot Scan |
| VoIP                                                         | Multi FTP Download/Upload            | MMS                                         | CW                                                           |
| MOS (POLQA/PESQ)[video tutorial](https://youtu.be/OhwKnLFAn3k) | HTTP Download/Upload/Page            | Receive/Send Email                          | Spectrum                                                     |
| MOS Self-Check                                               | Video Streaming/Telephony/Play       | WAP Page/Download                           | Color Code                                                   |
| MOS Self-Loop                                                | Attach/Idle                          | Facebook                                    | Blind                                                        |
| Manual MOS                                                   | PDP/Ping/Iperf                       | Skype                                       | EPS                                                          |
| PPP Dial                                                     | LET Power                            |                                             |                                                              |
| Mobile Terminated Call Test                                  | Speed Test                           |                                             |                                                              |
|                                                              | DNS Lookup                           |                                             |                                                              |
|                                                              | Trace Route                          |                                             |                                                              |
|                                                              | PBM/IDT                              |                                             |                                                              |
|                                                              | UDP/eLTE UDP                         |                                             |                                                              |
|                                                              | NR Registration                      |                                             |                                                              |

### 4.1 Add/Edit Test Plans

1. Click **Test**, click a device, and then the default test plan templates will be displayed under **Test Plan**.

   ![图17]()

2. If the required test service is not available under **Test Plan**, right-click a test template and select **Add** to select the test service type.

   ![图18]()

3. Right-click a test template and select **Edit** to configure test plan.

   ![图19]()

### 4.2 Configure a Loop Test

1. Add multiple test plans and configure required information .
2. Select multiple test plans as required. This way, Pilot Pioneer will execute the selected test services by sequence.

## 4.3 Configure a Multi-Service Test

1. Right-click a test template and select **Add**.
2. Select multiple services (at least two) for Multi-service tests, and then select **Multi-RAB** and **OK**.
3. Double click the added test plan to configure required information, and click **OK**.

![图20]()

---

## 5.Collect Logfile

## 5.1 Configure Logfile Collection

Click Menu button on the top right corner, and select **Configuration**>**Options** to configure:

```
* data storage path/format
* data partition
* data collection
```

## 5.2 Connect Mode

Click the **Connect** icon on the toolbar to display current test information in real time without saving any logfile.

![图21]()

## 5.3 Recording Mode

1. Click the **Start Recording** icon on the toolbar to save logfiles in the <font color=#0000FF>**ddib** </font>(default) and  <font color=#0000FF>**rcu** </font>formats. 

   ![图22]()

2. <font color=#38B0DE>Configure record:</font> click the **Configuration** button on the **Save Logfile** window.

   ![图23]()

3. <font color=#38B0DE>Configure test information:</font>  click the **Test** button on the **Save Logfile** window.

   ![图24]()

4. <font color=#38B0DE>Swap logfiles:</font>  Click the **Swap Logfile** icon on the toolbar to swap log files

## 5.4 Force Command

1. Click the **Test** tab and select a device to execute the force command.

2. Click **Force Set**. 

3. Select a force command as required.

4. Set the force command based on the information.

5. Click the button beside the force command to send the command.

   ![图25]()

## 5.5 AT Command

1. Click the phone under **Test** navigation pane, and click **AT Cmd**>  **+ **                              beside **Open AT Cmd Window** .

2. Select a device which will receive the AT command from the **Device List** drop-down list box.

3. Click **Connect** to connect to the AT port of the device.

4. Select an AT command as required from the Default drop-down list box.

5. Under the **CMD** column, enter an AT command.

6. Click **Send** to send the AT command. 

7. Set interval to send AT command(s) sequentially in a cycle manner under **Start cycle to send interval** option.

## 6.Replay Logfile

1. Select an imported logfile, and open windows (e.g. Message or Table) as required. 

2. Click the **Set Playback Data** button on the toolbar to replay logfile.

   ![图26]()

## ~~6.1 Copy Logfiles~~

1. ~~Select the start point in the log file replay window or associated windows and then click the **Copy Data** icon.~~

2. ~~Select the end point in the log file replay window or associated windows, and then click the **Copy Data** icon.~~

3. ~~In the window that is displayed, rename the file and set the file save directory for the new log file.~~

## ~~6.2 Synchronize Logfile~~

1. ~~Click the **Logfile Synchronization** icon to enter the **Logfile Synchronization** window.~~

2. ~~Select logfiles (at least two), and click the **Add** button to add the files to the right pane, and click **OK**.~~

## 7.Generate Statistics Report

**<font color=#A67D3D>The supported statistics reports:</font>** 

![图27]()

1. <font color=#38B0DE>Open statistics report window:</font> click **Report** on the navigation pane.

2. <font color=#38B0DE>Select a report template:</font> 

   1. Double click the report name to enter its settings page.
   2. Click the **Open Template** icon on the settings page.

   ![图28]()

3. <font color=#38B0DE>Load data files:</font>  select data files on the left pane of settings page and click **>** icon to load data files to the right pane. 

4. <font color=#38B0DE>Generate statistics reports:</font> click **Generate**.

5.  <font color=#38B0DE>View statistics results:</font>

   1. The statistics report will be automatically opened after successful generation. 
   2. Double click a report name at the bottom left corner on the navigation pane to open the report and view detailed information.

   ![图29]()

## 8.FAQ

## 8.1 PioneerTools 

### 8.1.1 How to deal with always “Expired (AuthFailed)” license status?

o  Uninstall PioneerTools app from the handset.

o  Delete all past PioneerTools setup package folders.

o  Contact DingLi technical support to obtain the latest PioneerTools setup package.

o  Reinstall the latest PioneerTools.

### 8.1.2 How to deal with always “Waiting” service status?

  Check whether the PioneerTools is connected? 

o  Check whether the USB debugging function is enabled?

o  Check whether the handset port works?

o  Check whether there is ADB interface in the **Computer Management** window?

o  Check the connection between handset and computer.

o  Check whether the ADB interface is used by other programs through the following methods:

1) Set the system environment variables **ANDROID_ADB_SERVER_PORT**:

Hereinafter we take Windows 7 as an example to illustrate the settings.

Right click **Computer** and select **Properties**>**Advanced system settings**>**Environment Variables**>**New** to add a new environment variable (Variable name: **ANDROID_ADB_SERVER_PORT**, Variable value: **7035**).

![图30]()

2.  Check whether the default ADB interface 7035 is used by other programs:

   ![*](file:///C:/Users/JINGYI~1.ZEN/AppData/Local/Temp/msohtmlclip1/01/clip_image001.gif)    Enter the command “**adb nodaemon server**” in the CMD window, and if the result “**cannot bind 'tcp: 7035**” returns, it means the ADB 7035 interface is used by other programs.

   ![*](file:///C:/Users/JINGYI~1.ZEN/AppData/Local/Temp/msohtmlclip1/01/clip_image001.gif)    Find out which program uses the ADB 7035 interface: Enter the command “**netstat -ano | findstr "7035"**”, and if the result “**TCP  127.0.0.1:7035   0.0.0.0:0  LISTENING    2832**” returns, it means the ADB 7035 interface is used by program 2832.

3. Terminate the program that uses ADB interface:

   ![*](file:///C:/Users/JINGYI~1.ZEN/AppData/Local/Temp/msohtmlclip1/01/clip_image001.gif)    Open **Windows Task Manager** window, and click **View** to select **Select Columns**.

   ![图31]()

   ![*](file:///C:/Users/JINGYI~1.ZEN/AppData/Local/Temp/msohtmlclip1/01/clip_image001.gif)    Select **PID (Process Identifier)** to view each program’s PID in the **Windows Task Manager** window.

   ![图32]()

   ![*](file:///C:/Users/JINGYI~1.ZEN/AppData/Local/Temp/msohtmlclip1/01/clip_image001.gif)    Right click the program and select **End Process Tree** to terminate the program that uses ADB 7035 interface.

   ![*](file:///C:/Users/JINGYI~1.ZEN/AppData/Local/Temp/msohtmlclip1/01/clip_image001.gif)    Restart the server through entering the command “**adb start-server**”. If the results “*** daemon not running. starting it now on port 7035\***

   ***daemon started successfully**” returns in the CMD window, it means restarting the server successfully.

## 8.2  HiSilicon Chipset-based Phone

### 8.2.1 No message display after the phone is connected to Pilot Pioneer?

o  Check whether the phone port configuration is correct? 

o  Switch the phone's Balong port to non-test port, restart the handset, switch the non-test port to Balong port, and reconnect the handset to the computer.

### 8.2.2 Phone fails to connect to Pilot Pioneer?

o  Check whether the phone port configuration is correct? 

o  Ensure that the computer may access to external network.

o  Close Pilot Pioneer, and delete **HiSD.dat**, **HiSL.dat** and **HiSR.dat** files under the path **C:\Windows\SysWOW64\Pioneer** (64-bit windows)/ **C:\Windows\System32\Pioneer** (32-bit windows) and Pilot Pioneer root directory.

o  Ensure that no other programs that will use the HiSilicon proxy are running, e.g. PHU Smart. If the programs are currently running, please close it and restart the handset. If the phone still fails to connect to Pilot Pioneer, restore the phone to factory settings.

## 8.3 Forcing Function under NSA Network

### 8.3.1 HiSilicon Chipset-based Terminal

If 5G HiSilicon chipset-based terminal is locked to LTE Band, it cannot access to 5G NSA network. 

If 5G HiSilicon chipset-based terminal is locked to LTE frequency or PCI, it can access to 5G NSA network.

### 8.3.2 Qualcomm Chipset-based Terminal

If 5G Qualcomm chipset-based terminal is locked to LTE frequency, it cannot access to 5G NSA network. 

If 5G Qualcomm chipset-based terminal is locked to LTE BAND or PCI, it can access to 5G NSA network.

## 8.4 How to deal with expired offline usage time?

**Problem**: when launching Pilot Pioneer, a dialog box appears and prompts the user that Pilot Pioneer offline usage time has expired.

**Solutions**: 1. Make sure that the computer is connected to the internet, and then click **Retry** in the dialog box that appears. 2. If the problem still exists even after applying method 1 above, just contact DingLi technical support to update the Pilot Pioneer version (V10.4.0.90 onwards)

## 8.5 Reasons for Low MOS Score

1. The reasons for Low MOS score:

(1)  Audio cable is not connected properly.

(2)  The phones volume does not adjust to the maximum

(3)  The phones were not set to VoLTE HD or SD mode.

(4)  The phones were fully charged which would cause low MOS score.

(5)  Check whether the audio file’s sound is indistinct (rustling sound)? If yes, change to connect to other USB interfaces. Please follow the instruction below to check the audio file’s sound:

·     Right click the data log under **Data** pane, and select **Open Log Path**. 

·     Click the last data folder

·     Click the **MOS** folder

·     Click the **Normal** folder

·     Copy the audio file to the music software and play it.







