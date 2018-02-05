ACA is file format created by Microsoft to store animation assets for its Microsoft Agent Characters like Clippy, Merlin, and Peedy. The ACA format only stores a single animation as a set of image frames and requires a corresponding ACF to supply further information about the character.

An [unofficial specification for ACA](MSAgentDataSpecification_v1_3.htm) was reverse engineered by [Remy Lebeau](http://www.lebeausoftware.org/).

Sample ACA files can be found in installations of Microsoft Office 1997. This signature was derived by decompressing the OLE files from [Ponx](http://www.ponx.org/msagent/Acs/), what seems to be a backup the now defunct agentry.org.

The OLE files carried the extension aaf, which might stand for Agent Animation File. According to the Lebeau spec, the first four bytes should correspond to a minor and major version number. In this case all files show as 1.30 and 1.31, but more samples would be useful for testing.

Documentation on how to create and edit Microsoft Agents is still available from [MSDN](https://msdn.microsoft.com/en-us/library/windows/desktop/ms695797.aspx)