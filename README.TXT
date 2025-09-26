test test


#21 created a music organized object added file names, used listAllFiles and saw the files print

#22 I imported ArrayList, created new ArrayList<String>()

#23 I set a breakpoint and used to the debugger. 
private ArrayList<String> file = <object reference>
private MusicPlayer player = <object reference>

#24  public void listWithIndex()
    {
        int position = 0;
        for(String filename : files) {
            System.out.println(position + ":" + filename);
            position++;
        }
    }
    
#25 public void listMatching(String searchString)
    {
        boolean found = false;
        for(String filename : files) {
            if (filename.contains(searchString)) {
                System.out.println(filename);
                found = true;
            }
        }
        if (!found) {
            System.out.println("No matches found for: " + searchString);
        }
        }
        
#27 I made a method that plys all tracks
public void playArtist(String artist) {
        for (String filename : files)  {
            if(filename.contains(artist)) {
                player.playSample(filename);
            }
            
        }
    }