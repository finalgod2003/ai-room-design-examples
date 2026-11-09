# AI room design examples: the photo, the prompt, and the result

An AI room redesign is easier to evaluate when the original photo stays beside the output. This case study records four examples from AI Image to Image: a furnished living room, a restyled bedroom, a Scandinavian kitchen, and a warmer bathroom.

These are generated visual concepts, not photographs of completed renovations. This write-up was prepared with AI assistance from the saved generation records and images.

## The four comparisons

The images below show the full input and output frames. The inputs are wider than the square results; they have not been cropped to imply matching geometry.

### Living room: an empty space, furnished in Japandi style

| Input | AI-generated concept |
| --- | --- |
| ![Empty living-room example used as the input](https://ai-image-to-image.io/images/interior-empty.png) | ![AI-generated living room with a linen sofa, oak table, rug and paper lamp](https://ai-image-to-image.io/images/verified-living.png) |

The result introduces a linen sofa, an oval oak coffee table, a cream rug, and a paper floor lamp. It also adds a plant, shelving, and wall art. The black-framed window and the daylight direction remain recognizable. Both the source and result are example imagery, not a client renovation.

### Bedroom: change the finishes around an existing bed

| Input | AI-generated concept |
| --- | --- |
| ![AI-generated bedroom example photo used as the input](https://ai-image-to-image.io/images/bedroom-before.jpg) | ![AI-generated bedroom with oatmeal bedding and an oak headboard](https://ai-image-to-image.io/images/verified-bedroom.png) |

The edit changes the bedding, headboard, rug, and bedside lamp. The bed and window remain recognizable in their original arrangement. The source was created for the example; this is not a homeowner's before-and-after.

### Kitchen: sage cabinets instead of blue wallpaper

| Original photograph | AI-generated concept |
| --- | --- |
| ![Kitchen photographed by Lisa Anna, with white cabinets and blue walls](https://ai-image-to-image.io/images/kitchen-before.jpg) | ![AI-generated kitchen with sage cabinets, ivory walls and brass handles](https://ai-image-to-image.io/images/verified-kitchen.png) |

Sage cabinet fronts, brass handles, ivory walls, and a cream backsplash change the palette. The window, doorway, sink, stove, and cabinet arrangement remain recognizable. The model also changes the floor pattern and adds decorative objects, although the requested edit focused on other finishes.

Source photograph: [Lisa Anna / Pexels](https://www.pexels.com/photo/kitchen-interior-with-white-cupboards-and-a-garden-view-window-19878507/).

### Bathroom: a warmer material palette

| Original photograph | AI-generated concept |
| --- | --- |
| ![Bathroom photographed by Peter Vang, with a dark vanity and patterned curtain](https://ai-image-to-image.io/images/bathroom-before.jpg) | ![AI-generated bathroom with pale oak cabinetry, beige tile and a white curtain](https://ai-image-to-image.io/images/verified-bathroom.png) |

The dark vanity becomes pale oak; the countertop, flooring, curtain, and fittings change. The basin, mirror, bathtub, and doorway remain recognizable. The square output changes the crop and proportions, so the result should not be used to infer clearances or fixture dimensions.

Source photograph: [Peter Vang / Pexels](https://www.pexels.com/photo/minimalist-bathroom-with-shower-and-vanity-35430081/).

## Generation record

| Example | Model | Recorded date | Output | Route used |
| --- | --- | --- | --- | --- |
| Living room | GPT Image 2.6 Sunburst | 2026-11-06 | 1024 × 1024 | Website editor |
| Bedroom | GPT Image 2.6 Sunburst | 2026-11-06 | 1024 × 1024 | Website editor |
| Kitchen | GPT Image 2.6 Sunburst | 2026-11-09 | 1024 × 1024 | Website's Kie adapter, invoked directly |
| Bathroom | GPT Image 2.6 Sunburst | 2026-11-09 | 1024 × 1024 | Website's Kie adapter, invoked directly |

The last two examples use the same Advanced model mapping and 1K output options as the editor. They were not submitted as website tasks. The underlying records retain the source and output hashes as well as the exact prompts.

## The kitchen prompt

```text
Restyle this exact kitchen in warm Scandinavian style. Change the cabinet fronts to muted sage green with brushed brass handles, replace the blue wallpaper and floral border with warm ivory painted walls, and use pale oak countertops and a simple cream tile backsplash. Preserve the room architecture, cabinet layout, window, doorway, sink, stove, extractor hood, dining table position, camera angle and daylight direction. Photorealistic interior. No text or watermark.
```

The preservation instructions guide generation; they do not lock pixels or guarantee measurements. To compare another style, return to the original photograph and change the finish description. Editing the generated result repeatedly can make it harder to track which details came from the original.

## Try a source photo

Open [AI Image to Image](https://ai-image-to-image.io/?utm_source=github.com&utm_medium=referral&utm_campaign=room_design_before_after&utm_content=case_study), choose **AI room design**, and load an example with **Try this photo** or upload your own image. Changing a style keeps the original source in the editor. These examples use the Advanced model; the free Standard option uses a different model.
