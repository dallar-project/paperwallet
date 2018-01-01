# DAL Paper Wallet
Resources for the zero fuck's given DAL Paper Wallet

Within this section, you'll find a way to show your family and friends that you *do* in fact give a fuck. Print these bad boys off after you've encoded your Private and Public Keys within a QR Code and have positioned said code within the white spaces of any of these DAL wallets (if you are unsure how to orientate them, I would suggest printing a test wallet off and see how they fold). After you've printed your new shiny DAL, fold along the dotted lines, taking care to cover your Private Key from prying eyes... then take it to your desired destination and make it rain on any unsuspecting victim - demonstrating how much you give a fuck. 

To go a step further, you can always laminate these DAL notes - making sure to laminate shut the private key, so that it can only be accessed via destroying the wallet. This ensures that;

1) you and your DAL look super awesome,
2) you don't reuse the wallet once you've exposed your Private Keys, and,
3) not even god can access your funds unless he cuts open the laminate.

Enjoy using your paper wallets, and remember - to give DAL is to give a fuck

#Steps to create your DAL Paper Wallet

Before you go printing anything, we need to derive the Public Key from the DAL QT-Wallet. Make sure to do these steps herein within an offline environment, then once you are done - restart the computer to dump the memory and remove all traces of these procedures before reconnecting to the interwebs. Before disconnecting, download this QR Code Generator which can be found [here](https://www.codetwo.com/freeware/qr-code-desktop-reader/) and install it ready for step 2

1) This step assumes you've already set up your wallet : open the wallet on your PC and navigate to console, if you have encrypted your wallet with a password, enter that first and hit enter. If you also have a wallet passphrase you will want to first use the command "walletpassphrase" like this;

`walletpassphrase <passphrase> <timeout>`

...where timeout specifies how long to keep the decryption key in memory

example: if your passphrase is  "dallarisawesome", you would write in the console :
  
`walletpassphrase dallarisawesome 500` and hit Enter

then type : 

`dumpprivkey your-dallar-adress-here`

Copy the Key displayed on the screen and paste it into notepad

2) Now that we have saved your private key, we need to open the QR Code Generator we downloaded earlier.  
