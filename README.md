EDI is short for Executable Disc Image, and is meant to be the executable version of an ISO. It is intended to be used for packaging apps and games. I know it's a little small, but that's the point, its meant to add functionality to the OS without having to take up much space. This started because I didn't like how much space AppImage libraries were taking on my potato laptop (2011 business Inspiron 14 laptop), so I decided to painstakingly learn C and now I have no clue what to fix anymore, which is why I decided to open a GitHub page to see if anyone could give feedback, and also to share it with everyone. RAM mode was implemented so that it loads everything into RAM prior to launching, which is only viable for small executables, but makes osu! run at almost 3x the speed (I went from 21fps to 54fps).

<h2>Commands</h2>

<h3>Installing</h3>

`sudo install.sh` (in the directory of the install.sh file)

<h3>Opening the compiler</h3>

`edi_compiler`

<h3>Using the runner</h3>

`edi_runner path/to/edi/file [flags]`

<h2>Future Features</h2>
<li>Installing EDI files</li>
<li>Compression</li>
<li>Bundling runners</li>
<li>Writing to discs</li>
<br>
<hr>

> [!IMPORTANT]
> 
> You may not advertise this as your own
> 
> This may be used or packaged in apps with given credit to contributors
> 
> You are free to contribute to this is you believe you can help further the project.
>
> THE WINDOWS INSTALL DOESN'T WORK. I ONLY REALIZED THIS WHEN I WAS GOING TO TEST AND SAW A FOLDER MISMATCH. I will make a separate download for Windows devices 10+ when it has a solid base.


<hr>
<br>
<h2>Roadmap</h2>
<li>v1.0.4: November 5th 2026</li>
<li>v1.0.5: December 1st 2026</li>
To be Continued...<br>

<h2>Custom Builds</h2>
To build your own version, all you have to do is download one of the versions you'd like to build, edit it, and then compile the C, and zip it up. You may need to change install.sh if you intend on adding new files or adding compatibility for other operating systems. If you do build your own version, please give credit, as this took a while to make.

<br>
<br>

> [!NOTE]
>
> I am juggling this and another project at the same time, so I hope that you'll be able to make a lot of <strong>sound</strong> with the next project.

![Static Badge](https://img.shields.io/badge/Development-Active-brightgreen) ![Static Badge](https://img.shields.io/badge/Status-Slowed_Development-orange) ![Static Badge](https://img.shields.io/badge/Version-V1.0.3-blue) ![Static Badge](https://img.shields.io/badge/Language-C-purple) ![Static Badge](https://img.shields.io/badge/Stars-1-yellow)
