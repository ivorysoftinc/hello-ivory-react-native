# React Native Test Project

Basic react native project based on typescript template

## Running

Clone the repository and run the following commands

### iOS

`yarn ios`

### Android

`yarn android`

## Project Structure

All sources are contained in the `📁 src`

`📁 src`
┣ `📁 assets` contains images, icons, fonts, and other assets
┣ `📂 components` contains all reusable components
┃ ┣ `📂 Button` example of a component
┃ ┃ ┗ `📜 index.tsx` contains the `Button` component implementation
┃ ┗ `📜 index.tsx` contains exports all of the components
┣ `📂 navigation` contains navigation stacks and related items
┃ ┗ `📜 index.tsx` root navigation stack
┣ `📂 screens` contains screen components
┃ ┣ `📂 Initial` example of a screen
┃ ┃ ┗ `📜 index.tsx` contains the `Initial` screen implementation
┃ ┗ `📜 index.tsx` contains exports all of the screens
┗ `📂 utils` contains utility functions
