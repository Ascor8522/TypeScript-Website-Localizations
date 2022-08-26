## How to add a new language

Things you need before:

 - Someone to be responsible
 - Others to help out (and maybe also make responsible)

## **In this repo**

1. Create an issue "[Language] Localization summary". Copy the issue number.
1. Make a new label for the language
1. Go to `localize.json` and add your new language
1. Add the new owner to `CODEOWNERS`

Send a PR with those changes, here's an example with French: [PR #101](https://github.com/microsoft/TypeScript-Website-Localizations/pull/101).

## **In TypeScript-Website**

1. Ask for the following translations ASAP:

```
en: {
    shorthand: "In En",
    body: "This page is available in English",
    open: "Go",
    cancel: "Don't ask again",
  },
```
1. Add that to: https://github.com/microsoft/TypeScript-website/blob/v2/packages/typescriptlang-org/src/copy/inYourLanguage.ts#L1


## **In Discord**

1. Create a new room: `#localize-[shortcode]`
1. Add the tag "localizer" to folks interested
