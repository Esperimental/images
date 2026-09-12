# Rendering style experiments

Seven full-resolution exploratory images comparing rendering styles for the Esperimental workshop story. These are experiments, not approved production assets.

## Shared scene

A cute cream-and-navy inventor robot and an ordinary tuxedo cat face each other across a human-scale workshop bench. The robot is intended to stand about 137 cm (4.5 ft) tall. A plant, warm lamp, moonlit window, and restrained retro-futuristic workshop establish the world.

The original visual reference was the workshop banner in `Esperimental/blog-staging`. The first round deliberately stayed closer to that reference. The second round simplified the environment and surfaces to explore styles that may be easier to keep consistent between story images.

## Files

| File | Treatment | Notes |
| --- | --- | --- |
| `a-animated-film-cgi.png` | Animated-film CGI | Smooth dimensional materials and natural fur |
| `b-painterly-cgi.png` | Painterly CGI | 3D volume with gouache-like surface treatment |
| `c-miniature-film.png` | Miniature-film photography | Handcrafted model-set appearance |
| `d-cinematic-illustration.png` | Cinematic illustration | Anime-influenced drawing and selective contours |
| `e-clean-line.png` | Clean-line comic | Economical outlines, flat colour, sparse detail |
| `f-retro-futurist.png` | Retro-futurist animation | Mid-century forms and limited colour blocking |
| `g-soft-cel-3d.png` | Soft cel-shaded 3D | Rounded volume with simplified shadows and surfaces |

## Round one prompt

The reference image controlled the robot identity, tuxedo cat, and broad world. The shared composition placed the robot on the left and cat on the right at the workbench, with a plant, articulated lamp, moonlit window, and softly focused shelves. The robot was specified as short-human sized rather than a miniature. The four rendering variants were:

- **A:** polished stylized animated-feature CGI, physically convincing light, smooth ceramic panels, natural fur, and no painted texture.
- **B:** dimensional CGI overpainted with delicate gouache brushwork, tactile surfaces, and a modern storybook finish.
- **C:** practical stop-motion set photography with handcrafted puppets, tactile ceramic and metal, macro material detail, and sophisticated miniature lighting.
- **D:** anime-inspired cinematic environment illustration with clean selective contours, simplified cel-shaded characters, painted gradients, and graphic clarity.

## Round two prompt

The second round used D only to preserve the recognisable robot and cat. It explicitly avoided copying the antique clutter, scratches, and exact room. The scene used broad clean shapes, few panel seams, no fine greebles, a light wood bench, pale walls, one tidy shelf, one futuristic instrument, and a teal/cream/muted-orange/navy/green palette.

- **E:** European clean-line comic illustration with even contours, restrained flat colours, one or two shadow shapes, crisp silhouettes, and almost no gradients or texture.
- **F:** mid-century retro-futurist 2D animation with geometric forms, flat colour blocking, subtle paper texture, optimistic space-age furniture, and minimal shading.
- **G:** soft cel-shaded 3D with matte ceramic surfaces, two- or three-tone shadows, subtle ambient occlusion, graphic cat fur, broad leaves, and gentle depth of field.

## Current observations

D, E, F, and G simplify visual information in different ways. Simpler detail may reduce distracting variation between scenes, but character proportions and room layout will still need dedicated reference images.
