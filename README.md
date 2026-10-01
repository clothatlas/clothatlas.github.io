# ClothAtlas project page

Project page for *ClothAtlas: Joint Garment Identification and State Estimation under Self-Occlusion*.

Static site served by GitHub Pages from the `main` branch root. Preview locally with:

```sh
python3 -m http.server 8000
```

- Figures in `static/images/` are cropped from the ICRA 2027 submission PDF (`ClothParticles-ICRA-2027`, `main.pdf`, 300 dpi).
- `static/videos/clothatlas.mp4` is the supplementary video, remuxed with `-movflags +faststart` for streaming.
- `static/videos/{identification,temporal,real}/` are result clips from the shared `ClothAtlas-ICRA2027` Drive folder (`videos_identification/*/full_figure.mov`, `video_temporal/*/full_figure.mov`, `method_figure/{pants,tops}{,_dd}/*/clip.mp4`), re-encoded to H.264 with `+faststart`. Transparent ProRes composites are flattened on white; each real-world robot-camera clip joins the first- and second-grasp clips, and the side-camera clip holds its last frame to match. Posters in `static/images/posters/` are the first frames.
- Layout adapted from [Nerfies](https://github.com/nerfies/nerfies.github.io) (CC BY-SA 4.0).

Before publishing: the paper is under double-anonymous review, and the author list, paper link, code link and BibTeX are placeholders (see `TODO` comments in `index.html`).
