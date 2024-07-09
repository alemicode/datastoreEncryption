# Secure Data Storage with DataStore and Encryption
Master DataStore and encryption in Android development. This example shows how to encrypt user settings before persisting them using DataStore.

This Android project demonstrates how to securely store sensitive user data using DataStore and AES encryption. It provides a simple UI for saving and loading user settings (username and password), ensuring the data is encrypted before being persisted.

## Screenshots

(If applicable, include screenshots or GIFs of your app in action here)

## Tech Stack

* **Kotlin:** The primary programming language used for Android development.
* **Jetpack Compose:** Modern declarative UI toolkit for building native Android interfaces.
* **DataStore:** Jetpack library for efficient and asynchronous data storage.
* **Android Keystore:** Secure system for key generation and storage.
* **AES Encryption:** Industry-standard encryption algorithm for protecting data at rest.

## Features

* **Secure Storage:** Sensitive user data (username and password) is encrypted before being stored using AES encryption.
* **DataStore Integration:** Leverages DataStore for efficient and asynchronous data persistence.
* **Custom Serializer:** Implements a custom serializer to handle encryption and decryption of data before interacting with DataStore.
* **User-Friendly UI:** Provides a simple and intuitive interface for saving and loading user settings.
