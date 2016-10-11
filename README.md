# notes
A note taking app with minimal UI. Designed for keyboard use. A work in progress. Heavily influenced by [nv](http://notational.net/). All client code is at codepen at the moment. See demo link below.

Btw: If you're looking for a todoapp in the same vein - check out [Monday](https://github.com/karlpokus/monday)

# features
- modeless operation
- persistant storage in browser

# usage
### main input
- search/create note by typing
- create new note by <kbd>RETURN</kbd>

### search results
- navigate list by <kbd>TAB</kbd>
- select note from list by <kbd>RETURN</kbd>
- remove note from list by <kbd>DEL</kbd>+<kbd>RETURN</kbd>
- empty list by emptying main input field

### note
- save note body by <kbd>RETURN</kbd>
- update note title by typing a longer title
- remove note by <kbd>RETURN</kbd> in empty note body
- move from body to title by <kbd>SHIFT</kbd>+<kbd>UpArrow</kbd>

# demo
[demo](http://s.codepen.io/KarlPokus/debug/KgQXaj)

# TODOs
- [x] markdown - nope
- [x] use app controller
- [x] try out a component design with templates and events
- [ ] client router for sharing
- [x] title color based on note saved/not saved
- [x] update search regex
- [x] fix bug where user tabs past list
- [x] fix bug where selected listitem makes selected title

# licence
MIT
