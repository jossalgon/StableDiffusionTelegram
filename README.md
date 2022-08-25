# StableDiffusionTelegram
StableDiffusionTelegram is a telegram bot that allows to generate images using the [Stable Diffusion](https://github.com/CompVis/stable-diffusion) AI from a telegram bot, in a much more comfortable and simple way. This bot can generate images from a text input or from an image with caption. In addition, given any response from the bot, a new try or a variation of the attempt can be generated.


## Installing
1. Install PyTorch (https://pytorch.org/get-started/).

2. Install requirements:
  ```
  pip install -r requirements.txt
  ```
  
3. Register in Hugging Face Hub and create a token (https://huggingface.co/docs/hub/security-tokens).

4. Use the token to login in huggingface-cli:
  ```
  $ huggingface-cli login
  ```
  
5. Talk to BotFather and create a bot (https://t.me/BotFather).

6. Create a .env file with the telegram token and the safe content option (if false, explicit content will be displayed, otherwise set to true):
  ```
  TG_TOKEN="YOUR_TOKEN_IS_HERE"
  SAFETY_CHECKER="false"
  ```
  
7. Run the bot
  ```
  python bot.py
  ```


## Examples
Generating image from text |  Generating a variation   |  Generating a new image from an user photo
:-------------------------:|:-------------------------:|:-------------------------:
![](assets/example1.jpg)   |  ![](assets/example2.jpg) |  ![](assets/example3.jpg)


## Credits

* [Stable Diffusion](https://github.com/CompVis/stable-diffusion)
* [Diffusers](https://github.com/huggingface/diffusers)
* [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot)
