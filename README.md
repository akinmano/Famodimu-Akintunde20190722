# Famodimu-Akintunde20190722
Operating Instructions
The program was written according to the stipulated conditions, which are:
Each entry has a rank, a suit, and a color:
•The rank of each entry is determined by its initial character(s), where: the rank of "A" equals 1; the rank of "2" through "9" equals the corresponding integer; and the rank of "10", "J", "Q", and "K" equals 10.
•The suit of each entry is determined by its final character, where: the suit of "C" = Club; the suit of "H" = Heart; the suit of "S" = Spade; and the suit of "D" = Diamond.
•The color of each entry is determined by its suit, where: the color of Clubs and Spades is Black; and the color of Hearts and Diamonds is Red.

Below are the specifications relating to the program for the software engineering challenge:
Language: Ansible Playbook
Ansible version needed:Ansible 2.7
Name of Playbook: batch.yml
Input file is test-input.json
Run command: ansible-playbook batch.yml -e @test5-input.json
Expected error message: Batch is invalid 
