# Nova

Nova is a fork of Notational Velocity based on Brett Terpstra's [nvALT][nvalt]. It includes a few additional features for tracking large numbers of projects by aggregating tags and tasks.

[Notational Velocity][notational] is a way to take notes quickly and effortlessly using just your keyboard. You press a shortcut to bring up the window and just start typing. It will begin searching existing notes, filtering them as you type. You can use &#x2318;-J and &#x2318;-K to move through the list. Enter selects and begins editing. If you're creating a new note, you just type a unique title and press enter to move the cursor into a blank edit area.

## Changes and Additional Features

* Do not refocus search bar when using hotkey to toggle window visibility.
* Display only the first line of each note in previews.
* Highlight lines containing @todo in red.
* Highlight *special tags in black.
* When sorted by tag, list notes with *special tags first.
* @todo: Aggregate the number of todo tags in each note in the note listing.
* @todo: Aggregate todo items in the home screen when no note is selected.

## Building

Nova is not built with code signing, so you should be able to build out of the box. For Simplenote synchronization, follow the instructions in SimperiumConfig-example.h to obtain an API key.

## Credits

* [nvALT 2][nvalt]
* [Notational Velocity][notational]
* Code: The original Notational Velocity [source code][original source] by Zachary Schneirov
* Code: DivineDominion's [MultiMarkdown fork][DivineDominion]
* Inspiration: [Elastic Threads' version](http://elasticthreads.tumblr.com/nv) of Notational Velocity

[nvalt]: http://brettterpstra.com/projects/nvalt/
[notational]: http://notational.net/
[original source]: https://github.com/scrod/nv
[DivineDominion]: https://github.com/DivineDominion/nv

