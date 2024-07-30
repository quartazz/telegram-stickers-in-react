# telegram-stickers-in-react
Guide on how to add stickers from telegram to your project


**1.**  You receive a sticker in **.tgs** format

**2.**  Open **.tgs** using an archiver and get the only file from there (the sticker itself)

**3.**  The sticker file has no extension. Now you need to change the file format to .json

![image](https://github.com/user-attachments/assets/04e6fa47-9f5e-4afa-9809-1ea18f7586f6)

![image](https://github.com/user-attachments/assets/980f9ef7-8682-4e6f-a7fa-844b9bfcde5c)

Ready!

## **Example in React:**

  Set lottie to display sticker:
  ```

  npm i lottie-react

  ```

  Import lottie and the sticker:
  ```jsx

  import Lottie from "lottie-react"

  import keyboardSticker from "/src/assets/stickers/keyboard.json"

  ```

  Tag lottie
  ```jsx

  <div style={{position: "relative", width: "32px", top: "2px"}}>
      <Lottie animationData={keyboardSticker} loop={true} />
  </div>

  ```
