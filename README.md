# CN-Practical-Exam
# Name- Sukaina Inam Naqvi 
# Examonation Roll no- 20020570033
# Semester -III 
# Subject- Computer Network Practical Exam
# ~~~~~~~~~~~~~~~~~~~~~~~~~
There are two questions:-
Q1.Simulate and implement go back n sliding window protocol.
Q2.Simulate Cyclic Redundancy Check (CRC) error detection algorithm for noisy channel.
# ~~~~ First Question Description ~~~~
Go Back N is an implementation of sliding window protocol
Go-Back-N ARQ is a particular instance of the automatic repeat request (ARQ) protocol, in which the sending process continues to send the number of frames determined by a window size even without receiving an acknowledgment (ACK) packet from the beneficiary. 
It is an uncommon instance of the general sliding window protocol with the transmit window size of N and get window size of 1. It can transmit N frames to the destination before requiring an ACK. 
The receiver process monitors the sequence number of the next edge it hopes to get and sends that number with each ACK it sends.
 The receiver will dispose of any casing that does not have the definite sequence number it expects and will resend an ACK for the last right in-request outline. 
Once the sender has sent the majority of the frames in its window, it will identify that the majority of the frames since the main lost edge are outstanding, and will go back to the sequence number of the last ACK it got from the receiver process and fill its window starting with that frame and continue the process over again. 
# ~~~~ Second Question Description~~~~
A cyclic redundancy check (CRC) is an error-detecting code commonly used in digital networks and storage devices to detect accidental changes to raw data.
Blocks of data entering these systems get a short check value attached, based on the remainder of a polynomial division of their contents.
On retrieval, the calculation is repeated and, in the event the check values do not match, corrective action can be taken against data corruption.
CRCs can be used for error correction.
CRCs are so called because the check (data verification) value is a redundancy (it expands the message without adding information) and the algorithm is based on cyclic codes.
CRCs are popular because they are simple to implement in binary hardware, easy to analyze mathematically, and particularly good at detecting common errors caused by noise in transmission channels. Because the check value has a fixed length, the function that generates it is occasionally used as a hash function.
