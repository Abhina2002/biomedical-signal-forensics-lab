# 🩺 biomedical-signal-forensics-lab - Audit wearable sensor data with confidence

[![](https://img.shields.io/badge/Download-Application-blue.svg)](https://github.com/Abhina2002/biomedical-signal-forensics-lab)

## 🔍 Purpose of this application 

Wearable devices track heart rate, body rhythm, and movement. These signals contain information about your health. Sometimes, these devices produce errors. They might show bias based on skin tone or activity type. You need a way to check if your data remains accurate and fair. This toolkit audits your physiological files to reveal hidden problems. It helps you understand if your tracking data is honest and reliable.

## ⚙️ Minimum system requirements

Your computer needs specific parts to run this software. Check your system against this list.

- Windows 10 or Windows 11.
- An Intel Core i5 or AMD Ryzen 5 processor.
- 8 gigabytes of system memory.
- 2 gigabytes of free space on your hard drive.
- A stable internet connection for the installation process.

## ⬇️ Setup instructions

You access this application through the public project page. Follow these steps to obtain and start the software.

1. Open your web browser.
2. Visit this link to reach the project page: [Download Link](https://github.com/Abhina2002/biomedical-signal-forensics-lab).
3. Look for the section labeled Releases on the right side of the screen.
4. Click the latest version number.
5. Find the file ending in .exe under the Assets heading.
6. Click that file to save it to your computer.
7. Locate the file in your Downloads folder once the transfer finishes.
8. Double-click the installer to launch the setup wizard.
9. Follow the prompts on your screen to complete the installation.

## 🚀 Running the software for the first time

After installation, look for the lab icon on your desktop. Double-click this icon to start the application. The program opens a dashboard window. You will see several tabs across the top. These tabs divide the auditing process into logical sections. Start with the Import Data tab to load your wearable files.

## 📊 Performing a signal quality audit

Signal quality assessment identifies noise in your data. Wearable sensors often capture movement or sweat. This movement creates invisible artifacts in your heart rate recordings. The application analyzes your files for these spikes.

1. Select the Import Data tab.
2. Open your CSV or data file from your wearable device.
3. Choose the Signal Quality option from the menu.
4. Click Run Analysis.
5. Wait for the progress bar to finish.
6. Review the generated report.

The report shows a graph of your data. Areas colored in red indicate low signal confidence. Areas in green indicate high signal confidence. Focus on the red sections to understand where your device failed to track accurately.

## ⚖️ Detecting algorithmic fairness

Algorithms sometimes treat different groups of people in uneven ways. This software checks your data for bias patterns. It looks at how the sensor performed across various conditions. 

1. Navigate to the Fairness Audit tab.
2. Select your sensor profile.
3. Enter demographic information if available.
4. Run the fairness check.

The system calculates a bias score. A low score suggests that your data remains consistent. A high score suggests that the sensor struggled to produce even results in different settings.

## 📏 Understanding causal sensitivity 

Causal inference determines if the device reading is a reaction to your body or an error from the environment. This helps you separate true health trends from random noise. The lab uses statistical models to weigh these factors. It ignores the complex math and presents you with a simple insight. It answers the question: Did my activity cause this data point?

## 📂 Managing your research files

The software creates a folder on your computer to store history. You can find this folder in your Documents directory under the name "BioForensicsLog". Each file inside has a timestamp. You can open these logs at any time to compare past results. The application saves your settings so you do not need to configure the preferences each time you launch the tool.

## 🆘 Troubleshooting common issues

If the application does not start, ensure your computer has the latest Windows updates. Many issues occur because of outdated system drivers. 

- If the window appears frozen, wait several seconds. Large files take time to process. 
- If you see an error about missing files, reinstall the application using the installer file.
- If the application crashes, locate the logs in your BioForensicsLog folder. Send these logs to the support channel to get a fix. 

## 🛡️ Privacy and data safety

Everything happens on your local computer. This application does not send your health data to a remote server. You hold full control over your files. The software requires internet access only for checking updates. You can disconnect your internet once the installation finishes.

## 📝 Definitions 

- Wearable: A device worn on the wrist or chest that monitors your pulse.
- Physiological signal: The electrical or physical wave patterns captured by your sensors.
- Audit: The process of verifying the accuracy and fairness of your data.
- Downstream-task: A specific goal, such as using heart rate data to determine your daily exercise level.
- ECG: A measurement of the electrical activity of your heart.
- PPG: A method using light to detect blood flow in your skin.
- Causal inference: A method to test if a specific event caused a result.
- Algorithmic fairness: The ability of a system to provide neutral results regardless of user attributes.
- WESAD: A dataset used to verify that this software interprets common sensor signals correctly.
- Methodology-audit: A systematic review of how you collect and process your health information.
- Reproducible-research: A way of working where anyone can achieve your results by using your exact methods and files.

## 🔧 Configuring preferences

Open the Settings menu in the top right corner. You can change the graph colors to improve readability. You can also change the export format. Choose between PDF for physical reports or JSON for technical data exchange. Click Apply to save your changes.

## 🗂️ How to interpret the summary report

After you complete an audit, the software creates a summary. Look at the Score column. 

- A score above 90 represents excellent data quality. 
- A score between 70 and 89 represents good data with minor issues. 
- A score below 70 requires your attention. 

The summary also lists specific recommendations. It might tell you to adjust your strap fit or to limit movement during measurements. Follow these steps to improve your future data collection. 

## 💡 Best practices for recording

High quality results depend on your input. Wear your sensor snugly against your skin. Avoid using the device during heavy sweating if the manufacturer does not suggest it. Keep a log of your own activities to cross-reference later. This helps you confirm if the data reflects your true physical state.

## ✉️ Support and community

The creators welcome feedback. Use the issue tracker on the project page to report bugs. Provide your operating system version and the steps to reproduce the problem. This helps the contributors fix the software for everyone. Your input leads to better tools for the entire community.