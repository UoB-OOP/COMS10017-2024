Java FX fix for Apple Silicon
=========================

1. In the pom.xml file (for both the model and the AI), modify the javafx.version field from ```17.02``` to ```23-ea+3```:
![pom.xml exit](AppleSiliconJavaFXfix.png)

2. Delete you local Maven repo. In the terminal type: ```rm ~/.m2```

Reaload Maven in Intellij:
