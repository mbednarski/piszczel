# Piszczel

Playing music using PC Speaker

Put in autostart on your school machine to make your teacher angry ;)

Created 12-03-2011 (when I was very young :D )

## Usage

There are two ways to use program

1. Just execute piszczel.exe Program will try to open music.txt file.
2. Give an argument - file name to open.
  
## File format
First line contains count of repeats and delay between plays (in seconds).
Every next line consist of: time (in miliseconds) and frequency(1) (in hertz).
Not number values or incorrect format causes undefined behavior.
For example please look at sample file

If prefer to use note names (like `c4`) you can use `convert_notes.py`
  
D. Authors

 mbednarski - code
 
 Gethiox - sample music [youtube](https://www.youtube.com/user/gethiox) [GitHub](https://github.com/gethiox).
 
(1) You can find it here: http://en.wikipedia.org/wiki/Piano_key_frequencies
