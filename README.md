# sokoban-js

JS module to load data, render and record playback of sokoban moves

## Usage

1. open sokoban.html. Note: Only Chrome supports ccapture recording.
2. Load a sokoban level from the "Load Level" button. These are specified in `stims/local_stim.js`

### Recording Moves

1. Click "Record" button when you are ready to start recording moves.
2. Play the game and make moves.
3. Click "Stop" button when you are done.

Right now, clicking "stop" will trigger saving the movie file to the "Downloads" folder.

### Playback Moves

1. Click "Choose file" button to load a trace log file. If successfully loaded, you should see the list of moves printed as an array.
2. Specify playback settings
   - Update the speed of playback using the "Playback Speed" box, specifying milliseconds per move.
   - To skip some moves, update "Start playing from action N" to specify the starting action for playback.
3. Click "Play" button to start playback of the moves.
