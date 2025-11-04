# New Life Baby Home Mobile Application


The **New Life Baby Home (NLBH)** mobile application helps connect the community with the organization’s mission to rescue and care for abandoned and vulnerable infants. The app simplifies donations, volunteering, event awareness, and communication — while empowering administrators to manage these areas efficiently through a secure admin interface.


---


## 1. Requirements


You will need the following to run or contribute to this application:


- Android Studio 2020.3 or later

- Android SDK 29 or later

- A device or emulator running Android 7.0 (Nougat) or above

- Internet connection

- Firebase project with Authentication & Firestore enabled


---


## 2. Installation / Setup


To set up and run the application:


1. Clone or download the project.

2. Open the project in **Android Studio**.

3. Insert your `google-services.json` file into the `/app` directory.

4. Sync the project to download dependencies.

5. Build and run the app on a real device or emulator.


For general users:

The app will be available on the **Google Play Store** (currently in closed testing).


---


## 3. User Features


After the splash screen, the user is taken to the **Dashboard**, which includes:


| Feature | Description |

|--------|-------------|

| **Impact Story** | Shows NLBH’s mission and allows users to open the Executive Summary PDF. |

| **Search Bar** | Search for any screen (Donate, Volunteer, Events, etc.) and navigate instantly. |

| **Donate** | Choose between monetary donations or item drop-offs. |

| **Volunteer** | Submit a volunteer application directly in-app. |

| **Events** | View upcoming events via an interactive calendar or event feed. |

| **FAQs** | Browse frequently asked questions about adoption, donations, etc. |

| **Testimonials** | Read real stories from families who have adopted through NLBH. |

| **About Us** | Learn about the Baby Home’s background and values. |


### 3.1 Donation Options

Users can donate through:

- **Zapper QR Code**

- **EFT Banking Details** (with copy-to-clipboard)

- **BabyChino Initiative QR Code**


The donation page includes a **Baby Bottle Progress Indicator** showing how much has been raised toward the monthly goal.


### 3.2 Drop-Off Zones

The Drop-Off Zone page provides:

- A map view and **Get Directions** link to open Google Maps

- **Call Us** one-tap dialing

- A **Wishlist** of urgently needed items (live-updated by admin)


### 3.3 Volunteer Application

Users fill in:

- Name

- Email

- Availability

- Two short volunteer-related questionnaire


Submissions are stored in Firestore for admin review.


### 3.4 Events

- Users can tap dates on the calendar to view events occurring that day.

- A scrollable list displays all **Upcoming Events**.

- Events include detailed information pages.


### 3.5 Testimonials & FAQ

- Testimonials page displays real, heartwarming family stories.

- FAQ page addresses the most commonly asked questions.


---


## 4. Admin Features


Admins log in securely through an **Admin Access** button.


| Admin Section | Actions Available |

|--------------|------------------|

| **Manage Donations** | Update monthly goal & total raised (updates Baby Bottle instantly). Add wishlist items & assign priority (High / Medium / Low). |

| **Manage Volunteers** | View volunteer applications, approve or reject them, and filter by status. Copy approved volunteer emails for follow-up. |

| **Manage Events** | Add new events with name, description, date, start time, and end time. Edit or delete existing events. |

| **Manage Testimonials** | Add new testimonials or edit/delete current ones. |


---


## 5. Non-Functional Requirements


- Fast and stable performance with smooth screen transitions

- Secure authentication and data integrity using Firebase

- Clean and intuitive UI designed for accessibility

- Admin updates instantly reflect on user-facing screens

- Compatible across various Android screen sizes


---


## 6. Feature Summary


- Splash Screen & App Branding

- Dashboard Navigation

- Donation Channels + Progress Indicator

- Volunteer Application Workflow

- Event Calendar + Upcoming Events List

- FAQ and Testimonials Viewer

- Admin Management Panels for Donations, Volunteers, Events, and Testimonials


---


## 7. Credits


Developed for **New Life Baby Home**

Developer: Axonix

Email: axonixtechnologies@gmail.com


---


## 8. Google Play Store


The app is currently in **closed testing** and will be publicly released soon.

Once released, users will receive:

- Automatic updates

- Store descriptions and app screenshots

- Easy installation on Android devices


---


## 9. GitHub Repository

```
https://github.com/st10039022/Frontend.git
```

---


## 10. AI Assistance Disclosure


ChatGPT (**GPT-5**) was used to:

- Assist in text clarity, formatting, and layout consistency

- Debug XML styling/layout issues

- Coding Assistance
