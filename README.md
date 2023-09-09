# tunley
# Tunley App Readme

Display of App 
    <a href="https://www.loom.com/share/bc5e8cc27ca145cda8ca46b7816a7f50">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/bc5e8cc27ca145cda8ca46b7816a7f50-with-play.gif">
    </a>

## Overview

The Tunley app is a mobile application developed using Swift that allows users to explore and view a list of music tracks from the iTunes API. Users can access detailed information about a specific track by tapping on it, which presents a dedicated detail view showing additional details about the track, such as the artist, album, and more.

## Project Description

In this lab project, you will create a mobile app that demonstrates the following features:

### Required Features

1. **View a List of Tracks**:
   - Display a list of music tracks in a table view.
   - The table view should use custom table view cells to present the track's title, artist, and album cover.
   - It's important to note that for this part of the project, we will use hardcoded Track data models. The focus here is on navigation and table views, and networking will be implemented in the next unit.

2. **Responsive UI**:
   - Ensure that the app's user interface is responsive to various screen sizes and orientations. This means that users should be able to use the app comfortably on both portrait and landscape orientations and on different iOS devices.

3. **Album Cover Loading**:
   - To load track album covers efficiently, we will integrate the Nuke library, a 3rd party image loading library, via Swift Package Manager (SPM). This library will help streamline the loading and caching of images, enhancing the app's performance.

4. **Track Detail View**:
   - Allow users to access more information about a specific track by tapping on it in the list view.
   - When a track is tapped, it should navigate to a detail screen where users can view additional details about the selected track. These details may include the artist's name, album name, and any other relevant information.

## Getting Started

To get started with the Tunley app project, follow these steps:

1. Clone this repository to your local development environment.

2. Open the project in Xcode or your preferred Swift development environment.

3. Familiarize yourself with the existing code and project structure.

4. Implement the required features mentioned above, making use of custom table view cells and integrating the Nuke library for efficient image loading.

5. Test the app on various device simulators and orientations to ensure responsive UI behavior.

6. Create a detailed user interface for the track detail view, and make sure it presents the necessary information when a track is selected.

7. Continuously test and debug your code to ensure a smooth user experience.

## Dependencies

The Tunley app relies on the following dependencies:

- Nuke: A third-party image loading library for efficiently loading and caching images.

You can integrate these dependencies into your project using Swift Package Manager (SPM).


## Conclusion

The Tunley app is a mobile application project that demonstrates essential iOS development concepts such as table views, responsive UI design, and third-party library integration. By building and expanding upon this project, you can further develop your iOS development skills and create engaging mobile apps. 
