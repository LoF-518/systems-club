Systems Club CTF challenges starting from 10th September, 2023.
Solved on 12th September 2023 after:
-- understanding the PKZIP binary structure
-- manually searching for the middle of the original zip file's hexdump using xxd to find the last "wrapper" zip 
-- copying that to create a binary zip out of the copied hexdump using xxd -r
-- extracting the flag.txt file.
