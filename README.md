# TrackMe
TrackMe is a smart personal finance tracker that automates expense logging through SMS detection while providing clear visual insights into your monthly budgets and spending habits.

<p align="center">
  <img width="268" alt="image" src="https://github.com/user-attachments/assets/b480e2b5-0849-42e7-aff9-f8b0e8872820" />
  <img width="255" alt="image" src="https://github.com/user-attachments/assets/d1ad6566-5146-48bf-ad77-f47ea126c070" />
  <img width="262" alt="image" src="https://github.com/user-attachments/assets/1cbe4634-6d2d-4a36-b291-83f11d5741ef" />
</p>

## Motivation

As a university student living on a budget, I frequently found myself reaching the end of the month wondering where my money had vanished. Balancing daily academic life with personal expenses made it incredibly easy to slip into careless spending habits, directly threatening my financial stability. I realized that to keep myself within bounds and stop overspending unnecessarily, I needed a frictionless way to monitor every transaction. But logging every transaction is quite boring in this age :3 so I decided to lean towards the lazy approach - building an app! Introducing **TrackMe**. By leveraging SMS detection to instantly log digital transactions alongside a quick manual entry system, this app serves as my personal financial guardrail ensuring I stay disciplined, visualizes my spending habits, and helps me build a secure financial foundation for the future. 

Could I have done that myself instead of needing an app? Yes, definitely. Would I do that though? Statistically, probably not T__T

## How It Works

TrackMe keeps your finance tracking seamless by combining background automation with powerful visual tools. Here is how you use it:

### 1. Automatic Expense Logging (Zero Effort)
* **Receive an SMS:** Whenever you make a transaction via apps like bKash, a bank, or utility SMS notification, TrackMe parses the message in the background.
* **Auto-Log:** The app instantly extracts the **amount**, **payment method**, and **vendor** (like *foodpanda* as seen in the logbook) without you ever needing to open the app.

### 2. Manual Entry 
* Tap the floating **`+` button** on the home dashboard.
* Type in the amount, add a quick reason (e.g., *Groceries*), pick a category, and select your payment method (Cash, Card, bKash).
* Hit **Save Transaction** to immediately update your balance.

### 3. Track Budgets & Analytics
* **Set a Limit:** Tap the edit icon under **Monthly Budget** to set your spending cap for the month.
* **Visual Breakdown:** Monitor the **Category Breakdown** pie chart on your dashboard to see exactly where your money goes (e.g., *Food*, *Shopping*, *Utilities*).
* **Yearly Insights:** Switch to the yearly overview to track your spending habits across months with simple, intuitive bar graphs.


## Installation & Setup

To get TrackMe up and running on your Android device right away, follow these simple steps:

1. **Download the Package:** Locate the `trackme.zip` file in the main repository file list above and download it to your machine or phone.
2. **Extract the Files:** Unzip the downloaded folder. 
3. **Locate the APK:** Navigate inside the extracted files to the `build-outputs` folder.
4. **Install the App:** Download and open the `app-debug.apk` file found inside that folder. 
   * *Note: Since this is a debug build directly from the development environment, your phone might ask you to allow installations from "Unknown Sources" or your file manager. Toggle that on to proceed with the installation!*
