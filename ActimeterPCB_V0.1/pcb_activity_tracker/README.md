Template PCB Project
====================

This is a template PCB project to help you setup a new project according to the
[PCB Guidlines Document][pcb_guidelines].

Quickstart
--------

To start a new project using this template you must first decide on two things:
1. Pick a project name. It should be short, all lower case and describe the purpose
   of the PCB in a meaningful name.
2. Pick a variant name. By using variants we are able to add components that may
   not be needed and mark them as not populated. If you are not shure what variant it is
   you can pick "initial" for now.

After deciding on these names you should do the following steps:
1. Rename all the `"project.*"` files to the project name.
2. Rename the `"project_variant.OutJob"` file to `"<project-name>_<variant-name>.OutJob"`.  
   If you have multiple variants create an OutJob file for each of them.
3. Open the altium project file and accept that it cannot find the files you just renamed.
4. Add the files to the project.
5. Rename the current variant to the variant name you picked.
6. Remove the "Installed" libraries from Altium. (see the [PCB Guidelines][pcb_guidelines])
7. Follow the design-checklist.txt document and update the output paths of the outputs.

It is good practice to add new items to the design-checklist.txt as you encounter
new constraints while developing the PCB. This will help in checking whether a 
design is ready for production. Adding more stuff to this file will make the checking better.

[pcb_guidelines]: https://docs.google.com/document/d/19WRGJmLK43YIEdcvINFX_yF6rSxiYO2XFBLLL6wZ0xA/edit?usp=sharing
