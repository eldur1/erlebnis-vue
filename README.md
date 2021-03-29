# erlebnis

## Web project of generative website
An attempt to create a generative website.

## Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).

## Syntax & naming convention
- Functions written in camelCase.
- `n` in a function/ variable mean number 
- `r` as beginning of function/ variable mean random.
- `a` in a function/ variable mean array.
- `o` in a function/ variable mean object.
- No use of ; at end of line.

## MVP 

It produce non predictable result.
The most important for the MVP is not to get the best algorithm but have an algorithm that work. 
We cannot jump this part. We need to see results that doesn't work to improve the algorithm. 
Here's a list of functionnality that the algorithm have in the MVP

### Generation tools :
- ✅ randomNumber()
- ✅ trueOrFalse()

### Color generation : 
- ✅ Five types of pallet 
- ✅ Background

### Font generation :
- ✅ Fon family (array of font)
- ✅ Lineheight
- ✅ Font size
- ✅ Random ratio 

### Layout generation : 
- ✅ Margin (body)
- ✅ Margin (elements)

## To do 
- ✅ Move to VueJS
- Animation on content generation

## Beta 

Beta include a improved version of the algorithm. 

- keyword system ( one keyword by category)
- readability font check

(?) : Not sure about that

### Generation : 
- Seed 
- Randomness cursor

### Font generation :
- Google Fonts
- Number of fonts
- Color font (readability check)

### Layout generation : 
- Grid generation
- Accorded spacing (same scale on every spacing) 


## Some stuff 
Webfontload package to simply load fonts from google fonts
https://www.npmjs.com/package/webfontloader

## Credit(s)

Done by myself 
