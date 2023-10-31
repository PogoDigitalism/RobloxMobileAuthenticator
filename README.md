
# Roblox Authenticator
### by PogoDigitalism (same username on Discord)

🎉 Easily authenticate your HTTP Requests with **RobloxAuthenticator**! 🎉


## This tool provides automation of group payouts and trades!
This is an easy-to-use wrapper written in 100% Python to automate process of Roblox' **2FA MOBILE authentication** system.
RobloxAuthenticator contains both a synchronous and asynchronous way of making these requests!

`❗ This is **NOT** a 2FA bypasser and can not be used to gain unauthorized access to Roblox accounts. I strongly discourage account theft and any other malicious practices of such matter.
This library is not made for the intend of such. RobloxAuthenticator is simply for enthusiastic people like me who want to make their life easier, make cool stuff and do good for others.`


    ⚠️ RobloxAuthenticator requires the external pyotp, requests and aiohttp libraries to function. ⚠️

### A small introduction:
Check out [this](https://github.com/PogoDigitalism/RobloxAuthenticator/blob/main/examples/sending_trades.py) for examples on how to use this lib.

In order for RobloxAuthenticator to make succesful HTTP requests, it requires a Roblox account's TOTP secret (to generate a 6-digit code) and .ROBLOSECURITY (to authorize requests).
Below is a tutorial that shows how to get this TOTP as it is a bit hidden in your account settings.

### TOTP KEY TUTORIAL:
To get the key, go to Roblox privacy settings, reset/add mobile authentication.

![image](https://github.com/PogoDigitalism/RobloxTradeAuthenticator/assets/107322523/2a448f61-3781-475e-880f-ed3a7cfc95c9)

Then, click the 'Cant't scan the code? Click here for manual entry'
This is your secret key (OTP_SECRET). Copy and paste this in your code (You can share this code across multiple devices, so adding this code to your phone as well won't affect your program.
