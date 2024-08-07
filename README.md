# notes


### svg useage
```
import Svg, { G, Path, Defs, ClipPath, Rect } from "react-native-svg"
<Svg
  width={20}
  height={20}
  viewBox="0 0 28 26"
  fill="none"
>
  <G clip-path="url(#clip0_3282_46737)">
  <Path d="M13.9589 23.25L4.71889 14.01C-3.05111 6.23998 6.18889 -3.00002 13.9589 4.76998C21.8689 -3.14001 31.1089 6.09999 23.1989 14.01L13.9589 23.25Z" stroke="#3AAFF1" stroke-width="2" stroke-miterlimit="10"></Path>
  </G>
  <Defs>
  <ClipPath id="clip0_3282_46737">
  <Rect width="28" height="25" fill="white" transform="translate(0 0.5)"></Rect>
  </ClipPath>
  </Defs>
</Svg>
```


### Прочекать
Linking (Deep Links)


### Mokky Dev
https://mokky.dev/dashboard/


### Колонки FlatList'a
https://stackoverflow.com/questions/50835303/2-column-layout-with-flexbox-on-react-native
```<FlatList numColumns={2}/>```


### Использование FlatList'а внутри ScrollView
https://stackoverflow.com/questions/67623952/error-virtualizedlists-should-never-be-nested-inside-plain-scrollviews-with-th


### Gap between cards in FlatList
https://stackoverflow.com/questions/73338922/how-do-i-add-gap-in-between-items-in-flatlist


### InfiniteScroll in FlatList
https://truesparrow.com/blog/infinite-scrolling-in-react-native/


### Русская дока react-native-navigation + reanimated + кастомный TabBottom
https://reactnativedev.ru/community/react-navigation.6/bottom-tab-navigator/#title


### Туториал reanimated
https://www.reactiive.io/animate-with-reanimated
https://medium.com/react-native-rocket/animating-scrollviews-with-react-native-reanimated-2-f38372681b2c


### React Native Stories like in Instagram
https://github.com/birdwingo/react-native-instagram-stories


### Долистали до конца ScrollView 
https://stackoverflow.com/questions/41056761/detect-scrollview-has-reached-the-end


### Refresh Control в ScrollView
https://stackoverflow.com/questions/56033315/how-to-do-refresh-in-react-native-scrollview-with-refreshcontrol


### Альтернатива FlatList
https://github.com/Shopify/flash-list


### Верстка списка Pinterest
https://www.npmjs.com/package/react-native-masonry-list


### Yoga Layout 
https://yogalayout.dev/docs/


### Swiper в React Native
https://www.npmjs.com/package/react-native-swiper


### Модалки выезжающие снизу экрана
https://github.com/gorhom/react-native-bottom-sheet
https://www.youtube.com/watch?v=lYYiuXcTnnE


### Учебник PWA
https://pwadev.ru/learn/30days-pwa/


### Шпаргалка по MarkDown
https://gist.github.com/fomvasss/8dd8cd7f88c67a4e3727f9d39224a84c

```yarn create-expo-app -e with-router-tailwind // [not-working]```


### base packages:
```
yarn add expo-constants expo-linking expo-router expo-splash-screen nativewind react-native-reanimated react-native-safe-area-context react-native-screens
yarn add --dev tailwindcss
```


### color scheme:
```
"userInterfaceStyle": "automatic",
yarn add expo-system-ui
yarn expo config --type introspect
```


### lottie react 
https://github.com/Gamote/lottie-react/
https://lottiereact.com/components/Lottie#getting-started 


### react imask
https://github.com/uNmAnNeR/imaskjs/tree/master/packages/react-imask 


### пакет иконок Expo
https://icons.expo.fyi/Index


### Кастомный цвет для status-bar ios
https://stackoverflow.com/questions/39297291/how-to-set-ios-status-bar-background-color-in-react-native


### Moti Animations
https://moti.fyi/


### Что-то прикольное про layout'ы 
https://react-native-flex-layout.js.org/


### Theme Provide | Чтобы отслеживать динамическое изменение темы, но по своей кнопке =/
https://blog.logrocket.com/building-react-native-theme-switcher-app/


### Framer Motion | Что-то типо Moti + Gsap но для классического реакта
https://www.framer.com/motion/examples/


### Bottom Sheet Modal, but for classic React
https://react-spring.bottom-sheet.dev

https://github.com/emilkowalski/vaul?tab=readme-ov-file

https://www.npmjs.com/package/react-modal-sheet

### React use
https://github.com/streamich/react-use

### React when element sticky
https://github.com/equinusocio/react-sticky-spy?tab=readme-ov-file

### Paramore fandom
https://paramore.fandom.com/wiki/Brick_By_Boring_Brick
