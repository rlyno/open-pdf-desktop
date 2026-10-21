# Third-party notices

Open PDF is closed source, but it is built on these open-source projects. Each one stays under its
own license; copies of the license texts ship inside the installers (in each package's folder).

## Both apps

| Project | License | Use |
| --- | --- | --- |
| [pdf-lib (@cantoo/pdf-lib)](https://github.com/cantoo-scribe/pdf-lib) | MIT | Reading and writing PDFs |
| [@noble/ciphers](https://github.com/paulmillr/noble-ciphers), [@noble/hashes](https://github.com/paulmillr/noble-hashes) | MIT | AES-256 encryption for passwords |
| [fflate](https://github.com/101arrowz/fflate) | MIT | ZIP files |
| [React](https://react.dev) | MIT | User interface |
| [Inter](https://rsms.me/inter/) | SIL Open Font License 1.1 | Typeface |

## Open PDF (Android/iOS)

| Project | License |
| --- | --- |
| [Expo](https://expo.dev) and Expo modules | MIT |
| [React Native](https://reactnative.dev) | MIT |
| react-native-gesture-handler, react-native-reanimated, react-native-screens, react-native-svg, react-native-safe-area-context | MIT |
| [react-native-pdf-thumbnail](https://github.com/songsterq/react-native-pdf-thumbnail) | MIT |

## Open PDF Desktop

| Project | License |
| --- | --- |
| [Tauri](https://tauri.app) and its plugins | MIT or Apache-2.0 |
| [pdf.js (pdfjs-dist)](https://mozilla.github.io/pdf.js/) | Apache-2.0 |
| [Lucide](https://lucide.dev) | ISC |
| [Vite](https://vite.dev) | MIT |

The full list of dependencies and their exact versions is in each app's `package-lock.json` and
`Cargo.lock`.
