### jrebel
---
https://github.com/topics/jrebel

https://zeroturnaround.com/software/jrebel/

```java
// src/com/example/intellijidea/plugins/generaterebelxml/FileTemplatesFactory.java

public class FileTemplateFactory implements FileTemplateGroupDescriptorFactory {
 
 public FileTemplateGroupDescriptor getFileTemplatesDescriptor() {
   FileTemplateGroupDescriptor descriptor descriptor = new FileTemplateGroupDescriptor("My extensions",AllIcons.Nodes.Plugin);
   final FileTemplateDescriptor fileDesc = new FileTemplateDescriptor("rabel.xml", StdFileTypes.XML.getIcon());
   descriptor.addTemplate(fileDesc);
   return descriptor;
 }
}

```

```
```

```
```


