# XML-Essential-Training

## Definition

The e**X**tensisble **M**arkup **L**anguage (XML) is a tag based syntax used to *structure* and *define* information.

## Examples

An xml fomat for storing business card data might look like
```
<BusinessCard>
    <name>P-Man</name>
    <number>07896088111</number>
    <company>TheInfoWars</company>
    <website>TheDataCrew.com</website>
    <email>P@Man.com</email>
</BusinessCard>
``` 

HTML, SVG, RSS are all examples of XML using a specific tag set


## Types of XML Content

Part | Example | Comments
---|---|---
XML Doc Declaration | `<?xml version = "1.0" encoding = "utf-8" standalone = "yes"?>` | Technically Optional, Encoding defaults to UTF-8
Elements (and attributes) | `<tag attribute='value'>stuff</tag>` | Same as html
Comments | `<!-- I am a comment -->` | Same as programming coments
Character Data | `<![[CDATA]This is unparsed text and data]]>` | Data ignored by an XML parser
Processing Instructions | `<?SpellCheckMode mode="en-GB"?>` | Instructions for the XML parser
Entity References | `Character (&#60;) and General (&Copyright;)` | Illegal characters to XML parser

## XML Syntax Rules

1. Must have a root tag (e.g. AlteryxDocument)
2. Close empty tags with a `<tag />`
3. Attribute values must be in quotes
4. Tags have to be properly nested



