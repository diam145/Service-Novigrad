# Service Novigrad

An Android project to emulate a provincial services platform, similar to Service Ontario. This application manages service requests, user accounts, and branch operations using Firebase.

##  Description

Service Novigrad is an Android application designed to simulate the operations of a government service provider. It allows for different user roles (Administrator, Employee, and Customer) to manage and access various services. This project uses Firebase for real-time data management.

## Features

The application is structured around three main user roles:

* **Administrator:**
    * Create, edit, and delete services.
    * Manage user accounts (Employees and Customers).
    * Assign roles and permissions.

* **Employee:**
    * Manage branch service requests.
    * Approve or reject service applications.
    * View and modify customer profiles within their branch.
    * Set branch working hours and services.

* **Customer:**
    * Create an account.
    * Search for branches and view their information (address, hours, services offered).
    * Submit service requests (e.g., license application, document request).
    * Track the status of their requests.

## Tech Stack

* **Platform:** Android
* **Language:** Java
* **Database:** Google Firebase Realtime Database
* **UI:** Android XML Layouts


## Getting Started

To get a local copy up and running, follow these simple steps.

1.  **Clone the repo**
    ```sh
    git clone [https://github.com/diam145/Service-Novigrad.git](https://github.com/diam145/Service-Novigrad.git)
    ```
2.  **Open the project**
    * Open the project in **Android Studio**.
    * It should detect the Gradle configuration and build the project.
3.  **Connect Firebase**
    * You will need to connect this project to your own Firebase instance.
    * Follow the Android Firebase setup guide to add your `google-services.json` file to the `app` directory.
4.  **Run the application**
    * Build and run the project on an Android emulator or a physical device.

## Usage

Once the application is running:
1.  You will be prompted to log in or create an account.
2.  Based on your role (Admin, Employee, or Customer), you will be presented with a menu of options.
3.  Follow the on-screen prompts to manage services, handle requests, or apply for a new service.

## License
