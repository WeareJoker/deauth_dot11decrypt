# deauth_dot11decrypt
It sends deauth packet to all stations for getting keys in 4-way handshakes from stations already connected to an AP. 
When it detected 4-way handshakes with a station and an AP, it stops sending deauth packet to that station.

# USAGE
Go to the folder which contains dot11decrypt.cpp and 
overwrite this dot11decrypt.cpp.
mkdir deauth_build
cd deauth_build
cmake ../
make
