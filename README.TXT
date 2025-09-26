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