Revised: 2022-09-29

A zot registry can store and serve a variety of content, but the type of content may dictate your choice of a client tool.

For various content types, this document shows examples of using a third-party client tool that supports the content. The following table shows which content and client tools are demonstrated.

<table><colgroup><col style="width: 50%" /><col style="width: 50%" /></colgroup><tbody><tr class="odd"><td><p>Content type</p></td><td><p>Client</p></td></tr><tr class="even"><td><p>OCI images</p></td><td><p><a href="#using-skopeo">skopeo</a></p></td></tr><tr class="odd"><td><p>OCI images</p></td><td><p><a href="#using-regedit">regclient</a> (<code>regctl</code>)</p></td></tr><tr class="even"><td><p>OCI artifacts</p></td><td><p><a href="#using-oras">ORAS</a></p></td></tr><tr class="odd"><td><p>Helm charts</p></td><td><p><a href="#using-helm">helm</a></p></td></tr></tbody></table>

In the following examples, the zot registry is located at myZotRegistry.com, using port number 5000.

Using skopeo for OCI images
===========================
