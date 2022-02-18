# **Pilot Pioneer Operation Guide V10.5**

***

# 1.Install

## 1.1 Operating System

Windows 10 (32/64-bit)/Windows 8 (32/64-bit)/Windows 7 (32/64-bit) is required.

## 1.2 Recommended Configuration

- CPU: Intel i7
- Memory: 16.00 GB or above (recommend to use SSD)
- Display: SVGA; Color quality must be 16 bit or higher
- Resolution: 1366*768
- Hard Disk: 500 GB or more of free space
- At least three USB 3.0 interface
- OS: 64-bit Win 7/Win 10 Ultimate or Professional. Ghost or SP3 system downloaded from third-party website is prohibited

## 1.3 Install and Activate Pilot Pioneer

1. Install by **PioneerDriversSetup.exe**. [Click Here to Download](https://drive.google.com/file/d/1LTesmVq-LMRy6Zpg5XhCJv8bNAuT3ao2/view?usp=sharing);

2. Users must select Dongle Driver, and select a dongle type (default dongle type is Sense Dongle);

   <p align="left">
       <img src="https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/install_1.png" width="50%"/>
   </p>

3. Activate for sense dongle:

   1. For Sense hard dongle
      1. Install license activation tool: **Virbox User License Tool**. [Click Here to Download](https://lm.virbox.com/tools.html);
      2. No need to activate, users can run Pilot Pioneer once Virbox is installed.
   2. For Sense Soft dongle
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

## 1.4 Migrate Sense Soft License

1. Online Migration
   1. **On original PC**
      
      1. Run Virbox, Click Cloud/Soft>Local Soft>License-key Activate Online>Online-Unbind;
      
         ![figure 1-1](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure1-1.png)
      
         ![figure 1-2](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure1-2.png)
      
   2. **On target PC**
      
      1. Run Virbox, click Cloud/Soft>Local Soft>License Key Activate Online;
      
      2. Input the activation code and click 'Activate'.
      
         ![figure 1-3](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure1-3.png)

## 1.5 Install PioneerTools on the Phone(Optional)

This step is only required for <font color=#0000FF>data services testing </font>when connecting a external mobile phone, such as FTP, iPerf, HTTP test.

1. Install **PioneerTools.apk** on the phone;

2. Enable the USB debugging function under Settings>System&updates>Developer options page in the phone.

   ![figure 1-4](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure1-4.png)

---

# 2.Connect Device

## 2.1Qualcomm Chipset-based Phone

1. Install **Qualcomm Driver** on PC.<font color=#FF0000> [Click Here to Download](https://drive.google.com/file/d/1gxuN6QOLefDwnZ0mbpT3XzgVA_Ns_Tz8/view?usp=sharing) </font>

   1. Run Qualcomm Driver setup package as administrator;

   2. Select **ETHERNET-DHCP is used to get IPAddress**,and click **Next**;

   3. Click **Next** and install until finish.

      ![figure 2-1](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure2-1.png)

2. Phone Settings

   Hereinafter, we take Samsung  S20 as an example to illustrate Qualcomm chipset-based phone settings.

   1. Dial ***#0808#** in the phone;

      ![figure 2-2](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure2-2.png)

   2. Select **RMNET+DM+MODEM+ADPL(5G) +ADB** in the USB Settings interface;

      ![figure 2-3](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure2-3.png)

   3. Enable **Developer options**>**USB debugging**.

      ![figure 2-4](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure2-4.png)

      ![figure 2-5](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure2-5.png)

3. Configure device on PC

   1. Add device
      
      - Automatically Detect Device
      
      ![figure 2-6](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure2-6.png)
      
      - Manually Add Device
      
        ![figure 2-7](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure2-7.png)
      
   2. Connect device
      1. Run PioneerTools on the phone;
      
         ![figure 2-8](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure2-8.png)
      
      2. Click **Connect** in Pilot Pioneer to connect the device to Pilot Pioneer.
      
         ![figure 2-9](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure2-9.png)

## 2.2 HiSilicon Chipset-based Phone

1. Install HiSilicon Driver on PC. [Click Here to Download](https://drive.google.com/file/d/1Vv4cjRqJDFwYuVy27owtZxCSPBQa6wUB/view?usp=sharing)

2. Phone Settings
   1. Enable Test Port
      1. Dial **\*#\*#2846579159#\*#\*** on the mobile to enter Project Menu Act window.
      
      2. Select **Background setting**->**Usb ports setting**->**Balong Debug mode**
      
         ![figure 2-10](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure2-10.png)
      
   2. Enable **Developer options**>**USB debugging**
   
      ![figure 2-11](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure2-11.png)
   
   3. (Optional) Lock SA and NSA Mode Settings
   
      ![figure 2-12](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure2-12.png)
   
3. Configure device on PC
   1. Add device
      
      - Automatically Detect Device
      
      - Manually Add Device
      
   2. Connect device
      1. Run PioneerTools on the phone;
      2. Click **Connect** in Pilot Pioneer to connect the device to Pilot Pioneer.

# 3. Workspace and Scenes

## 	3.1 Load Default Scenes

​		Click **Scene** icon to select and load the default scenes. 

![figure 3-1](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure3-1.png)

## 3.2 Windows

### 3.2.1 Message Window

- View message by table:  select data and double click **Message** icon under **Network**>**Data** pane. 

- View message details: right click a message, and select **Message Details Windows**

![figure3-2](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure3-2.png)

- Export messages: right click a message and select **Export** to export all messages in *.csv format.

### 3.2.2 Event Window

- View events by table: select data and double click **Event** icon under **Network**>**Data** pane.

![figure3-3](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure3-3.png)

- View events by map: select data and double click **Map** icon under **Network**>**Data** pane, and drag the event to the map window. 

![figure3-4](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure3-4.png)

- View event details: double click a an event

![figure3-5](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure3-5.png)

- Export events: right click an event and select **Export** to export all events in *.csv format.

### 3.2.3 Map Window

----

Users may view parameter(see section 3.2.3), event (see section3.2.2), cell site and map information in the map window.

1. Outdoor test

   - Set cell&site information: click the **Cell Settings** icon from the toolbar of the Map window.

   ![figure3-6](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure3-6.png)

   - Display site information: 

   ​        -  Click **Layer**, right-click **Site** to select **Import**, and select site file to import

   ​        -  Select and drag the imported site file on the **Layer** tab page into the **Map** window.

   ![figure3-7](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure3-7.png)

   - Load online map: click the **Open Map Layer** icon on the toolbar on the Map window and select a map type as required. 

   - Import offline map:

   1. Click **Layer** tab, and then double click the offline map format as required under **Geo Map**.

   2. Select an offline map from local computer.

   3. Drag the imported offline map to the **Map** window.

   - Display serving cell line: click the **Cell line linking** drop down arrow on the map window and select a corresponding display mode as required.

   ![figure3-8](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure3-8.png)

   - Compare data: click **Lay Control** icon, and set the X or Y axis offset value of one data file to 50.

   ![figure3-9](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure3-9.png)

2. Indoor positioning test

   1. Start the test and record test data.

   2. Import indoor map: click **Layer** tab, and then double click the offline map format as required under **Indoor Map**.
   3. Drag the imported indoor map from **Layer** tab to the **Map** window.
   4. Click the **Pinpointing** drop-down arrow in **Map** window, and select **Pinpoint**.
   5. Pinpoint a test route on the indoor map.

    ![figure3-10](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure3-10.png)

## 3.3 Parameters

- Add parameters: click **+** icon beside **Parameter List** under **Param** pane and select parameters to add.

  ![figure3-11](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure3-11.png)

- View parameter by table: select data under **Data** pane, right click a parameter as required under **Param** pane and select **Table** to display it. 

![figure3-12](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure3-12.png)

- View parameter by map: select data under **Data** pane, right click a parameter as required under **Param** pane and select **Map** to display it.

![figure3-13](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure3-13.png)

- View parameter statistics information: select data under **Data** pane, right click a parameter as required under **Param** pane and select **Statistics** to display it.

  ![figure3-14](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure3-14.png)

- View parameters by line chart: select data under **Data** pane, right click a parameter as required under **Param** pane and select **Line Chart** to display it.

![figure3-15](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure3-15.png) 

- Compare parameters: pull down the arrow at the top right corner of map window, select **Parameters Comparison**, and select multiple parameters to compare.

![figure3-16](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure3-16.png)

- Export parameters: right click the parameter table window and select **Save as Template**.

  ![figure3-17](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure3-17.png)

----

# 4.Configure Test Plans

**The supported test services include:** 

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

## 4.1 Add/Edit Test Plans

- Click **Test**, click a device, and then the default test plan templates will be displayed under **Test Plan**.

![figure4-1](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure4-1.png)

- If the required test service is not available under **Test Plan**, right-click a test template and select **Add** to select the test service type.

![figure4-2](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure4-2.png)

- Right-click a test template and select **Edit** to configure test plan.

![figure4-3](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure4-3.png)

## 4.2 Configure a Loop Test

1. Add multiple test plans and configure required information .
2. Select multiple test plans as required. This way, Pilot Pioneer will execute the selected test services by sequence.

## 4.3 Configure a Multi-Service Test

1. Right-click a test template and select **Add**.
2. Select multiple services (at least two) for Multi-service tests, and then select **Multi-RAB** and **OK**.
3. Double click the added test plan to configure required information, and click **OK**.

![figure4-4](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure4-4.png)

---

# 5.Collect Logfile

## 5.1 Configure Logfile Collection

Click Menu button on the top right corner, and select **Configuration**>**Options** to configure:

```
* data storage path/format
* data partition
* data collection
```

## 5.2 Connect Mode

Click the **Connect** icon on the toolbar to display current test information in real time without saving any logfile.

![figure5-1](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure5-1.png)

## 5.3 Recording Mode

- Click the **Start Recording** icon on the toolbar to save logfiles in the <font color=#0000FF>**ddib** </font>(default) and  <font color=#0000FF>**rcu** </font>formats. 

![figure5-2](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure5-2.png)

- Configure record: click the **Configuration** button on the **Save Logfile** window.

![figure5-3](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure5-3.png)

- Configure test information:  click the **Test** button on the **Save Logfile** window.

![figure5-4](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure5-4.png)

- Swap logfiles: Click the **Swap Logfile** icon on the toolbar to swap log files

## 5.4 Force Command

1. Click the **Test** tab and select a device to execute the force command.

2. Click **Force Set**. 

3. Select a force command as required.

4. Set the force command based on the information.

5. Click the button beside the force command to send the command.

   ![figure5-5](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure5-5.png)

## 5.5 AT Command

1. Click the phone under **Test** navigation pane, and click **AT Cmd**>  **+** beside **Open AT Cmd Window** .

2. Select a device which will receive the AT command from the **Device List** drop-down list box.

3. Click **Connect** to connect to the AT port of the device.

4. Select an AT command as required from the Default drop-down list box.

5. Under the **CMD** column, enter an AT command.

6. Click **Send** to send the AT command. 

7. Set interval to send AT command(s) sequentially in a cycle manner under **Start cycle to send interval** option.

# 6.Replay Logfiles

1. Select an imported logfile, and open windows (e.g. Message or Table) as required. 

2. Click the **Set Playback Data** button on the toolbar to replay logfile.

   ![figure6-1](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure6-1.png)

# 7. Export Logfiles

1. Enter the Export Logfile window: On the Menu bar, choose **File**>**Export Logfile**.

   ![figure 7-1](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure7-1.png)

2. Click **Add** or **Delete** to add or delete logfiles as required.

3. Click **Template Manager** and **Settings** to perform configuration for log file export.

4. Click **Export** after setting the template.

   ![figure 7-2](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure7-2.png)

# 8. Merge/Partition Logfiles

On the Menu bar, choose **Tool**>**Merge/Partition Logfiles** to enter the **Merge/Partition Logfiles** window. 

![figure 8-1](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure8-1.png)

## 8.1 Merge Logfiles

1. Click **Import Logfile** to add logfiles that need to be merged.

2. Select logfiles to be merged on the left pane of the **Merge/Partition Logfiles** window.

3. Click **...** button at the bottom to select a directory to save the merged logfile.

4. Click **Merge** to merge two or more *rcu, *ddib and *.dcf logfiles.

   ![figure 8-2](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure8-2.png)

## 8.2 Partition Logfiles

1. Click **Import Logfile** to add logfiles that need to be partitioned.

2. Select logfiles to be partitioned in the **Merge/Partition Logfiles** window.

3. Click **Partition** to enter the **Partition Logfile** window.

   ![figure 8-3](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure8-3.png)

4. Select partition conditions.

5. Click **OK** to partition one or multiple *.rcu, *.ddib or *.dcf logfiles. 

   ![figure 8-4](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure8-4.png)

# 9.Generate Statistics Report

**The supported statistics reports:** 

![figure9-1](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure9-1.png)

- Open statistics report window: click **Report** on the navigation pane.

- Select a report template:

1. Double click the report name to enter its settings page.
2. Click the **Open Template** icon on the settings page.

![figure9-2](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure9-2.png)

- Load data files:  select data files on the left pane of settings page and click **>** icon to load data files to the right pane. 

- Generate statistics reports: click **Generate**.

- View statistics results:

​       - The statistics report will be automatically opened after successful generation. 

​       - Double click a report name at the bottom left corner on the navigation pane to open the report and view detailed information.

![figure9-3](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure9-3.png)

# 10.FAQ

## 10.1 PioneerTools 

### 10.1.1 How to deal with always “Expired (AuthFailed)” license status?

o  Uninstall PioneerTools app from the handset.

o  Delete all past PioneerTools setup package folders.

o  Contact DingLi technical support to obtain the latest PioneerTools setup package.

o  Reinstall the latest PioneerTools.

### 10.1.2 How to deal with always “Waiting” service status?

  Check whether the PioneerTools is connected? 

o  Check whether the USB debugging function is enabled?

o  Check whether the handset port works?

o  Check whether there is ADB interface in the **Computer Management** window?

o  Check the connection between phone and computer.

o  Check whether the ADB interface is used by other programs through the following methods:

1) Set the system environment variables **ANDROID_ADB_SERVER_PORT**:

Hereinafter we take Windows 7 as an example to illustrate the settings.

Right click **Computer** and select **Properties**>**Advanced system settings**>**Environment Variables**>**New** to add a new environment variable (Variable name: **ANDROID_ADB_SERVER_PORT**, Variable value: **7035**).

![figure10-1](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure10-1.png)

2.  Check whether the default ADB interface 7035 is used by other programs:

   - Enter the command “**adb nodaemon server**” in the CMD window, and if the result “**cannot bind 'tcp: 7035**” returns, it means the ADB 7035 interface is used by other programs.

   - Find out which program uses the ADB 7035 interface: Enter the command “**netstat -ano | findstr "7035"**”, and if the result “**TCP  127.0.0.1:7035   0.0.0.0:0  LISTENING    2832**” returns, it means the ADB 7035 interface is used by program 2832.

3. Terminate the program that uses ADB interface:

   - Open **Windows Task Manager** window, and click **View** to select **Select Columns**.

   ![figure10-2](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure10-2.png)

   - Select **PID (Process Identifier)** to view each program’s PID in the **Windows Task Manager** window.

   ![figure10-3](https://cdn.jsdelivr.net/gh/Brandoooon/pioneer_doc/img/figure10-3.png)

   - Right click the program and select **End Process Tree** to terminate the program that uses ADB 7035 interface.

   - Restart the server through entering the command “**adb start-server**”. If the results “*** daemon not running. starting it now on port 7035\***

   ***daemon started successfully**” returns in the CMD window, it means restarting the server successfully.

## 10.2  HiSilicon Chipset-based Phone

### 10.2.1 No message display after the phone is connected to Pilot Pioneer?

- Check whether the phone port configuration is correct? 

- Switch the phone's Balong port to non-test port, restart the handset, switch the non-test port to Balong port, and reconnect the phone to the computer.

### 10.2.2 Phone fails to connect to Pilot Pioneer?

- Check whether the phone port configuration is correct? 

- Ensure that the computer may access to external network.

- Close Pilot Pioneer, and delete **HiSD.dat**, **HiSL.dat** and **HiSR.dat** files under the path **C:\Windows\SysWOW64\Pioneer** (64-bit windows)/ **C:\Windows\System32\Pioneer** (32-bit windows) and Pilot Pioneer root directory.

- Ensure that no other programs that will use the HiSilicon proxy are running, e.g. PHU Smart. If the programs are currently running, please close it and restart the handset. If the phone still fails to connect to Pilot Pioneer, restore the phone to factory settings.

## 10.3 Forcing Function under NSA Network

### 10.3.1 HiSilicon Chipset-based Terminal

If 5G HiSilicon chipset-based terminal is locked to LTE Band, it cannot access to 5G NSA network. 

If 5G HiSilicon chipset-based terminal is locked to LTE frequency or PCI, it can access to 5G NSA network.

### 10.3.2 Qualcomm Chipset-based Terminal

If 5G Qualcomm chipset-based terminal is locked to LTE frequency, it cannot access to 5G NSA network. 

If 5G Qualcomm chipset-based terminal is locked to LTE BAND or PCI, it can access to 5G NSA network.

## 10.4 How to deal with expired offline usage time?

**Problem**: when launching Pilot Pioneer, a dialog box appears and prompts the user that Pilot Pioneer offline usage time has expired.

**Solutions**: 1. Make sure that the computer is connected to the internet, and then click **Retry** in the dialog box that appears. 2. If the problem still exists even after applying method 1 above, just contact DingLi technical support to update the Pilot Pioneer version (V10.4.0.90 onwards)

## 10.5 Reasons for Low MOS Score

The reasons for Low MOS score:

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







