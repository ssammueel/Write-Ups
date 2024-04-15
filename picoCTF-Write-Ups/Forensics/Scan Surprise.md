# Scan Surprise

## overview
* forensics
* 100 points 

## Description
I've gotten bored of handing out flags as text. 
Wouldn't it be cool if they were an image instead?

challenge file [challenge.zip](https://artifacts.picoctf.net/c_atlas/14/challenge.zip)

## Hints
1. QR codes are a way of encoding data. While they're most known for storing URLs, they can store other things too.
2. Mobile phones have included native QR code scanners in their cameras since version 8 (Oreo) and iOS 11
3. If you don't have access to a phone, you can also use zbar-tools to convert an image to text

## Approach
download the file and unzip it

     $ unzip challenge.zip 
you are given a QR code
![Screenshot (405)](https://github.com/ssammueel/Write-Ups/assets/124765323/9d2adebc-5e7a-4dbe-b77e-05e8b80972d6)

mobile phone has many ways to scan a QR code

    $ 1. use goggle lens
    $ 2.use third party apps
you can olso use pc to scan codes

output of the scan will be flag
    

## flag
    picoCTF{ME74D47A_HIDD3N_b32040b8}

### solved by 
* git hub &rarr; [Samuel](https://github.com/ssammueel)
* potfolio &rarr; [Samuel potfolio](https://ssammueel.github.io/samuel.github.io/)

