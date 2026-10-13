# Painted people — AI model and prompts

Style: glossy hand-painted acrylic fashion illustration with a 1970s disco feel (like the painted crowd in Inspo/IMG_8890): long slim figures, small stylised faces, closed eyes with lilac eyeshadow, glossy red lips, big tinted sunglasses, thin dark-brown outlines, thick saturated paint with white highlight streaks, flat background.

## Model

**Qwen-Image 2.1 LoRAs PnP**
huggingface.co/spaces/prithivMLmods/Qwen-Image-2.1-LoRAs-PnP

Alternative if that one is busy: **Qwen-Image** — huggingface.co/spaces/mcp-tools/Qwen-Image

How to use it:
- Sign in to Hugging Face first (more free generation time).
- Set Width and Height under Advanced Settings before pressing Run. A page refresh resets them to square.
- Make 4–6 of each and keep the best; this style varies a lot.

## Prompts

### 1. The crowd — bottom of event posters (1024 × 768)
```
Hand-painted acrylic fashion illustration in a glamorous 1970s disco style, five stylish friends at a cocktail bar against a flat solid black background, cropped at the hips. Two men in open-collar satin shirts in cobalt blue and violet with feathered hair and orange-tinted aviator sunglasses, a woman in a gold sequin mini dress in the centre laughing with eyes closed, lilac eyeshadow and glossy red lips, all raising martini glasses and champagne coupes. Elongated figures, long necks, small stylised faces, thin dark brown painted outlines, thick saturated paint with bright white highlight streaks on satin, sequins and hair, visible brush strokes, vivid cobalt, violet, gold and red, naive glossy painted look, not photorealistic, not 3D, not vector
```

### 2. Two at the bar (1024 × 1280)
```
Hand-painted acrylic fashion illustration in a glamorous 1970s disco style, a tall slender couple leaning on a brass bar against a flat deep bottle-green background, cropped at the knees. A man in a rust-orange three-piece suit with wide lapels, slicked dark hair and orange-tinted aviator sunglasses holding an old fashioned. A woman with a sharp black bob in a red satin slip dress, oversized red-lens sunglasses and gold hoop earrings holding a martini, one hand on her hip. Elongated figures, long necks, small stylised faces, glossy red lips, thin dark brown painted outlines, thick saturated paint with bright white highlight streaks on satin and hair, soft painted wisps of smoke behind, visible brush strokes, naive glossy painted look, not photorealistic, not 3D, not vector
```

### 3. The bubbly lady — stories (768 × 1344)
```
Hand-painted acrylic fashion illustration in a glamorous 1970s disco style, an elegant woman laughing with her head tilted back and eyes closed, lilac eyeshadow, glossy red lips, huge voluminous dark curls, big gold statement earrings, emerald velvet blazer over a violet satin top, holding up a champagne coupe, against a flat solid black background, cropped at the waist. Elongated figure, long slender neck, small stylised face, thin dark brown painted outlines, thick saturated paint with bright white highlight streaks on velvet, satin and hair, visible brush strokes, vivid emerald, violet and gold, naive glossy painted look, not photorealistic, not 3D, not vector
```

### 4. The bartender (1024 × 1280)
```
Hand-painted acrylic fashion illustration in a glamorous 1970s disco style, a charismatic slender bartender with slicked-back hair and a thick curled moustache, crisp white shirt with rolled sleeves and a black waistcoat, stirring a cocktail in a crystal mixing glass with a long gold spoon, a row of glowing cobalt and amber bottles painted loosely behind him, against a flat solid black background, cropped at the waist. Elongated figure, small stylised face, eyes half closed, thin dark brown painted outlines, thick saturated paint with bright white highlight streaks on the glass, waistcoat and hair, visible brush strokes, vivid cobalt, red and gold, naive glossy painted look, not photorealistic, not 3D, not vector
```

## Tips
- All four end with the same style text (from "Elongated…"), so the set looks like one artist. Keep that ending on any new prompt.
- Too clean or digital? Add: "painted on paper with acrylic markers, slightly uneven, hand-made".
- One person instead of a group: keep the ending, describe the single person at the start.
- No cigarettes in hands (Instagram tobacco rules); painted smoke haze in the background is fine.
- Don't upload the Inspo artwork as a style reference — it's another venue's commissioned art. Describing the style, as above, gives you original characters.
- Drop finished images in mist_socialmedia/Generated and ask Claude to place them on the canvas.
