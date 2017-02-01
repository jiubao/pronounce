# Phonetic Transcription Lessons

- [Lesson one 基础音标](#lesson-one)
- [LESSON TWO](#lesson-two)
- [Documentation](#documentation)
- [Examples](#examples)
- [Extending React Native](#extending-react-native)
- [Upgrading](#upgrading)
- [Opening Issues](#opening-issues)
- [Contributing](#contributing)
- [LESSON THREE - 重点问题纠正](#LESSON-THREE---重点问题纠正)

## LESSON ONE

### 英语音标表

| 元音 |||||||||
| ----- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| 长元音 | ɑ: | ɔ: | ɜ: | i: | u: ||||
| 短元音 | ʌ | ɒ | ə | ɪ | ʊ | e | æ ||
| 双元音 | eɪ | aɪ | ɔɪ | ɪə | eə | ʊə | əʊ | aʊ |

| 辅音 |||||||
| ----- | :-: | :-: | :-: | :-: | :-: | :-: |
| 轻辅音 | p | t | k | f | θ | s |
| 浊辅音 | b | d | g | v | ð | z |
| 轻辅音 | ʃ | h | ʦ | ʧ | tr ||
| 浊辅音 | ʒ | r | ʣ | ʤ | dr ||
| 鼻音 | m | n | ŋ ||||
| 半元音 | j | w |||||
| 边音 | l |||||||

课后跟读练习：

- 闹钟：alarm   /ə'lɑ:m/ 
- 美国：America   /ə'merikə / 
- 阿凡达：Avatar   /'ævətɑ:/  
- 博客：blog   /blɔg / 
- 英国：Britain  /'britn / 
- 首都：capital   / 'kæpitəl/ 
- 城市：city   / 'siti / 
- 家庭：family   / 'fæməli/ 
- 鱼：fish  /fiʃ/ 
- 朋友：friend   /frend/ 
- 手：hand   /hænd/ 
- 冰淇林：ice cream   / 'aiskri:m/ 
- 钥匙：key   /ki:/ 
- 孩子：kid   /kid/ 
- 信件：letter   /'letə/ 
- 男人：man   /mæn/ 
- 钢笔：pen   /pen/ 
- 警察：police  /pə'li:s/ 
- 绵羊：sheep  /ʃi:p/ 
- 轮船：ship  /ʃip/ 
- 10：ten   / ten / 

## LESSON TWO

关于如何运气，如何做发音之前的准备。

发音之前，把舌头和嘴巴放在相应位置，吸气，然后将气挤压出去，发出音。注意需让每个单词都包含一个长元音。

| 分类 | 舌唇准备 | 单词举例 |
| -- | -- | -- |
| AEIOU | 开口60% | [Answer] ending in often [under] |
| BMP | 双唇轻轻合拢 | Best mention patient |
| CKG | 开口20% 喉音 | Can kick gone |
| DJNT | 舌头抬起45度 | Duck [justice] nice time |
| FV | 上齿轻咬下唇 | Fast fancy very visit |
| H | 开口40% | Hate handsome hired have |
| L | 舌头抬起30度，抵住牙齿 | Leave last love |
| RSY | 开口10%（几乎不开口） | Ran sent yes |
| W | 开口呈亲吻式O型 | Want why word went |
| TH | 舌头抵住上齿底部（不需要太多伸出） | ① this those [these] them that ② thank thought [throw] |

## Getting Help

Please use these community resources for getting help. We use the GitHub issues for tracking bugs and feature requests and have limited bandwidth to address them.

- Ask a question on [StackOverflow](https://stackoverflow.com/) and tag it with `react-native`
- Chat with us on [Reactiflux](https://discord.gg/0ZcbPKXt5bWJVmUY) in #react-native
- Articulate your feature request or upvote existing ones on [Product Pains](https://productpains.com/product/react-native/)
- Start a thread on the [React Discussion Board](https://discuss.reactjs.org/)
- Join #reactnative on IRC: chat.freenode.net
- If it turns out that you may have found a bug, please [open an issue](#opening-issues)

## Documentation

[The website’s documentation](https://facebook.github.io/react-native/docs/) is divided into multiple sections.
- There are **Guides** that discuss topics like [debugging](https://facebook.github.io/react-native/docs/debugging.html), [integrating with existing apps](https://facebook.github.io/react-native/docs/integration-with-existing-apps.html), and [the gesture responder system](https://facebook.github.io/react-native/docs/gesture-responder-system.html).
- The **Components** section covers React components such as [`View`](https://facebook.github.io/react-native/docs/view.html) and [`Navigator`](https://facebook.github.io/react-native/docs/navigator.html).
- The **APIs** section covers other libraries like [Animated](https://facebook.github.io/react-native/docs/animated.html) and [StyleSheet](https://facebook.github.io/react-native/docs/stylesheet.html) that aren’t React components themselves.
- Finally, React Native provides a small number of **Polyfills** that offer web-like APIs.

Another great way to learn more about the components and APIs included with React Native is to read their source. Look under the `Libraries` directory for components like `ScrollView` and `Navigator`, for example. The UIExplorer example is also here to demonstrate some of the ways to use these components. From the source you can get an accurate understanding of each component’s behavior and API.

The React Native documentation only discusses the components, APIs and topics specific to React Native (React on iOS and Android). For further documentation on the React API that is shared between React Native and React DOM, refer to the [React documentation](https://facebook.github.io/react/).

## Examples

- `git clone https://github.com/facebook/react-native.git`
- `cd react-native && npm install`

### Running the examples on iOS

Now open any example (the `.xcodeproj` file in each of the `Examples` subdirectories) and hit Run in Xcode.

### Running the examples on Android

Note that you'll need the Android NDK installed, see [prerequisites](https://github.com/facebook/react-native/blob/master/ReactAndroid/README.md#prerequisites).

```bash
./gradlew :Examples:Movies:android:app:installDebug
# Start the packager in a separate shell (make sure you ran npm install):
./packager/packager.sh
# Open the Movies app in your emulator
```

## Extending React Native

- Looking for a component? [JS.coach](https://js.coach/react-native)
- Fellow developers write and publish React Native modules to npm and open source them on GitHub.
- Making modules helps grow the React Native ecosystem and community. We recommend writing modules for your use cases and sharing them on npm.
- Read the guides on Native Modules ([iOS](https://facebook.github.io/react-native/docs/native-modules-ios.html), [Android](https://facebook.github.io/react-native/docs/native-modules-android.html)) and Native UI Components ([iOS](https://facebook.github.io/react-native/docs/native-components-ios.html), [Android](https://facebook.github.io/react-native/docs/native-components-android.html)) if you are interested in extending native functionality.

## Upgrading

React Native is under active development. See the guide on [upgrading React Native](https://facebook.github.io/react-native/docs/upgrading.html) to keep your project up-to-date.

## Opening Issues

If you encounter a bug with React Native we would like to hear about it. Search the [existing issues](https://github.com/facebook/react-native/issues) and try to make sure your problem doesn’t already exist before opening a new issue. It’s helpful if you include the version of React Native and OS you’re using. Please include a stack trace and reduced repro case when appropriate, too.

The GitHub issues are intended for bug reports and feature requests. For help and questions with using React Native please make use of the resources listed in the [Getting Help](#getting-help) section. [Product Pains](https://productpains.com/product/react-native/) in particular is a good way to signal your interest in a feature or issue. There are limited resources available for handling issues and by keeping the list of open issues lean we can respond in a timely manner.

## Contributing

For more information about contributing PRs and issues, see our [Contribution Guidelines](https://github.com/facebook/react-native/blob/master/CONTRIBUTING.md).

[Good First Task](https://github.com/facebook/react-native/labels/Good%20First%20Task) is a great starting point for PRs.

We encourage the community to ask and answer questions on Stack Overflow with [the react-native tag](https://stackoverflow.com/questions/tagged/react-native). It's a great way to help out and be involved!

## LESSON THREE - 重点问题纠正

React is [BSD licensed](./LICENSE). We also provide an additional [patent grant](./PATENTS).

React documentation is [Creative Commons licensed](./LICENSE-docs).

Examples provided in this repository and in the documentation are [separately licensed](./LICENSE-examples), as are some of the [custom components](./LICENSE-CustomComponents).
