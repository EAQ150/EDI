EDI is short for Executable Disc Image, and is meant to be the executable version of an ISO. It is intended to be used for packaging apps and games. I know it's a little small, but that's the point, its meant to add functionality to the OS without having to take up much space. This started because I didn't like how much space AppImage libraries were taking on my potato laptop (2011 business Inspiron 14 laptop), so I decided to painstakingly learn C and now I have no clue what to fix anymore, which is why I decided to open a GitHub page to see if anyone could give feedback, and also to share it with everyone. RAM mode was implemented so that it loads everything into RAM prior to launching, which is only viable for small executables, but makes osu! run at almost 3x the speed (I went from 21fps to 54fps).

Below are the commands that the package adds:

Installing

`sudo install.sh` (in the directory of the install.sh file)

Opening the compiler

`edi_compiler`

Using the runner

`edi_runner path/to/edi/file [flags]`

> [!IMPORTANT]
> 
> You may not advertise this as your own
> 
> This may be used or packaged in apps with given credit to contributors
> 
> You are free to contribute to this is you believe you can help further the project.
>
> THE WINDOWN INSTALL DOESN'T WORK. I ONLY REALIZED THIS WHEN I WAS GOING TO TEST AND SAW A FOLDER MISMATCH. I will make a separate download for Windows devices 10+ when it has a solid base.

To build your own version, all you have to do is download one of the versions you'd like to build, edit it, and then compile the C, and zip it up. You may need to change install.sh if you intend on adding new files or adding compatibility for other operating systems.

[![Star History Chart](https://api.star-history.com/chart?repos=eaq150/edi&type=date&legend=top-left)](https://www.star-history.com/?repos=eaq150%2Fedi&type=date&legend=top-left)
I found this randomly today :)
