# systems-club
Contests by Systems Club @ IIT GN
Started on 10th September 2023

Solved on 12th September 2023 after:
- Understanding the PKZIP binary structure
> PKZIP has three major markers:
> * File Header marker
> * Start of Central Directory marker (this and the above together can be thought of as an "opening bracket")
> * End of Central Directory marker (this can be thought of as a "closing bracket")
- Manually searching for the "deepest" enclosed content in the hexdump (created using xxd)
- Copying that to create a binary zip out of the copied hexdump using xxd -r
- Extracting the flag.txt file.
