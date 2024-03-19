Java FX fix for Apple Silicon
=========================

Background: Java is essentially slightly broken on the latest version of Mac OS (Sonoma 14.4): See [here](https://bugs.java.com/bugdatabase/view_bug?bug_id=8327860) and [here](https://blogs.oracle.com/java/post/java-on-macos-14-4) If you have not updgeaded, it is best to wait until after the coursework.

1. In the pom.xml file (for both the model and the AI), modify the javafx.version field from ```17.02``` to ```23-ea+3```:
![pom.xml exit](AppleSiliconJavaFXfix.png)

2. Delete you local Maven repo. In the terminal type: ```mv ~/.m2 ~/.old_m2```

3. Reaload Maven in Intellij:
  
   ![maven reload](mavenreload.png)

4. Try running the GUI again:
   ![run model](rungui.png)
