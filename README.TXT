Project: midi-player
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

41) I see dih.addNote("C", 12); You can play with this.

43) Yes you can

45) External code: tune.getNotes()
    Internal code: addNoteToTrack(noteValue, track, tick, duration);
    
46)

47) I used this code to modify the TuneCreator source code, so that it creates a MidiPlayer object.
public class TuneCreator {
    private MidiPlayer player;

    public TuneCreator() {
        player = new MidiPlayer();
    }
}

48)

49)

50) I succesfully changed it by putting the value that stands for the Piano.

51)

52) This code gives the same result.

public String getDisplayValue() {
    return String.format("%02d", value);
}

53)

54)

55)

56)

57)

58)


