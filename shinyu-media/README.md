# Shinyu hero animation media

This folder is for the 30-second, 16:9, muted looping, connected-mesh sphere/cube/pyramid hero video for shinyuembody.org.

Upload `connected_mesh_geometric_cube_pyramid_hero.mp4` to this folder on the `main` branch using GitHub's **Add file > Upload files** interface. GitHub's web upload accepts this 4.5 MB file.

Once uploaded, the raw MP4 URL is:

https://raw.githubusercontent.com/ljwair/ljwair/main/shinyu-media/connected_mesh_geometric_cube_pyramid_hero.mp4

Hostinger video snippet (embed into current custom-code hero section rather than a new player):

```html
<video autoplay muted loop playsinline preload="metadata" aria-label="Animated Shinyu connected mesh transforming from sphere to cube to pyramid">
  <source src="https://raw.githubusercontent.com/ljwair/ljwair/main/shinyu-media/connected_mesh_geometric_cube_pyramid_hero.mp4" type="video/mp4">
</video>
```

For a production commercial homepage, prefer a dedicated media CDN such as Cloudflare R2 after confirming the design. GitHub repositories are not an ideal long-term video CDN.
