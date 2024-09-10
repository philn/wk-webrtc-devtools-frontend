# WebKit WebRTC devtools frontend

This is a standalone web page, it can be used to display graphs, given a JSON stats file.

Hopefully this can also be used for live-graphing within WebKit itself, either
in the WebInspector or with a custom URI protocol handler.

```shell
python -m http.server
```

Then select one of the sample JSON provided in this repository.

The graphs currently show stats about the outbound video RTP stats. More will
come, this is a proof-of-concept.
