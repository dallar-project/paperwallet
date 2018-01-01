# DAL Paper Wallet
Resources for the zero fuck's given DAL Paper Wallet

Within this section, you'll find a way to show your family and friends that you *do* in fact give a fuck. Print these bad boys off after you've encoded your Private and Public Keys within a QR Code and have positioned said code within the white spaces of any of these DAL wallets (if you are unsure how to orientate them, I would suggest printing a test wallet off and see how they fold). After you've printed your new shiny DAL, fold along the dotted lines, taking care to cover your Private Key from prying eyes... then take it to your desired destination and make it rain on any unsuspecting victim - demonstrating how much you give a fuck. 

To go a step further, you can always laminate these DAL notes - making sure to laminate shut the private key, so that it can only be accessed via destroying the wallet. This ensures that;

1) you and your DAL look super awesome,
2) you don't reuse the wallet once you've exposed your Private Keys, and,
3) not even god can access your funds unless he cuts open the laminate.

Enjoy using your paper wallets, and remember - to give DAL is to give a fuck

## Steps to create your DAL Paper Wallet

**Before you go thinking you're ready to print,** we need to derive the Private Key from the DAL QT-Wallet using your Public Key. Make sure to do these steps herein within an offline environment, then once you are done - restart the computer to dump the memory and remove all traces of these procedures before reconnecting to the interwebs. Before disconnecting, download this QR Code Generator which can be found [here](https://www.codetwo.com/freeware/qr-code-desktop-reader/) and install it ready for step 2

**1)** This step assumes you've already set up your wallet : open the wallet on your PC and navigate to console, if you have encrypted your wallet with a password, enter that first and hit enter. If you also have a wallet passphrase you will want to use the command "walletpassphrase" like this;

`walletpassphrase <passphrase> <timeout>`

...where timeout specifies how long to keep the decryption key in memory

example: if your passphrase is  "dallarisawesome", you would write in the console :
  
`walletpassphrase dallarisawesome 500` and hit Enter

then type : 

`dumpprivkey <your-dallar-public-address-here>` (without the <>)

Copy the Key displayed on the screen and paste it into notepad, or if you're the competent kind of computer whiz that you are, just leave it on the clipboard.

**2)** Now that we have pasted your private key into notepad, we need to open the QR Code Generator we downloaded and installed earlier. 

**3)** After it opens you want to find in the top of the UI on the toolbar, a "Generate Mode On" function. Click that, and then copy the private address out of notepad and paste it in the "QR Code Text" field. This will present to you a QR Code on the screen like some form of black magic.

**4a)** Back up the top of the UI on the toolbar, you will find a "save as" button. Click it. Do it. Save that where you won't lose it - we want to delete this file once we've finished with it (or back it up to a secure, offline location)

**b)** Repeat steps 3 & 4a for your public key

**5)** Make your way to your favourite photo editing application such as the trusty Windows Paint, and cut / paste your newly discovered QR Code into the corresponding White spaces in any of the templates provided to you, free of fuck's given, from the git repo. 

**6)** Now it's time for your to print your shiny new beast of a DAL. While in your editing software, click print, and **make sure your page format is set to landscape**, then beam it up, Scotty. 

After you're happy with the results, delete all remaining traces of your presence on this computer, such as the QR Code itself, and the wallet that you so cleverly designed... or if you prefer to save this template you've just made, **be aware** that this will **compromise the integrity of your security** since you will have your private keys exposed digitally in a few other locations other than this paper wallet. This is wholly not recommended unless you take extreme steps to wipe your tracks and store the digital asset **offline**.

**7)** Now we restart the computer and come back online. You're done!

### Bonus Level

Be the best at giving a fuck as you can be, by laminating your folded paper wallet - just fold the public key tab over the top of your private key QR Code and send the Dallar note through the machine, plastic and all. You won't be disappointed at the results. 
