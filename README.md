```
          _____                    _____                    _____                    _____                    _____                    _____                    _____          
         /\    \                  /\    \                  /\    \                  /\    \                  /\    \                  /\    \                  /\    \         
        /::\    \                /::\____\                /::\    \                /::\____\                /::\    \                /::\    \                /::\____\        
       /::::\    \              /:::/    /               /::::\    \              /:::/    /               /::::\    \              /::::\    \              /:::/    /        
      /::::::\    \            /:::/    /               /::::::\    \            /:::/    /               /::::::\    \            /::::::\    \            /:::/    /         
     /:::/\:::\    \          /:::/    /               /:::/\:::\    \          /:::/    /               /:::/\:::\    \          /:::/\:::\    \          /:::/    /          
    /:::/__\:::\    \        /:::/    /               /:::/__\:::\    \        /:::/____/               /:::/__\:::\    \        /:::/__\:::\    \        /:::/____/           
   /::::\   \:::\    \      /:::/    /                \:::\   \:::\    \      /::::\    \              /::::\   \:::\    \      /::::\   \:::\    \      /::::\    \           
  /::::::\   \:::\    \    /:::/    /      _____    ___\:::\   \:::\    \    /::::::\    \   _____    /::::::\   \:::\    \    /::::::\   \:::\    \    /::::::\    \   _____  
 /:::/\:::\   \:::\____\  /:::/____/      /\    \  /\   \:::\   \:::\    \  /:::/\:::\    \ /\    \  /:::/\:::\   \:::\    \  /:::/\:::\   \:::\ ___\  /:::/\:::\    \ /\    \ 
/:::/  \:::\   \:::|    ||:::|    /      /::\____\/::\   \:::\   \:::\____\/:::/  \:::\    /::\____\/:::/  \:::\   \:::\____\/:::/__\:::\   \:::|    |/:::/  \:::\    /::\____\
\::/   |::::\  /:::|____||:::|____\     /:::/    /\:::\   \:::\   \::/    /\::/    \:::\  /:::/    /\::/    \:::\  /:::/    /\:::\   \:::\  /:::|____|\::/    \:::\  /:::/    /
 \/____|:::::\/:::/    /  \:::\    \   /:::/    /  \:::\   \:::\   \/____/  \/____/ \:::\/:::/    /  \/____/ \:::\/:::/    /  \:::\   \:::\/:::/    /  \/____/ \:::\/:::/    / 
       |:::::::::/    /    \:::\    \ /:::/    /    \:::\   \:::\    \               \::::::/    /            \::::::/    /    \:::\   \::::::/    /            \::::::/    /  
       |::|\::::/    /      \:::\    /:::/    /      \:::\   \:::\____\               \::::/    /              \::::/    /      \:::\   \::::/    /              \::::/    /   
       |::| \::/____/        \:::\__/:::/    /        \:::\  /:::/    /               /:::/    /               /:::/    /        \:::\  /:::/    /               /:::/    /    
       |::|  ~|               \::::::::/    /          \:::\/:::/    /               /:::/    /               /:::/    /          \:::\/:::/    /               /:::/    /     
       |::|   |                \::::::/    /            \::::::/    /               /:::/    /               /:::/    /            \::::::/    /               /:::/    /      
       \::|   |                 \::::/    /              \::::/    /               /:::/    /               /:::/    /              \::::/    /               /:::/    /       
        \:|   |                  \::/____/                \::/    /                \::/    /                \::/    /                \::/____/                \::/    /        
         \|___|                   ~~                       \/____/                  \/____/                  \/____/                  ~~                       \/____/         
```
# Lunar Lander AI
## LunarLanderAI.ipynb
I used Google Colab's free GPU to train my AI, so the `LunarLanderAI.ipynb` contains the code to train and save the model on Google Colab.

Moreover, there is a workaround that I have picked up from here to visualize the gameplay as the model trains, because Colab is a Notebook only environment, which makes it difficult for Open AI gym to bind to a display.
So, we use the `pyvirtualdisplay` library and a wrapper around our environment.

## model.zip
Contains the model weights that I have trained on Google Colab.

## videos.zip
Contain the videos of gameplay as the bot triains

## requirements.txt
is the usual requirements.txt that any python project should have, though it isnt complete, it only contains what you need to run the LunarLander-v2 Environment in Open Ai Gym