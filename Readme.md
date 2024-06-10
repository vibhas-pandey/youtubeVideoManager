# YouTube Video Manager

YouTube Video Manager is a simple Command Line Interface (CLI) application for managing your favorite YouTube videos. You can list, add, update, and delete videos stored in a local JSON file.

## Features

- **List All Videos**: View all videos with their name and duration.
- **Add a Video**: Add a new video by entering its name and duration.
- **Update a Video**: Update the details of an existing video.
- **Delete a Video**: Remove a video from the list.
- **Exit the App**: Exit the application gracefully.

## How to Use

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/yourusername/youtube-video-manager.git
    cd youtube-video-manager
    ```

2. **Run the Application**:
    ```sh
    python youtube_manager.py
    ```

3. **Follow the On-Screen Instructions**:
    - Choose an option from the menu to list, add, update, or delete videos.
    - Enter the required information as prompted.

## Example Usage

- **Listing Videos**:
    ```plaintext
    youtube manager | choose an option:
    1. List all youtube videos:
    2. Add a youtube video:
    3. Update a youtube video:
    4. Delete a youtube video:
    5. Exit the App
    Enter your choice : 1

    **********************************************************************
    1. Video Name 1, Duration: 10:00
    2. Video Name 2, Duration: 15:30
    **********************************************************************
    ```

- **Adding a Video**:
    ```plaintext
    Enter video name: New Video
    Enter video time: 20:45
    ```

- **Updating a Video**:
    ```plaintext
    Enter the video number to update: 1
    Enter the new video name: Updated Video Name
    Enter the new video time: 12:30
    ```

- **Deleting a Video**:
    ```plaintext
    Enter video number to be deleted: 2
    ```

## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue to discuss improvements or bugs.

## License

This project is licensed under the MIT License.
