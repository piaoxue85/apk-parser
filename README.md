A pure java apk parser.

for now, the following is (partially) supported:
* resource table by ResourceTableParser
* binary xml file by BinaryXmlParser
* dex file by DexParser
* certificate by CetificateParser

the easiest way is to use the ApkParserUtils class, which contains convenient static mehods to get AndroidManifest.xml, apk meta infos, etc.
