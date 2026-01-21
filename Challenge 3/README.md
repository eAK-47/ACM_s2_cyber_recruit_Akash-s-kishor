## Challenge discription

There is html code given we have to find flag in it

## Explanation

found out that these flag are divided into parts

there was part a,part b in comments so i tried to decode it using website base64 decoder
and got output part1,part2

from this i got idea that this flags are divided into parts

checked for this type of strings in that code and found part 3 in var urlEncoded = encodeURIComponent("UEFydDM=");

decoded that string and got part3

part 4 was difficult and got idea that in each string "UEFy" was common,so checked for similar string and got part4

# Flag{part1part2part3part4}

