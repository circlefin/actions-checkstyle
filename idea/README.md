# IntelliJ IDEA Integration
If you use IntelliJ for development, it is very helpful to setup IntelliJ so that its Reformat Code capabilities produce Checkstyle-compliant code. 

To do this, first install the CheckStyle-IDEA plugin.
![Checkstyle-IDEA Plugin](assets/checkstyle-idea-plugin.png)

Then import `checktyle-circle.xml` as a **CheckStyle Configuration** under **Editor -> Code Style**:
![Import Code Style](assets/import-code-style.png)

You will also need to ensure your **Import Layout** is correct, which is in the **Imports** tab under **Editor -> Code Style -> Java**
![](assets/codestyle-java-imports.png)

At the bottom of this screen, ensure your **Import Layout** looks like this:
![](assets/import-layout.png)