<h1>SMARTFREN TV</>

## **INTRODUCTION**
Application is a catalog listing for movies & TV shows provide by [Smartfren TV](https://www.smartfren.com/), in this application there is some
features like ***Movie now playing***, ***Top rated movie***, ***Tv airing today*** and many other.
Fetching data in this application is using opensource free api [TMDB](https://developers.themoviedb.org/3/getting-started/introduction) 
to show some movie data and tv shows like poster and banner.


### **Getting Started**
You can modifie or edit component in this repository with your owns style,<br/> or learn more about this application by fork and develop </br>
<strong>Clone the repository with this command :</strong>
tarted**
</br>
</br>

#### Clone

```shell
git clone https://devops-imun-admin@bitbucket.org/devops-imun/smartfrentv.git
```
</br>
</br>

#### Install

```shell
npm install or yarn add
```
</br>
</br>

#### Run

```shell
npx react-native run-android
```
</br>
</br>


#### Testing

```shell
npm test or yarn test
``` 

</br>
</br>

### **Requirement**
Requirement include: 

- Android 5.1 (Lollipop) or higher
- Screen size of 7 inches or less
- React native (0.63 or higher)
</br>
</br>

### **Changelog**

This application is first version **0.0.1** and still in development mode, please fork or create issue if any request on the application for further.
</br>
</br>

### **Features**
This application have some features and components can use by user
- Show Movie
- Show TV
- Show Popular People
</br>
</br>

## **DEVELOP**

### **Library**
This application is build with alot of library and some library is required to install by 
some other library, in the example is **react-navigation**. This library must install a lot of other library,
so I've list to make sure the library is works and easy to develop by other developer.

| Library                                                           | Usability                 |   Star    |
| :-----------------------------------------------------------------|:--------------------------|:---------:|
| [@apollo/client](https://pub.dev/packages/dartz)                           | Data Handling             | [![Github Stars](https://img.shields.io/github/stars/spebbe/dartz?style=flat&logo=github&colorB=blue&label=stars)](https://github.com/spebbe/dartz) |
| [@react-native-community/masked-view](https://pub.dev/packages/dio)                               | Http client               | [![Github Stars](https://img.shields.io/github/stars/flutterchina/dio?style=flat&logo=github&colorB=blue&label=stars)](https://github.com/felangel/bloc)    |
| [@react-navigation/bottom-tabs](https://pub.dev/packages/equatable)                   | Getting data abstract     | [![Github Stars](https://img.shields.io/github/stars/felangel/equatable?style=flat&logo=github&colorB=blue&label=stars)](https://github.com/felangel/equatable)    |
| [@react-navigation/drawer](https://pub.dev/packages/flutter_bloc)               | State management          | [![Github Stars](https://img.shields.io/github/stars/felangel/bloc.svg?style=flat&logo=github&colorB=blue&label=stars)](https://github.com/felangel/bloc)      |
| [@react-navigation/material-top-tabs](https://pub.dev/packages/get_it)                         | Component Injector        | [![Github Stars](https://img.shields.io/github/stars/fluttercommunity/get_it?style=flat&logo=github&colorB=blue&label=stars)](https://github.com/fluttercommunity/get_it)     |
| [@react-navigation/native](https://pub.dev/packages/get)                              | Component handling        | [![Github Stars](https://img.shields.io/github/stars/jonataslaw/getx?style=flat&logo=github&colorB=blue&label=stars)](https://github.com/jonataslaw/getx)       |
| [@react-navigation/stack](https://pub.dev/packages/pedantic)                     | Code formatting           | [![Github Stars](https://img.shields.io/github/stars/google/pedantic?style=flat&logo=github&colorB=blue&label=stars)](https://github.com/google/pedantic)     |
| [graphql](https://pub.dev/packages/rxdart)                         | Data handling async       | [![Github Stars](https://img.shields.io/github/stars/reactiveX/rxdart?style=flat&logo=github&colorB=blue&label=stars)](https://github.com/ReactiveX/rxdart)     |
| [moment](https://pub.dev/packages/logger)                         | Beautiful terminal log    | [![Github Stars](https://img.shields.io/github/stars/google/pedantic?style=flat&logo=github&colorB=blue&label=stars)](https://github.com/google/pedantic)     |
| [react-native-elements](https://pub.dev/packages/shared_preferences) | Save data local storage   | [![Github Stars](https://img.shields.io/github/stars/flutter/plugins?style=flat&logo=github&colorB=blue&label=stars)](https://github.com/flutter/plugins)     |
| [react-native-gesture-handler](https://pub.dev/packages/shared_preferences) | Save data local storage   | [![Github Stars](https://img.shields.io/github/stars/flutter/plugins?style=flat&logo=github&colorB=blue&label=stars)](https://github.com/flutter/plugins)     |
| [react-native-paper](https://pub.dev/packages/shared_preferences) | Save data local storage   | [![Github Stars](https://img.shields.io/github/stars/flutter/plugins?style=flat&logo=github&colorB=blue&label=stars)](https://github.com/flutter/plugins)     |
| [react-native-reanimated](https://pub.dev/packages/shared_preferences) | Save data local storage   | [![Github Stars](https://img.shields.io/github/stars/flutter/plugins?style=flat&logo=github&colorB=blue&label=stars)](https://github.com/flutter/plugins)     |
| [react-native-safe-area-context](https://pub.dev/packages/shared_preferences) | Save data local storage   | [![Github Stars](https://img.shields.io/github/stars/flutter/plugins?style=flat&logo=github&colorB=blue&label=stars)](https://github.com/flutter/plugins)     |
| [react-native-screens](https://pub.dev/packages/shared_preferences) | Save data local storage   | [![Github Stars](https://img.shields.io/github/stars/flutter/plugins?style=flat&logo=github&colorB=blue&label=stars)](https://github.com/flutter/plugins)     |
| [react-native-skeleton-placeholder](https://pub.dev/packages/shared_preferences) | Save data local storage   | [![Github Stars](https://img.shields.io/github/stars/flutter/plugins?style=flat&logo=github&colorB=blue&label=stars)](https://github.com/flutter/plugins)     |
| [react-native-splash-screen](https://pub.dev/packages/shared_preferences) | Save data local storage   | [![Github Stars](https://img.shields.io/github/stars/flutter/plugins?style=flat&logo=github&colorB=blue&label=stars)](https://github.com/flutter/plugins)     |
| [react-native-tab-view](https://pub.dev/packages/shared_preferences) | Save data local storage   | [![Github Stars](https://img.shields.io/github/stars/flutter/plugins?style=flat&logo=github&colorB=blue&label=stars)](https://github.com/flutter/plugins)     |
| [react-native-vector-icons](https://pub.dev/packages/shared_preferences) | Save data local storage   | [![Github Stars](https://img.shields.io/github/stars/flutter/plugins?style=flat&logo=github&colorB=blue&label=stars)](https://github.com/flutter/plugins)     |
<br/>
<br/>

### **Languages**
I developed this application using the Javascript and Typscript programming languages,but for native Android using Java
- **[Javascript](https://www.javascript.com/)**
- **[Typescript](https://www.typescriptlang.org/)**
- **[Java](https://www.java.com/en/)**
- **[Android](https://developer.android.com/)**
</br> 
</br> 

### **Testing**

I develop unit testing for this application is using **[Jest](https://jestjs.io/)** 
and Javascript language. In below I've make example code of unit testing and explain about it.
**Testing graphql now playing movie**
>movie-now-playing.test.js
```js
export const GET_NOW_PLAYING_MOVIE = gql`
  query nowPlayingMovie {
    movies: nowPlaying {
      id
      name
      overview
      releaseDate
      score
      tagline
      runtime
      genres {
        name
      }
      backdrop {
        medium
      }
      poster {
        medium
      }
      reviews {
        id
        author
        content
      }
    }
  }
`;

const mocks = [
  {
    request: {
      query: GET_NOW_PLAYING_MOVIE,
    },
    result: {
      data: {
        movie: [{ id: '1', name: 'name', overview: 'overview' }],
      },
    },
  },
];

///test must be load data movie now playing
it('Get now playing movie', async () => {
  const component = TestRenderer.create(
    <MockedProvider mocks={mocks} addTypename={false}>
      <Text>OK</Text>
    </MockedProvider>,
  );
  await 0;

  const tree = component.toJSON();
  expect(tree.children).toMatchSnapshot();
});

```


## **OVERVIEW**

### **Movie**

### **TV Shows**