theCloudNatives DNA
===================

> theCloudNatives DNA is a fork of the [Crisp DNA][crisp-dna] repository.
Similar to the Crips DNA, it describes how theCloudNatives collective works and
why. The source lives on github and is auto-published on
[dna.thecloudnatives.com][thecloudnatives-dna] every time a change is pushed.

[crisp-dna]: https://github.com/crispab/crisp-dna
[thecloudnatives-dna]: http://dna.thecloudnatives.com

## Getting started

Use Docker to run the DNA locally. The website will be served at the following
address: [https://localhost:4000](https://localhost:4000).

```bash
$ docker run --rm \
    -p 4000:4000 \
    --volume="$PWD:/srv/jekyll" \
    -it jekyll/jekyll:3.8 \
      jekyll serve
```

There is an auto-reload feature that automatically refresh the website when
change are made.
