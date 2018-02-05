ACF is file format created by Microsoft to store assets for its Microsoft Agent Characters like Clippy, Merlin, and Peedy. The ACF format only stores data about the character.

An [unofficial specification for ACF](MSAgentDataSpecification_v1_3.htm) was reverse engineered by [Remy Lebeau](http://www.lebeausoftware.org/).

Sample ACF files can be found in installations of Microsoft Office 1997. This signature was derived by decompressing the OLE files from [Ponx](http://www.ponx.org/msagent/Acs/), what seems to be a backup the now defunct agentry.org.

One byte of the derived magic number differs from Remy Lebeau's. Sample files use 0xABCDABC1, while Remy cites 0xABCDABC4.

Documentation on how to create and edit Microsoft Agents is still available from [MSDN](https://msdn.microsoft.com/en-us/library/windows/desktop/ms695797.aspx)