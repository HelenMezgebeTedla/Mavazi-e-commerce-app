# Mavazi

A Flutter-based E-commerce application featuring a clean state-management architecture powered by Provider.

## Project Structure

The project follows an MVVM directory layout to decouple UI presentation from business logic. Inside the lib folder, the structure includes:

lib/
├── assets/images/    # Application asset files and graphics
├── model/           # Core data objects (Product, Cart, User)
├── screens/         # UI Elements and Views (HomeScreen, CartScreen, ProductCard)
├── service/         # Remote APIs and network connections (test_api.dart)
├── viewmodel/       # State controllers managing business logic (AuthViewModel)
└── main.dart        # Entry point of the application

## Getting Started

Follow these instructions to set up, clean, and run the development environment on your local machine.

### Prerequisites

- Flutter SDK: Ensure you have the latest stable version installed by running flutter version.
- Target Devices: An active Android Emulator, iOS Simulator, or a connected physical mobile device with debugging enabled.

### Run Environment Cycle

If you encounter stale build artifacts or package resolution problems, reset your build environment by running the following sequential commands in your terminal:

1. Clean build cache:
   flutter clean

2. Fetch dependencies:
   flutter pub get

3. Launch the application:
   flutter run

## Dependencies

This project relies on the following core external packages:

- Provider: Used for reactive state management and dependency injection across views.

## Testing

To ensure code stability, run automated widget and unit tests defined within the codebase by executing:
flutter test
