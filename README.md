Schyla Solms 
Z23695226

Instaparse - Lab 1

This lab is the first part of a two-part lab where we clone some of the main functionalities of Instagram and apply some aspects of the BeReal app to help prepare for the unit project. In this lab, users will be able to sign up and log in to Instaparse, select photos from their photo album, and post them to their feed. All user authentication and data will be managed via a custom remote Parse backend server.

Goals
By the end of this lab, you will be able to:

Create and configure a custom remote Parse backend server.
Add and configure the Parse Swift SDK in your project.
Implement user authentication via Parse Swift.
Save and access data using Parse Swift.
Allow users to pick and post photos from their photo library.
Features Implemented

Authentication: Users can create accounts and log in via Parse Swift.
Photo Uploading: Users can select and upload photos from their local photo library to their feed.
Data Management: All user data and posts are securely saved and accessed via a custom Parse backend.
Installation

Clone this repository to your local machine.
bash
git clone https://github.com/your-repo/instaparse-lab1.git

Open the project in Xcode.

Run pod install to ensure all necessary dependencies (e.g., Parse SDK) are installed.

Configure your custom Parse backend server URL and app credentials in the project settings.

Build and run the project in the simulator or on a physical device.

How to Use

Sign Up: New users can create an account by providing a username and password.
Log In: Existing users can log in with their credentials.
Upload Photo: Once logged in, users can select a photo from their photo library and post it to their feed.
Project Structure

AppDelegate.swift: Handles app launch and configuration.
LoginViewController.swift: Manages user sign-in and sign-up.
FeedViewController.swift: Displays the user's feed of photos.
PhotoPicker.swift: Allows users to choose a photo from their library and upload it.
ParseManager.swift: Centralized logic for interacting with the Parse backend (user authentication, data saving, etc.).
Tools and Libraries Used

Xcode: Development environment.
Parse Swift SDK For backend interaction and data management.
UIKit: To create the app's user interface.
Configuration
To set up your Parse server:

Create an account at Back4App or another Parse hosting provider.
Set up a new Parse project.
Obtain your Parse server URL, App ID, and Client Key.
Add this information to your project configuration (Info.plist or directly in ParseManager.swift).
Resources

Parse Swift SDK Documentation
Back4App - Parse hosting platform.

![instaparse_walkthrough_1_xtra_small](https://user-images.githubusercontent.com/11927517/199710313-700aef85-ba89-427c-aa07-f89f0fdfdbbe.gif)
