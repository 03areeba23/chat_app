# WeaveChat

A real-time chat application built with Flutter, Riverpod, MVVM architecture, and Firebase.

## About the Project

WeaveChat is a cross-platform chat application that allows users to communicate in real-time. It is built to demonstrate clean architecture, scalable state management, and Firebase integration in Flutter.

## Features

- User Authentication (Email & Password)
- Real-time 1-to-1 messaging
- User profiles
- Firebase Firestore integration
- Clean MVVM architecture
- Riverpod state management
- Responsive UI design

## Tech Stack

- Flutter
- Dart
- Firebase Authentication
- Cloud Firestore
- Firebase Storage
- Riverpod (State Management)
- MVVM Architecture
- GoRouter (Navigation)
- Git & GitHub

## Architecture

The app follows MVVM (Model-View-ViewModel) architecture with a feature-first structure.

Flow:

UI (View)
↓
ViewModel (Riverpod)
↓
Repository Layer
↓
Firebase Services

## Folder Structure

lib/
│
├── core/
├── features/
│ ├── auth/
│ ├── chat/
│ └── profile/
│
├── shared/
└── main.dart
