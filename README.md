<h1> AudSecure </h1>
<b><i>Audio cryptography tool with steganographic techniques</i></b>
<br>
It has two components:<br>
<b>1. Audsteg<br>2. Audspy</b><br><br>
<h2> Audsteg:</h2>
Audsteg turns an audio file into encrypted text and then decrypts the encrypted text, returning the original audio as output.

<h1> Steps to work: </h1>

```
pip3 install cryptography
git clone https://github.com/technoreck/AudSecure.git

cd Audsteg
python3 Audsteg.py
```

 <h2> Audspy:</h2>
 
 
<b></i>Simple audio steganography tool</b></i>

Audspy will hide the plain text inside the given audiofile.

<h2> Hiding using Audspy: </h2>

```
Audspy_hid.py [-h] [-f AUDIOFILE] [-m SECRETMSG] [-o OUTPUTFILE]
```

option|usage
------|-----
 -f | to specify the intial audiofile
 -m | for the secrete message to be hidden inside
 -o | name of the output file
 
 <h2> Extracting using Audspy: </h2>
 
 ```
 Audspy_ext.py [-h] [-f AUDIOFILE]
 ```
 -f is to specify the audio file   
