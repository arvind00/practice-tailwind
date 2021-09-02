## Learning Objective
- [x] Learn how to integrate tailwindcss in an angular project

## Step 01 - Add it using schematics

```sh
ng add @ngneat/tailwind
ℹ Using package manager: npm
✔ Found compatible package version: @ngneat/tailwind@7.0.3.
✔ Package information loaded.

The package @ngneat/tailwind@7.0.3 will be installed and executed.
Would you like to proceed? Yes
✔ Package successfully installed.
"NgAdd" schema is using the keyword "id" which its support is deprecated. Use "$id" for schema ID.
? Would you like to enable Tailwind JIT (preview feature)? Yes
? Would you like to enable dark mode? class
? What @tailwindcss plugins do you want to enable? aspect-ratio, forms, line-clamp, typography
    ✅️ Added tailwindcss@2.2.9
    ✅️ Added @tailwindcss/typography@0.4.1
    ✅️ Added @tailwindcss/line-clamp@0.2.1
    ✅️ Added @tailwindcss/aspect-ratio@0.2.1
    ✅️ Added @tailwindcss/forms@0.3.3
    ✅️ Installed dependencies
CREATE tailwind.config.js (570 bytes)
UPDATE package.json (1298 bytes)
UPDATE src/styles.scss (175 bytes)
UPDATE src/index.html (315 bytes)
✔ Packages installed successfully.
```

## Important Notes
- To get tailwind css intellisence install the extension Tailwind CSS Intellisence by Brad Cornes
- If you use material components don't use tailwindcss classes to it as it gets overridden by material's styles. 
- You can use it in non-material elements and layouts

## Reference
- [why tailwindcss](https://adamwathan.me/css-utility-classes-and-separation-of-concerns/)
- [integrate tailwind css with angular](https://levelup.gitconnected.com/my-experience-with-tailwind-css-and-angular-b5f40eeda838)
- [Official Tailwindcss site](https://tailwindcss.com)