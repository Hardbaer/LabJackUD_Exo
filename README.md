# LabJackUD_Exo
This is a wrapper library using the LabJack exodriver to enable software using the LabJackUD driver to run on other systems than windows

I am heavily using the products from LabJack Corporation. I like their products and use them as often as I can in any projects.
They have a highlevel driver, they call it LabJackUD driver, that does all the management like device handling etc. for you.
Unfortunately this driver is only available for Windows-OS.
As there are not enough people interested in having this driver in other os, they told me that they will not port it as this work would need a lot of resources.
I understand that and asked them if they would have issues when creating an opensource project that wraps the UD driver calls to the available exodriver. They seem to have no concerns.
I already started a wrapper library for my personal use some years ago. The reason for this was my need to run my code in MSWindows- and also in GNU/Linux-environments. The functions I need are already implemented and they run fine. But there is still a lot work to do. As I started this project with the thought in mind to release it as open source and as I do not have enough time to do all this work on my own, I decided to do the release earlier as intended.
The project is far from handling it as a release candidate but it gives an overview what I want to accomplish.
What I want to do before releasing the project is some cleanup in the documentation of the code and the license headers. So it still needs a while before you can see the code here.
In the meantime I would appreciate any comments. 
What would be interesting for me is the question: Are there people out there that need that wrapper library?
Or an even better question: Would there be anyone willing to contribute to that project?
