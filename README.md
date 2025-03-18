# flutter_application_1

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

 //this code is generated by chatgpt and modified by sukhmanpreet Singh//

 **Overview**

This Flutter application fetches Pokémon Trading Card Game (TCG) data from the Pokémon TCG API and displays the card images and names in a ListView. When a user taps on a card, a larger version of the image appears in a dialog.

**Features**

Fetches Pokémon TCG card data using an API.

Displays card images and names in a ListView.

Enlarges the card image when tapped.

Uses http package for API requests.

**installation**

Clone this repository or copy the Dart code.

Navigate to the project directory in the terminal.

Run:flutter pub get 
flutter run

**Dependencies**

Add these dependencies in pubspec.yaml:

dependencies:
  flutter:
    sdk: flutter
  http: ^0.13.6
# 
 ** API Reference**

This app fetches data from the Pokémon TCG API:

API URL: https://api.pokemontcg.io/v2/cards

**Usage**

Launch the app.

View Pokémon cards in a list.

Tap on a card to see an enlarged image.

