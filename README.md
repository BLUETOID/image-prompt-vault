# image-prompt-vault

A simple JavaScript utility for storing and retrieving image prompts using browser localStorage. Perfect for web-based projects that need to save and reuse user-generated prompts for image generation or creative workflows.

## Features

- Save image prompts to browser localStorage
- Retrieve, update, and manage prompts easily
- Lightweight and easy to integrate with any web app

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/BLUETOID/image-prompt-vault.git
   ```

2. **Include in your project**
   - Add `utils.js` to your HTML:
     ```html
     <script src="utils.js"></script>
     ```

3. **Usage Example**
   ```js
   // Save a prompt
   localStorage.setItem("imagePrompt", "A futuristic city skyline at sunset");

   // Retrieve a prompt
   const imagePrompt = localStorage.getItem("imagePrompt");
   ```

## Requirements

- Runs in any modern web browser (localStorage API support)

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

This project is open source. Add your preferred license here.

---

Created by [BLUETOID](https://github.com/BLUETOID)
