# Naver TTS API For Japanese

This script uses the Naver TTS API (found on e.g. papago.naver.com) to produce the pronunciation
for a given Japanese phrase and saves it as an mp3 file.

I use this for automating the process of adding pronunciation samples to electronic flashcards.

For testing purposes, the script defaults to playing the mp3 after downloading it. Once you've
confirmed it works, comment out the last line to just download the file without playing it.

I did test on Python 3.7-32 for Windows.

## Usage

`python naver.py [TEXT] [OUT_FILE.MP3]`

## Example

`python naver.py "こんにちは" hello.mp3`

## Download cmdmp3.exe for MP3 player on windows command line

http://www.mailsend-online.com/wp/cmdmp3new.zip
