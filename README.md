# prompt-library
A collection of prompts I revisit for various text-guided AI models.

--- 
## GPT-4
### System prompts:

**Make it write shorter denser code:**
```
You are an expert programmer, known for writing clean, concise code, and avoiding unnecessary abstraction. You always write in a code golf style, using as few lines of code as possible.
```

**Force GPT to be slightly more creative when writing verses:**
```
You are an innovative, creative, freeform rapper known for your storytelling, unconventional style, and mind-bendingly creative wordplay. You use lots of slang and references in your verses. Be creative, and break the mold! You always write long verses, with no choruses in between. Avoid standard rap tropes (like talking about your rhymes, saying "gather round and listen"), and focus on the given topic.
```

### User prompts:

**Midjourney prompt generator for random trippy aesthetics:**
```
please write a list of random words that could define a visual aesthetic. include relevant nouns/objects as well. Then, write them as a sentence in the format "word1::[random number between -1 and 1] word2::[random number]" etc. include "Abstract::1" at the beginning and "Portrait::-2" at the end. Do not generate underscores!
Here are some examples of types of words that would be good here: bright, psychedelic, watercolor, shattered, feathers, underwater, multicolored, gradient, vaporwave, clouds, god rays, foliage.
words to avoid: Kaleidoscopic, Ethereal, Luminous.
don't repeat the example words, instead create new ones with the same vibe.
```

**Midjourney prompt generator for compositional photos (like interior design):**
```
the following are key compositional elements for a landscape photograph:
scene, composition, camera angle, style, ecology, focal point, textures, color palette, lighting, location, time of day, mood, season.
Please come up with a list of compositional elements for other types of photos:
```
```
please create a table that breaks down a ______ photograph composition into the following key elements, where each of these key elements is a column: [paste previous output here]. fill the table with 10 rows of data. Then, write each row as a comma-separated sentence, and append --ar 16:9 to each one.
```

**Magic card generator:**
```
You are a magic card generator. You make cards as a JSON code block (surrounded by 3 backticks) with keys: name, type, cost, text, power, toughness, flavor, rarity. make sure your cards have mechanics relevant to the name, are fun to play, and have an appropriate rarity.
```

```
please make 5 burning man themed magic cards
```

**Prompt generator for midjourney food pics:**
```
Please describe appearance and ingredients of a delicious traditional {country, culture, or name of dish} dish. Don't write a recipe for it, or write about how it tastes. Don't use the name of the dish, just describe the dish in this format:  A tripadvisor's photograph of a half-eaten, messy [detailed description of your dish] in a [restaurant] in [location]. [more optional description of the dish]. The photograph is zoomed in to focus on the food and shot with a Canon EF - S 35mm f/ 2. 8 Macro IS STM camera [end with: --no camera --s 250 --v 5 , do not end with a period.]
```

**Generic midjourney prompt generator (requires browsing model):**
```
look up midjourney v5 prompts (https://aituts.com/midjourney-v5/). then, using what you learned, write a midjourney prompt for [quick description of your topic]
```

--- 

## Midjourney v5
```

```
