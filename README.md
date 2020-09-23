<div align="center">

## All About Beep API \[Article\]


</div>

### Description

U may assume that Beep API can only be used 4 beeping. But, wait there's more what you can do with this API. You can also drive the mosquitos away using this technique! Check it out now! AND NEVER FORGET TO RATE!!
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[MadWizardBD](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/madwizardbd.md)
**Level**          |Beginner
**User Rating**    |3.8 (50 globes from 13 users)
**Compatibility**  |VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Windows API Call/ Explanation](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/windows-api-call-explanation__1-39.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/madwizardbd-all-about-beep-api-article__1-38784/archive/master.zip)





### Source Code

<p align="justify">&nbsp;</p>
<p align="justify"><b><font color="#FF0000" size="5" face="Tahoma">All About
Beep API<br></font></b><font face="Tahoma" size="2"><br>
<font color="#0000FF"><b>Introduction<br>
</b></font>Today we will discuss about the Beep API which is very simple to use.
You may think that what the Beep API can do without beeping. But, wait there's
more what you can do with this API. You can also drive the mosquitos away using
this technique! Let's have a look at them.<br>
<br>
<b><font color="#0000FF">The Beep API</font><br>
</b>The function is synchronous, so it doesn't return control to its caller
until the sound finishes. Actually if you have Win9x OS such as Windows95/98/ME,
there is nothing more you can do than beeping with this API. So, it would be
better if you use the built-in VB command 'beep' instead of using Beep API. You
can generate 37Hz to 32768Hz (inclusive) frequency on WinNT/2000/XP and it is up
to you how long your VB program will generate this frequency using your PC
Speaker. Let's take a look at this one of the simpliest APIs use...<br></p></p><p align="justify"><font face="Courier New" size="2" color="#008080">
</font></font><font size="2" face="Courier New" color="#000080">Private Declare Function Beep Lib &quot;kernel32&quot; Alias &quot;Beep&quot; (ByVal _<br>dwFreq As Long, ByVal dwDuration As Long) As Long</font><font size="2"><font face="Courier New"><br></font>
</font>
<font face="Courier New" color="#008000"><br>
</font>
<font size="2" face="Courier New" color="#0000FF">Private Sub Form_Load()</font><font size="2"><font face="Courier New" color="#008000"><br><br>'36 &lt; Frequency &lt; 32768 and Duration in miliseconds.<br>
' here we are using Frequency=11000 and Duration = 1000<br>
'so set the variable<br><br>
</font>
<font face="Courier New" color="#0000FF">Freq=11000<br>
Duration=1000<br>
ai = Beep(Freq,Duration)</font><font face="Courier New" color="#008000"><br><br>
'if success ai &lt;&gt; 0<br><br>
</font>
</font><font size="2" face="Courier New" color="#0000FF">End Sub</font><font size="2"></font></font></font></font></p>
<p align="justify"><font face="Tahoma" size="2">
In this code, first we have declared the Beep API and set the arguments to pass.
The first argument it takes is dwFreq, and the last one is dwDuration. As we
would like to generate 11KHz of frequency for 1 second. We've just simply set
variable to pass. Here you should remember that the dwDuration argument is in
miliseconds. So, if you set this to 1000, it will generate sound for 1 second.
So, you can also drive the mosquitos away using this technique!<br>
<br>
<font color="#0000FF"><b>Conclusion</b><br>
</font>And this is exactly all about. Hope I'll introduce you with few good
stuffs in VB programming. Never forget to contact me for any question, comments
regarding Win32 API, VB, Java etc. Contact me without hesitation. My email
address is MadWizardBD@hotmail.com. I'll be happy to help you. LET ME KNOW WHAT
DO YOU THINK!!! AND NEVER FORGET TO RATE!!</font></p>

