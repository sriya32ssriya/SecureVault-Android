# SecureVault – Offline Password Vault

SecureVault is a privacy-focused Android application designed to securely store and manage user credentials in an offline environment. The app protects sensitive information using strong cryptographic techniques and keeps all data stored locally on the user's device without relying on cloud services.

## Features

- Offline password vault for storing credentials
- Master password authentication for accessing the vault
- AES-GCM encryption for secure credential storage
- SHA-256 hashing for password verification
- Secure local storage without internet dependency
- Modern UI built using Jetpack Compose
- MVVM architecture for better code organization and scalability

## Security Implementation

SecureVault implements multiple layers of security to protect stored credentials:

- AES-GCM encryption is used to encrypt sensitive data before storing it locally
- SHA-256 hashing is used for secure password verification
- All data remains stored locally on the device
- Authentication ensures that only authorized users can access stored credentials

## Technologies Used

- Kotlin
- Jetpack Compose
- MVVM Architecture
- AES-GCM Encryption
- SHA-256 Hashing
- Android Studio

## Project Structure

The application follows the MVVM (Model-View-ViewModel) architecture:

- Model – Handles data and encryption logic
- View – Jetpack Compose UI components
- ViewModel – Manages UI state and application logic

## Purpose of the Project

This project demonstrates secure Android application development practices with a focus on cryptographic security, privacy-preserving credential storage, and modern Android architecture.

## Future Improvements

- Biometric authentication support
- Secure backup and restore functionality
- Password strength analysis
- Improved credential management
