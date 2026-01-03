# Free Wallpapers

This folder contains image files that are displayed as "Free Wallpapers" on the About Us page (`/pages/public/about/index.html`).

## How to Add New Wallpapers

To add a new wallpaper, follow these steps:

1.  **Place your image file** (e.g., `my-new-wallpaper.jpg`, `another-wallpaper.png`) directly into this `assets/free` folder.
    *   Supported formats include PNG, JPEG, GIF, etc.

2.  **Update `wallpapers.json`**:
    *   Open the `wallpapers.json` file, also located in this `assets/free` folder.
    *   Add the exact filename of your new wallpaper to the JSON array. Each filename should be a string enclosed in double quotes, separated by a comma.

    **Example `wallpapers.json`:**

    ```json
    [
      "free01.png",
      "my-new-wallpaper.jpg",
      "another-wallpaper.png"
    ]
    ```

    **Important:** Ensure the JSON remains valid. Every filename must be a string in double quotes, and items must be separated by commas, with the entire list enclosed in square brackets.

After saving `wallpapers.json` with the updated list, your new wallpapers will automatically appear on the About Us page.