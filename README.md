Entity-Framework-Code-Generation-Tools-Experiments
==================================================

Entity Framework Code Generation Tools Experiments : From EF.Utility.CS.ttinclude but all in a collection of .Net Classes.

EF.Utility.CS.ttinclude:

Have you ever tried to read and understand the 2500 lines of code in EF.Utility.CS.ttinclude?
I've made the Classes into *.cs files with a namespace, and created a simple Console Application to run some simple tests.
Now it's very easy to use the debugger to see what the library offers.

EF 5.x DbContext Fluent Generator for C#:

I've also taken this VSIX and looked at the *.tt templates in the included ItemTemplate.
The CSharpDbContextFluent.Mapping.tt template is the most complex and similarly I've taken the
supporting Classes and made them into *.cs files, with very little modification.

Have fun!
JsrSoft
June 2013


========================================================================================================

Thank you JsrSoft!  Your work made a project possible.

This fork reduces the Solution to one .NET 4.6.2 Class Library Project, with the intention of including that in other projects.

I did some renaming, and got it to build using EF6.

Only CodeGenerationTools and EntityFrameworkTemplateFileManager were updated from the latest EF6.Utility.CS.ttinclude file.

Christopher Grace
March 2018