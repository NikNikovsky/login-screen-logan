# Backgrounds

This directory contains background images used in the login screen.

## Adding New Backgrounds

To add a new background image:

1. **Add the image file** to this directory (e.g., `background1.jpg`, `background2.png`)

2. **Update `backgrounds.json`** in the root directory with the new entry:

```json
{
  "id": "unique-id",
  "type": "image",
  "url": "backgrounds/your-image.jpg",
  "author": "Photographer Name",
  "authorUrl": "https://photographer-website.com",
  "description": "Brief description of the background"
}
```

### Background Types

The system supports two types of backgrounds:

- **`gradient`**: CSS gradients
  ```json
  {
    "id": "example-gradient",
    "type": "gradient",
    "value": "linear-gradient(135deg, #667eea 0%, #764ba2 100%)",
    "author": "Designer Name",
    "authorUrl": "https://designer-website.com",
    "description": "Description"
  }
  ```

- **`image`**: Image files
  ```json
  {
    "id": "example-image",
    "type": "image",
    "url": "backgrounds/example.jpg",
    "author": "Photographer Name",
    "authorUrl": "https://photographer-website.com",
    "description": "Description"
  }
  ```

## Attribution

All backgrounds must include proper attribution to their creators. The login screen automatically displays author credits in the bottom-right corner based on the selected background's metadata from `backgrounds.json`.
