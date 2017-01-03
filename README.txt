Ariella Kahan and Julia Hou
Project: iTerminal

OVERVIEW:
Our project works similarly to iTunes. You begin with a library containing four songs, and you can add more songs to the library (or to specific playlists, which you can create). In order for the “play” or “shuffle” function to work, the songs must be in the same directory as the project and they must be .wav files. Also, this project will only work on macs because we use the “afplay” terminal command; in order for this to work on a Linux, “afplay” would have to be changed to “aplay.”

When you create a library, the four already-added songs are “Let it Be,” “Big Yellow Taxi,” “Fake Plastic Trees,” and “Breathe Again”. We included these four songs — and four additional songs (“Cantaloop” by US3, “Mr. Jones” by Counting Crows, “Down By The Water” by The Drums, and “Tears In Heaven” by Eric Clapton), that you can add to the library or to playlists in order to test our code — in a folder on Google drive, which you can access using this link: https://drive.google.com/folderview?id=0B2pvlIfrCKc3LWpvTXo4aXlfQmM&usp=sharing  

You compile the project using makefile, and use the project by following the directions. You must make an account before logging into it. Our project has the following files: 

FILES:
1. libraryf.c
This contains all of the functions we use. The first function used is the one that allows you to create or sign into your account. After creating an account or logging into it, a document called <username>.txt is opened; this document includes all the songs in the library, and all the songs in playlists. When you add songs to the library and to playlists, you write to this file. And when we use this file to lists songs to play or to use in other functions, we transfer the contents of the file into a double array.

2. libraryf.h
This is the header file accompanying libraryf.c

3. main.c 
This is the file where we ask for user input, so that the user can decide what functions of the library to use.