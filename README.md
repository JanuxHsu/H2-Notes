# H2-Notes
H2 database memo

'''
java -cp h2*.jar org.h2.tools.Server -tcp -tcpAllowOthers

jdbc:h2:tcp://localhost/~/Desktop/Test/prod
'''

# bat-Notes
Restart Explorer
```bat
taskkill /im explorer.exe /f
start "Shell Restarter" /d "%systemroot%" /i /normal explorer.exe
```

# jboss-Note
```
java -cp picketbox-5.0.3.Final.jar$CLASSPATH org.picketbox.datasource.security.SecureIdentityLoginModule password
```

```java
System.setProperty("java.awt.headless", "false");
System.setProperty("swing.defaultlaf", "javax.swing.plaf.metal.MetalLookAndFeel");
```
