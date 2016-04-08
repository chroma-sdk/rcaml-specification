# RCAML Specification
Working Draft: 8th April 2016

##What is RCAML?

Razer Chroma Animation Markup Language (RCAML) is an declarative language, suggested and initiated by [Adrian][wolfspiritm]. Specifically, RCAML is an initiativoe to create a common language for declaring animations for Razer Chroma peripherals via hierarchical structure. RCAML files can be freely created, edited and distributed by any person to be used in any applications that support it.

When you see them as part of your projects, RCAML files are essentially XML files with the .rcaml file name extension.

## RCAML libraries

A set of libraries will be made available in order to translate and consume the RCAML files within applications. Although the libraries are not strictly required in order to consume the file, it is highly recommended in order for the animations to run as intended by the file author(s).

### Proposed language support:
* C# (As an extension of the [Colore][Colore] library)
* C++

## Basic RCAML syntax

RCAML has a basic syntax that builds on XML. By definition, valid RCAML must also be valid XML. But RCAML also has syntax concepts that are assigned a different and more complete meaning, while still being valid in XML per the XML 1.0 specification. For example, RCAML supports property element syntax, where property values can be set within elements rather than as string values in attributes or as content. To regular XML, a RCAML property element is an element with a dot in its name, so it's valid to plain XML but doesn't have the same meaning.

## Contributing to the specification

Contributors are very welcome! In order to propose any changes, please [submit a pull request][newpull] here on GitHub to be included in the next working draft.

## License

Copyright &copy; 2016 by [@wolfspiritm][wolfspiritm] and [@njbmartin][njbmartin].

This project is licensed under the MIT license, please see the file [LICENSE][license] for more information.

Razer is a trademark and/or a registered trademark of Razer USA Ltd.  
All other trademarks are property of their respective owners.


[wolfspiritm]: https://github.com/wolfspiritm
[njbmartin]: https://github.com/njbmartin
[colore]: https://github.com/CoraleStudios/Colore
[license]: ../../blob/master/LICENSE
[newpull]: ../../pull/new/develop
