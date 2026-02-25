#🎲 Dice Roller App

A simple and interactive Android application built using Kotlin and
Jetpack Compose.\
The app allows users to roll a virtual dice by clicking a button, and
the dice image updates dynamically based on a randomly generated number.

------------------------------------------------------------------------

## Overview

The Dice Roller App demonstrates the fundamentals of Jetpack Compose,
including composable functions, state management, layouts, and resource
handling. It is designed as a beginner-friendly project to understand
modern Android UI development.

------------------------------------------------------------------------

## Features

-   Roll a dice with a button click\
-   Displays dice images from 1 to 6\
-   Uses state to trigger recomposition\
-   Implements proper resource management\
-   Accessible UI with content descriptions

------------------------------------------------------------------------

## Tech Stack

-   Language: Kotlin\
-   UI Toolkit: Jetpack Compose\
-   IDE: Android Studio\
-   Architecture: Single Activity (Compose-based)

------------------------------------------------------------------------

## How It Works

1.  The app displays a dice image and a "Roll" button.
2.  When the button is pressed:
    -   A random number between 1 and 6 is generated.
    -   The corresponding dice image is selected.
    -   The UI recomposes automatically using Compose state.

------------------------------------------------------------------------

## Key Concepts Used

-   @Composable functions\
-   remember state management\
-   Column layout\
-   Button and Image composables\
-   Modifier for UI styling and alignment\
-   Drawable and string resources

------------------------------------------------------------------------

## Project Structure

    DiceRollerApp/
    │
    ├── MainActivity.kt
    ├── DiceRollerApp.kt
    └── res/
        ├── drawable/ (dice images)
        └── values/
            └── strings.xml

------------------------------------------------------------------------

## Learning Outcomes

-   Understanding Jetpack Compose basics\
-   Managing UI state in Compose\
-   Updating UI dynamically\
-   Using Android resources properly\
-   Debugging in Android Studio

------------------------------------------------------------------------

## Future Improvements

-   Add dice roll animation\
-   Add sound effects\
-   Track roll count\
-   Improve UI styling\
-   Add landscape support

------------------------------------------------------------------------


