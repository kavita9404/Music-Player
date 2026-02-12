🎵 Music Playlist Manager (DSA Project)
📌 Overview

This project is a console-based Music Playlist Manager implemented in C++ using fundamental Data Structures concepts.

It simulates a simple music player where users can:

Create a playlist

Add / Delete songs

Search songs

Play songs

View recently played tracks

Sort playlist

Store playlist in file

This project demonstrates practical implementation of:

Doubly Linked List

Stack

File Handling

Dynamic Memory Allocation

String Handling

🧠 Data Structures Used
1️⃣ Doubly Linked List

Used to:

Store playlist songs

Navigate forward & backward

Insert at end

Delete by position

Delete by search

Sort playlist

Each node contains:
struct node
{
    char song[100];
    struct node *next;
    struct node *prev;
};

2️⃣ Stack (Recently Played Songs)

Implemented using Linked List.

Used to:

Track recently played songs

Display last played song

Display recently played history

3️⃣ File Handling

File: playlist.txt

Used for:

Saving songs permanently

Loading playlist from file

Updating file on delete

🚀 Features
✅ Add Song

Adds song to playlist (end of list)

Saves song to file

✅ Delete Song

Delete by search

Delete by position

Removes from file

✅ Display Playlist

Shows all songs

✅ Count Songs

Displays total number of songs

✅ Search Song

Linear search in playlist

✅ Play Song

Plays selected song

Pushes into recently played stack

✅ Recently Played

Shows history (stack)

✅ Last Played

Shows top element of stack

✅ Sort Playlist

Bubble sort implementation on linked list

✅ Load Playlist From File

Reads saved songs from playlist.txt

