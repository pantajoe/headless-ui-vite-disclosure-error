# Vite 3 - Headless UI (React is not defined)

## Steps to Reproduce

0. If you have [`asdf`](https://asdf-vm.com), then run `asdf install`
1. `yarn install`
2. `yarn build`
3. `yarn serve` to show the preview

The page should be blank (while `yarn dev` works fine)
and the console should show the error `React is not defined`

An issue was already opened in the repository of [headlessUI](https://github.com/tailwindlabs/headlessui/issues/1693).
But with Vite < 3, there was no issue, so this is no actual bug with HeadlessUI. 
