description: Read how to install and configure Bastion Bot, on Linux. One step closer to making your Discord Server AWESOME!

# Bastion Installation on GNU/Linux

*If you are going to install Bastion in any other operating system besides Linux,
you can skip this step and visit to the appropriate page for the specific guides
on [Windows](install-win) or [macOS](install-macos). Or if you are an advanced
user and want to know what's going on with the installer or want to go through
the installation step by step, manually (trust me I understand), we have a
[manual installation guide](install-manual), made just for you!*

!!! tip "Want to run Bastion 24x7?"
    If you want Bastion to serve 24/7 without having to hosting it on your
    PC and want to keep it cheap, reliable and convenient as possible, you can
    install Bastion, using the following guide, on a [DigitalOcean](https://m.do.co/c/0ee6cb9c7ee0)
    Linux VPS using [this link](https://m.do.co/c/0ee6cb9c7ee0) (using this link
    will be supporting The Bastion Bot project and will give you **$10** for
    free to start with DigitalOcean).

## Download the installer

Run the following command to download the Bastion Bot installer that'll help
you install Bastion smooth and easy:
```bash
wget https://raw.githubusercontent.com/TheBastionBot/Bastion-Scripts/master/BastionInstaller.sh && chmod +x BastionInstaller.sh
```

## Proceed with the installation

Now that you've downloaded the installer, it will automatically download and
install everything you'll need to run Bastion.

To start the installation, run the following command:
```bash
./BastionInstaller.sh
```

Wait for a few moments for the installer to finish installing.

After the installation is done, it will prompt you to configure Bastion and will
ask you to configure Bastion, type/paste the answers as asked (here you'll be
needing your API keys) and if you want to skip any step, just leave it blank and
press <kbd>&crarr; Enter</kbd>.

After you're done configuring Bastion, it'll let you know that the installation
was successfully completed and Bastion is ready to boot up. :smile:

Now, you should have a new folder named `Bastion` in your `$HOME` (`~`)
directory.

## Get Bastion running

You get a `bastion.sh` script file that makes it easy to run Bastion without
any hassle, among other things. To start Bastion, run the following command:
```bash
cd ~/Bastion # Changes the current directory to the `Bastion`, if you aren't already there.
./bastion.sh --start # Starts Bastion
```

!!! tip "Pro Tip"
    The `bastion.sh` script can do a whole lot of other things besides just
    helping you with running & updating Bastion. Want to find out what else
    can it do? Just run the following command to know more: `./bastion.sh`
