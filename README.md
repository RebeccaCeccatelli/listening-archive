# Listening Archive

Every clip generated in the final round of sweeps for the Master's thesis on Tonic, an Energy-Based Transformer for
symbolic music: unguided generation and single- and multi-attribute control, by Tonic and the Llama / GPT-2 baselines.
More about Tonic (thesis, showcase, survey, demo): https://rebeccaceccatelli.github.io/tonic/

Live: https://rebeccaceccatelli.github.io/listening-archive/

The site (≈626 MB of audio) is not stored in git. It is built on the cluster by
`demo/archive/build_archive_site.py` in [music_EBT](https://github.com/RebeccaCeccatelli/music_EBT) and attached
to the latest release here as `archive.zip`; the Pages workflow downloads that file and publishes it.

To update: upload a new `archive.zip` to the release (`gh release upload site archive.zip --clobber`), then run
the workflow (`gh workflow run pages.yml`).
