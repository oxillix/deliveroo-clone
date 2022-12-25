##### I made this app as an educational introduction to developing modern hybrid apps fast with React-Native through a great tutorial from PapaReact. Amazing that he can build this in just 4 hours!
###### Tutorial link: 
[🔴 Let's build Deliveroo 2.0 with REACT NATIVE! (Navigation, Redux, Tailwind CSS & Sanity.io)](https://www.youtube.com/watch?v=taPz40VmyzQ)

### Demo:
![demo.gif](demo.gif)

### Live Demo (scan with expo app):
**(Only Burger King and Dunkin Donuts have dishes)**
![expo-go.svg](expo-go.svg)


### Technologies used:
Expo, Sanity, Redux, Navigation, Tailwind CSS (NativeWind), react-native-maps

### Installation:
1. create an account at https://www.sanity.io/sonny
2. git clone https://github.com/oxillix/deliveroo-clone.git
3. run sanity local server
```bash
cd sanity && npm run dev
```
4. Import sanity dataset
```bash
sanity dataset import sanity/production.tar.gz production
```
5. Install dependencies (from root folder)
```
  npx expo install
```
6. Run expo cli (from root folder)
```
npx expo start
```

### I learned, among other things:
- How to use RN expo for quickly starting and testing a cross-platform app
- How to use TailwindCSS for styling
- How to debug RN apps
- How to use react-native-maps
- The use of screens and components
- How to use RN navigation
- How to use the react-native-heroicons package to easily import icons
- How to use Sanity.io as a CMS
- The difference between useLayoutEffect(), useEffect() and useMemo()
- How to make GROQ queries (Sanity's query language)
- Handy Tailwind arbitrary value notation e.g. bg-[#00CCBB], instead of creating custom theme.colors
- Handy extensions: Auto Close Tag, Auto Import, Auto rename Tag, ES7 React/Redux/React-Native snippets, Import Cost, npm Intellisense, Prettier, SonarLint, vscode-styled-components, vscode-icons, TailwindCSS intellisense

### Improvements I made
- nativewind instead of tailwindcss-react-native
- Sanity v3 instead of v2
- RN SafeAreaView
- react-native-format-currency instead of react-currency-formatter (breaks with React 18)

### Issues I encountered, and how I fixed them 
- Images in components didn't show (no width&height set), turned out I forgot to include the screens & components folder in tailwind.config.js