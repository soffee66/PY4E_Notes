1. Web Services is to send data across the net, with an agreed upon wired format
   - undergo "serialization"
2. XML (eXtensible Markup Language)
   - its primary purpose is to help information systems share structured data
   - XML Elements (Nodes)
     - Simple Element
     - Complex Element
     - Attributes
   - Think of XML as paths (trees of data)
3. XML Schema
   - Description of the legal format of an XML document
   - XML document and XML Schema Contract go through the XML validator
     - xs:elememt
     - xs:sequence
     - xs:complexType
4. **Quiz Question**
*If you were building an XML Schema and wanted to limit the values allowed in an xs:string field to only those in a particular list, what XML tag would you use in your XML Schema definition?*
 xs:sequence
 **xs:enumeration**
 xs:element
 maxOccurs
 xs:complexType
5. JSON
   - JSON comes from the literal syntax of JavaScript
   - Represents data as nested "lists" and "dictionaries" (is a data interchange format)
   - it's simpler than XML, so the big movement prefers it over XML for less complex situations
6. Service Oriented Approach
   - most non-trivial web applications use services
   - services publish the "rules" applications must follow, aka API
