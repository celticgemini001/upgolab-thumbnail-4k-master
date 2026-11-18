# Making a 4K Thumbnail Master From a 720p Frame

A thumbnail has one job: survive being shrunk. Measured round trip through an 8x master and back to 320px: the edge contrast gain from sharpening vanishes, but a small-radius pass still helps. On real photographs the radius budget is 0.25 feed pixels and the gain is about half a decibel — not the 2.9 dB a synthetic test suggests.

**Read it with the tables and the reproduction snippets:** <https://celticgemini001.github.io/upgolab-thumbnail-4k-master/>

## About this repo

This repository exists to serve one measured article. Every number in it came from
ffmpeg and numpy run on real files on this machine — the commands are in the page so
you can re-run them and get the same rows. Where the measurement contradicted the
hypothesis, the page says so.

## The tool behind the notes

<https://upgolab.com> — browser-based AI upscaler for photos and short video.

## Index

All the guides are cross-linked from the hub:
<https://celticgemini001.github.io/upgolab-tools/>
