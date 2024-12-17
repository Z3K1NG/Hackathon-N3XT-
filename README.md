# N3XT Chrome Extension  

## Overview  
**N3XT** is a Chrome browser extension built using **Manifest V3** that extracts all links from a webpage and evaluates their safety.  
Currently, it leverages the **Google Safe Browsing API** to verify link safety and provides real-time alerts on the results.  
In the future, we aim to integrate a **machine learning model** to perform the safety checks locally.  

## Features  
- **Extracts** all links from the active webpage.  
- **Checks** the safety of links using the **Google Safe Browsing API** .  
- **Displays alerts** to inform users about the safety of the links.  
- **Future Enhancement**: Integration with a **custom machine learning model** for local safety analysis to replace the existing google safe browsing api.  

## Repository Structure  
- `N3XT.zip`: Contains the source code for the Chrome extension.  
- `machineLearning/`: The base version of the machine learning model, which will enhanced and integrated soon.

## How to Use  
1. Download or clone the repository.  
2. Extract the `N3XT.zip` file.  
3. Open **Google Chrome** and navigate to `chrome://extensions`.  
4. Turn on **Developer Mode** (toggle in the top-right corner).  
5. Click **Load Unpacked** and select the **N3XT** folder.  
6. The extension will now be installed and ready to use.  

## Future Plans  
We are working on replacing the reliance on **Google Safe Browsing API** with our own **machine learning model** for link safety analysis.   
