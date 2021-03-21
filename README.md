# CiviPort-Alpha
Alpha test of CiviPort V1 on the Kovan and Sokol Testnets

## Hello Admin how do I use this?

The very fist thing you need to do is download the CiviPort Client from [here](https://www.github.com/blahblah). Make sure you pick the right download for your operating system.

The donwload is a zip file which will need to be extracted:

### Windows

After downloading navigate to the directory the zip file was downloaded to and right click the flie.  Choose `Extract All`.

![Extract1](https://github.com/Civitas-Fundamenta/CiviPort-Alpha/blob/main/extract1.png)

A window will pop up and ask you to choose the path of the extraction.  You can make this whatever you want.

![Extract2](https://github.com/Civitas-Fundamenta/CiviPort-Alpha/blob/main/extract2.png)

The easiest way to access the clinet is as follows:

- Navigate to the extracted files in windowd explorer.
- in the URL bar type `CMD` and press enter

![image](https://user-images.githubusercontent.com/41549105/111911676-293d2800-8a2c-11eb-9471-d7f885b4f4c0.png)

This will open the Windows Command Prompt which looks like this:

![image](https://user-images.githubusercontent.com/41549105/111911826-a8326080-8a2c-11eb-82d0-bacdf112f773.png)

To start the client and create a new wallet use the following:

`Client.exe --testnet --wallet-file WALLET --create-wallet`
![image](https://user-images.githubusercontent.com/41549105/111911980-445c6780-8a2d-11eb-9993-b97c14d2d422.png)

This will create a wallet file called `WALLET` in the same directory as the client.  

**NOTE** --create-wallet only needs to be passed when creating a new wallet.  When opening an existing wallet --create-wallet is not required.

![image](https://user-images.githubusercontent.com/41549105/111912044-808fc800-8a2d-11eb-96a8-7c4f2ceecd9f.png)

And will also start the CiviPort Client and connect to CiviSwarm and the bridge contracts. 

![image](https://user-images.githubusercontent.com/41549105/111912034-7077e880-8a2d-11eb-9512-acc8d7e03098.png)



