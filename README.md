# js-epub-maker

`js-epub-maker` will allow you to create and download epubs. It offers an API through which you can set meta info, navigation and content.

This project is not a full blown epub configurator and publisher: to reduce the complexity and time needed to accomplish offering epubs to end-users, this project relies on sample templates which can be populated using `js-epub-maker`'s API.

The sample templates are (initially) taken from IDPF's own samples: http://idpf.github.io/epub3-samples/


Currently the only template supported is [idpf's wasteland epub sample](http://idpf.github.io/epub3-samples/samples.html#wasteland) ([source code](https://github.com/IDPF/epub3-samples/tree/master/30/wasteland)). This template is suitable for generating books in epub format with a single continuous content page. Includes navigation compatible with the older epub2 standard.