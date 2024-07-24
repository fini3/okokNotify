Sure, here is a nicely formatted README for the provided notification image:

---

# okokNotify

## Screenshot

![okokNotify Screenshot](https://github.com/user-attachments/assets/36db1ae6-6dc6-49b3-b857-6ef7fb0be05b)

## Features

- Clean and user-friendly notification interface
- Widely used across popular servers such as RichRP and OnlyRP and more
- Customizable and easy to integrate into your own server

## Installation

1. **Download the Resource:**
   Download the latest version of okokNotify from [GitHub](https://github.com/your-repo/okokNotify).

2. **Add to Your Server:**
   Place the `okokNotify` folder into your server's `resources` directory.

3. **Update server.cfg:**
   Add the following line to your `server.cfg` file to ensure the resource starts when your server is launched:
   ```plaintext
   ensure okokNotify
   ```

4. **Customize:**
   Open the `config.lua` file within the `okokNotify` folder to customize the notification settings to your liking.

## Usage

To send a notification, use the following example command in your scripts:
```lua
TriggerEvent('okokNotify:Alert', 'Title', 'Message', timeout, type)
```
- `Title`: The title of the notification.
- `Message`: The message content.
- `timeout`: Duration for how long the notification will be displayed.
- `type`: Type of the notification (e.g., 'success', 'info', 'error').

## Example

Here’s an example usage that displays a success notification:
```lua
TriggerEvent('okokNotify:Alert', 'Notification Title', 'This is a success message!', 5000, 'success')
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
