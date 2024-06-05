Hi,

Just how you can see below, there some Introduction, what kind of skill you need to have to start that room.
Must have in that room is a burpsuite, don't forget to install foxyproxy to traffic your package. If u still don't have it, just search in google.
Start the machine (you can find in the right corner)

![image](https://github.com/Anogota/XXE_Injection/assets/143951834/fa75e401-29ac-4bd9-98bc-651702df797c)

Let's go the next task.

  2.Exploring XML
Obviously i can commend to do by your self overview that.
First what we have is a What is XML, we can find there a lot of intresting information.
XML is a language derived from SGML (Standard Generalized Markup Language) which is the same standard that HTML is based on.
Where we use typically MXL, typically used by applications to store and transport data in a format that's both human-readable and machine-parseable.  XML consists of elements, attributes, and character data, which are used to represent data in a structured and organized way. Like in HTML.

XML Syntax and Structure
XML elements are represented by tags, which are surrounded by angle brackets (<>). Tags usually come in pairs, with the opening tag preceding the content and the closing tag following the content. For example:

```
<?xml version="1.0" encoding="UTF-8"?>
<user id="1">
   <name>John</name>
   <age>30</age>
   <address>
      <street>123 Main St</street>
      <city>Anytown</city>
   </address>
</user>
```

The tags like name,age,street,city represents an elements with some content, tag <user id="1"> pecifies an attribute "id" with the value "1" for the element "user". 

<?xml version="1.0" encoding="UTF-8"?> declaration indicates the XML version, and the element contains various sub-elements and attributes representing user data.

The image below shows the type of entities in a DOM structure:
![image](https://github.com/Anogota/XXE_Injection/assets/143951834/130820ef-0df4-4615-a548-a31fa07c1a37)

