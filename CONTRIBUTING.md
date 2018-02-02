# Contributing to File Format Signature Development

First, thank you for helping the community!

The following is a set of guidelines for contributing to the development of file format signatures in this repository. These guidelines are adopted from Ross Spencer's [Five Star Format Signature Development](http://openpreservation.org/blog/2016/06/14/five-star-file-format-signature-development/). You can send any proposed changes (or additional stars) to foster a stronger community in a pull request.

## Tell the community about your identification gaps
Do you have any files in your collection that could be used to develop new signatures?

If you're a DROID user Jenny Mitcham and Max Eckard have written about [their](http://digital-archiving.blogspot.com/2017/02/) [experiences](http://archival-integration.blogspot.com/2016/06/born-digital-data-what-does-it-really.html) profiling their collections.

If you're a Siegfried user, you can use the following command to find unidentified files from a Siegfried profile.
```
sf -replay *sf_report.ext* -log unknown
```

If you see any potential file formats in your reports, search this repository's format signatures and issue reports. If you can't find an existing signature or issue, file an issue in this repo. Here's an example issue report.

Title
> Potential name of the format

Body
> Short description of the format with any information you've gathered about it, including:
* what kind of information it holds
* what software produces it
* what communities use it
* what extensions are common
* links to any specifications or website
* any other information you have found that is relevant.

## Share sample files

It's important to test signatures against real examples of a file format. If you have created an issue or found an issue for a format you'd like to have identified, consider sharing sample files with the community in the issue thread.

If your organization restricts the sharing of digital materials with third-parties, consider documenting an exception for the purposes of format research. A [sample non-disclosure agreement](samples/sample_nda.md) is available if your organization requires one.

If possible, consider contributing your sample files to the [OPF Format Corpus](https://github.com/openpreserve/format-corpus).

## Develop basic signatures

To learn how to create a format signature, you can read posts on the subject by [Andrea Byrne](http://openpreservation.org/blog/2016/09/08/making-the-switch-from-user-to-user-and-contributor-my-first-file-format-signature/), [Jenny Mitcham](http://digital-archiving.blogspot.com/2016/08/my-first-file-format-signature.html), Nick Krabbenhoeft(https://nypl.github.io/digpres/2018/01/30/bashing-out-a-file-format-signature.html), and Ross Spencer[http://openpreservation.org/blog/2016/01/07/droid-container-signature-files-what-they-are-and-how-to-create-them-a-template-and-an-example-or-few/]

If you'd like to contribute a draft format signature, send it as a pull request. Pull requests should include the following items:

1. README.md - required, a basic description of the format with references to any resources found
2. *format-name*-pronom.xml - required, a PRONOM XML formatted signature file
3. *format-name*-droid.xml - optional, a DROID XML formatted signature file
4. *format-name*-roy.sig - optional, a roy-built profile
5. *sample-file.ext* - optional, any sample files that can be shared
6. *specification.txt* - optional, any files that detail the format specification

## Where feasible, engage openly with the community

If you need to find more sample files to test your signature or people to review your draft signature, reach out to the community. You can post on:

* [PRONOM Google Group](https://groups.google.com/forum/#!forum/pronom)
* [DROID Google Group](https://groups.google.com/forum/#!forum/droid-list)
* [Digital Curation Google Group](https://groups.google.com/forum/#!forum/digital-curation)
* Twitter

## Seek supporting evidence

Strengthen a draft signature with documentation about the format, whether its an official specification or an unofficial reverse engineering efforts. The [Just Solve It wiki](http://fileformats.archiveteam.org/wiki/Main_Page) is a great place to start your search and contribute your findings.

