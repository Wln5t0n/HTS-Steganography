# HTS-Steganography
Hack this site stego solution
# Mission level 1
Challenge link [here](https://www.hackthissite.org/missions/playit/stego/1)

![Mission 1](https://github.com/sar1m/HTS-Steganography/blob/main/file/a.png)

**HINT**: This is an encoded message, the only tip you get is '2 null bytes'
# solution
Open the picture in a hex editor and search for two null bytes.

![hex_editor](https://github.com/sar1m/HTS-Steganography/blob/main/file/hex.PNG)

converting 16 to binary shows 0 as least significant bit

Binary convertor link [here](https://www.rapidtables.com/convert/number/hex-to-binary.html)

![hex to binary](https://github.com/sar1m/HTS-Steganography/blob/main/file/16.PNG)

converting 17 to binary shows 1 as least significant bit

![hex to binary](https://github.com/sar1m/HTS-Steganography/blob/main/file/17.PNG)

Now replace 16 with 0 and 17 with 1 .As we know that every 8-bit binary digits represent one ASCII character. Therefore, one bit is missing. After some hit and trials, I found that the missing bit is the trailing 0 of the first character. Now, after decoding the binary we get the password.

Binary to ASCII convertor link [here](https://www.binaryhexconverter.com/binary-to-ascii-text-converter)

![Binary to ascii](https://github.com/sar1m/HTS-Steganography/blob/main/file/as.PNG)

| binary | char | 
|--------|------|
|00111000|8|
|00110011|3|
|00110111|7|
|01101000|h|
|01100001|a|
|01110011|s|
|00110110|6|

Password = **837has6**

----

# Mission level 2
Challenge link [here](https://www.hackthissite.org/missions/playit/stego/2)

Download file link [here](https://www.hackthissite.org/missions/stego/lvl/2.wav)

**HINT**:did I hear that correctly?  
# solution
Download the audio file.

Audio file consist of whitenoise.

Use Audacity and view the spectrogram of the audio wave.

you will find the password.


Password = **jb298abc9qb2**

----

# Mission level 3
Challenge link [here](https://www.hackthissite.org/missions/playit/stego/3)

![Mission 3](https://www.hackthissite.org/missions/stego/lvl/3.bmp)

**HINT**:Look carefully: it's obvious, just not at first sight 
# solution
Open the photo in Forensically website.

Forensically link [here](https://29a.ch/photo-forensics/#forensic-magnifier)

Check the principal analysis conponent.
you will find the password.




Password = **n38f298hsjf**

----

# Mission level 4
Challenge link [here](https://www.hackthissite.org/missions/stego/template.php)

![Mission 4](https://github.com/sar1m/HTS-Steganography/blob/main/file/stego4.gif)

**HINT**: I am being hexed!.
# solution
Open the picture in a hex editor and scroll down to bottom.

![hex_editor](https://github.com/sar1m/HTS-Steganography/blob/main/file/lvl4b.PNG)

Convert the binary to ascii

![Binary to ascii](https://github.com/sar1m/HTS-Steganography/blob/main/file/lvl4a.PNG)

Password = **p68cq1hb**

----

# Mission level 5
Challenge link [here](https://www.hackthissite.org/missions/playit/stego/5)

![Mission 5](https://www.hackthissite.org/missions/stego/lvl/stego5.bmp)

**HINT**:  
# solution
 


Password = **hgbvZw07**

----
# Mission level 6
Challenge link [here](https://www.hackthissite.org/missions/playit/stego/6)

![Mission 6](https://www.hackthissite.org/missions/stego/lvl/stego6.png)

**HINT**:  
# solution
Extract the strings from the picture
Check the strings you will find code that looks like it is encoded in Base64

code=Tm90IGxpa2UgaXQncyBoYXJkIHRvICdkZWNyeXB0JyB0aGlzIGh1aD8gVGhlIHBhc3N3b3JkIGlzIGhnYnZadzA3Lg==

Decode this code with Base64 decoder\

Decoded=Not like it's hard to 'decrypt' this huh? The password is hgbvZw07.


Password = **hgbvZw07**

----
# Mission level 7
Challenge link [here](https://www.hackthissite.org/missions/playit/stego/7)

[Mission 7](https://www.hackthissite.org/missions/stego/lvl/stego7.zip)

**HINT**:  
# solution

DOwnload and extract the zip file.

It is a .tif extension.

Open the file in photoshop.You will find three layers of the image.

turn off the first layer you will get the password.


 
Password = **4aH5CEta**

----
# Mission level 8
Challenge link [here](https://www.hackthissite.org/missions/playit/stego/8)

![Mission 8](https://www.hackthissite.org/missions/stego/lvl/stego8.bmp)

**HINT**:  
# solution
Open the picture in hex editor.

scroll to the middle.

You will find= p��a��s��s��w��o��r��d��=��Y��r��R��o��t��7


Password = **YrRot7**

----
# Mission level 9
Challenge link [here](https://www.hackthissite.org/missions/playit/stego/9)

Download file link [here](https://www.hackthissite.org/missions/stego/lvl/Stego9.zip)

**HINT**: kiss me alone 
# solution
 Peform spectrum analysis of the song.
 You will find long and small dashes in the soundtrack.
 
Spectrum analyser link [here](https://academo.org/demos/spectrum-analyzer/)

It is morse code .Taking small dash as a dot(.), large dash as (-), small space as space and large space as (/). On decoding, we get the following Morse code.

".---- ----- --... / ..... -.... / .---- ..--- ----- / ....- ---.. / .---- .---- ----. / ..... ...-- / ----. ---.. / ----. ---.. / .---- .---- --... / .---- .---- ...--
"

Decoding the moorse code we get decimal numbers


morse code decoder link [here](http://www.unit-conversion.info/texttools/morse-code/)


107 56 120 48 119 53 98 98 117 113

convert the decimal into ascii you will get password


Decimal to ascii converter link [here](https://onlineasciitools.com/convert-decimal-to-ascii)

Password = **k8x0w5bbuq**

----
# Mission level 10
Challenge link :- [here](https://www.hackthissite.org/missions/playit/stego/10)
![Mission 10](https://github.com/sar1m/HTS-Steganography/blob/main/file/10.png)
# solution 
<p>Stego 10<br />
Look at the picture of the words.<br />
encode it yourself, then decode with version 2.<br />
For every bold letter is a B<br />
and<br />
For every not bold letter is a A</p>
<p>The first one I think looks like BAABB = T.<br />
BAABB = T<br />
AABBB = H<br />
AABAA  = E<br />
ABBBB = P<br />
AAAAA  = A<br />
BAAAA &#8230;&#8230;..AND SO ON!</p>
<p>answer = thepasswordisnothere<br />
So just use that and its complete: nothere<br />
Done!</p>

----
# Mission level 12
Challenge link :- [here](https://www.hackthissite.org/missions/playit/stego/12)

![Mission 12](https://github.com/sar1m/HTS-Steganography/blob/main/file/12.bmp)
# Solution
<p>This given bitmap has a single row of grey values, with the hint &#8216;I am the not of a file&#8217;. This sounds like the values are the &#8220;not&#8221; as in, inverse of a file. This python script I wrote will spit out the values of the bitmap:</p>
<p>#!/usr//bin/python<br />
import Image<br />
import sys<br />
im = Image.open(&#8220;12.bmp&#8221;)<br />
newnumber = 0<br />
oldnumber = 0<br />
counter = 0<br />
width = range(0,123)<br />
hight = range(0,1)<br />
for each2 in hight:<br />
for each1 in width:<br />
it = im.getpixel((each1,each2))<br />
print chr(255-it),<br />
sys.stdout.softspace = 0<br />
print<br />
If you run this you get:</p>
<p>PK???t??8ZJ?Gpass.txt6ae4nt5TBPK????t??8ZJ?G? pass.txtPK???6/<br />
There is something in there&#8230; is that a zip file?</p>
<p>$ python decode.py &gt; file<br />
$ file file<br />
file: Zip archive data, at least v2.0 to extract<br />
$ unzip file<br />
Archive:  file<br />
extracting: pass.txt<br />
$ cat pass.txt<br />
6ae4nt5TB</p>
<p>So the password is: 6ae4nt5TB</p>
