<h1>SMARTFREN TV</h1>


## **INTRODUCTION**
Application is a catalog listing for movies & TV shows develop by [Imam Abdul Azis](https://github.com/imamabdulazis) to finish **Mobile Testing** **[Smartfren](https://www.smartfren.com)** Company, in this application there is some
features like ***Movie now playing***, ***Top rated movie***, ***Tv airing today*** and many other.
Fetching data in this application is using opensource free api [TMDB](https://developers.themoviedb.org/3/getting-started/introduction) 
to show some movie data and tv shows like poster and banner.


### **Getting Started**
You can modifie or edit component in this repository with your owns style,<br/> or learn more about this application by fork and develop </br>
</br>
</br>

### **GraphQL**
Using graphql playground to test the API is work or not and also create shema to get response data from server. </br>
 ***Please using this link*** : **[GRAPHQL PLAYGROUND](https://tmdb-api.saeris.io/.netlify/functions/tmdb-api)**

![Screen Shot 2021-07-02 at 2 25 14 PM](https://user-images.githubusercontent.com/39134128/124237092-5deb7000-db41-11eb-803e-f5766d286d77.png)

</br>
</br>

### **Clone**

```shell
git clone https://devops-imun-admin@bitbucket.org/devops-imun/smartfrentv.git
```
</br>
</br>

### **Install**

```shell
npm install or yarn add
```
</br>
</br>

### **Run**

```shell
npx react-native run-android
```
</br>
</br>

### **Connection**

```js
export const link = createHttpLink({
  uri: config.baseUrl,
});

const client = new ApolloClient({
  cache: new InMemoryCache(),
  link,
  onError: ({ networkError, graphQLErrors }) => {
    console.log('graphQLErrors', graphQLErrors);
    console.log('networkError', networkError);
  },
});

const App: () => Node = () => {
  return (
    <ApolloProvider client={client}>
      <RouteNavigator />
    </ApolloProvider>
  );
};

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
| [@apollo/client](https://github.com/apollographql/apollo-client)                                                         | Data Handling             | ![Github Stars](https://img.shields.io/github/stars/apollographql/apollo-client?style=flat&logo=github&colorB=blue&label=stars) |
| [@react-native-masked-view/masked-view](https://github.com/react-native-masked-view/masked-view)                         | Required React Navigation               | ![Github Stars](https://img.shields.io/github/stars/react-native-masked-view/masked-view?style=flat&logo=github&colorB=blue&label=stars)   |
| [@react-navigation](https://github.com/react-navigation/react-navigation/tree/4.x)                                       | Navigation                | ![Github Stars](https://img.shields.io/github/stars/react-navigation/react-navigation?style=flat&logo=github&colorB=blue&label=stars)   |
| [graphql](https://github.com/graphql/graphql-js)                                                                               | Data handling Graphql     | ![Github Stars](https://img.shields.io/github/stars/graphql/graphql-js?style=flat&logo=github&colorB=blue&label=stars)     |
| [moment](https://github.com/moment/moment)                                                                                | Date format               | ![Github Stars](https://img.shields.io/github/stars/moment/moment?style=flat&logo=github&colorB=blue&label=stars)    |
| [react-native-elements](https://github.com/react-native-elements/react-native-elements)                                                     | Library  Compinent UI     | ![Github Stars](https://img.shields.io/github/stars/react-native-elements/react-native-elements?style=flat&logo=github&colorB=blue&label=stars)  |
| [react-native-gesture-handler](https://github.com/software-mansion/react-native-gesture-handler)                                              | Save data local storage   | ![Github Stars](https://img.shields.io/github/stars/software-mansion/react-native-gesture-handler?style=flat&logo=github&colorB=blue&label=stars)    |
| [react-native-paper](https://github.com/callstack/react-native-paper)                                                        | Library  Compinent UI     | ![Github Stars](https://img.shields.io/github/stars/callstack/react-native-paper?style=flat&logo=github&colorB=blue&label=stars)    |
| [react-native-reanimated](https://github.com/software-mansion/react-native-reanimated)                                                   | Build Beautiful Animation | ![Github Stars](https://img.shields.io/github/stars/software-mansion/react-native-reanimated?style=flat&logo=github&colorB=blue&label=stars)    |
| [react-native-safe-area-context](https://github.com/th3rdwave/react-native-safe-area-context)                                            | Manage SafeAreaScreen     | ![Github Stars](https://img.shields.io/github/stars/th3rdwave/react-native-safe-area-context?style=flat&logo=github&colorB=blue&label=stars)    |
| [react-native-screens](https://github.com/software-mansion/react-native-screens)                                                      | Required React Navigation | ![Github Stars](https://img.shields.io/github/stars/software-mansion/react-native-screens?style=flat&logo=github&colorB=blue&label=stars)    |
| [react-native-skeleton-placeholder](https://github.com/chramos/react-native-skeleton-placeholder)                                         | Skeleton Placeholder      | ![Github Stars](https://img.shields.io/github/stars/chramos/react-native-skeleton-placeholder?style=flat&logo=github&colorB=blue&label=stars)    |
| [react-native-splash-screen](https://github.com/crazycodeboy/react-native-splash-screen)                                                | Build Splash Screen Customization    | ![Github Stars](https://img.shields.io/github/stars/crazycodeboy/react-native-splash-screen?style=flat&logo=github&colorB=blue&label=stars)     |
| [react-native-tab-view](https://github.com/satya164/react-native-tab-view)                                                     |  Required React Navigation  | ![Github Stars](https://img.shields.io/github/stars/satya164/react-native-tab-view?style=flat&logo=github&colorB=blue&label=stars)     |
| [react-native-vector-icons](https://github.com/oblador/react-native-vector-icons)                                                 | React Native Icons   |![Github Stars](https://img.shields.io/github/stars/oblador/react-native-vector-icons?style=flat&logo=github&colorB=blue&label=stars)     |
| [react-native-linear-gradient](https://github.com/react-native-linear-gradient/react-native-linear-gradient)                                       |  Build Linear Gradient UI   | ![Github Stars](https://img.shields.io/github/stars/react-native-linear-gradient/react-native-linear-gradient?style=flat&logo=github&colorB=blue&label=stars)     |

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

**RUN**
```shell
npm test or yarn test
```

</br>
</br>

**Example Overview**

![Screen Shot 2021-07-02 at 2 32 12 PM](https://user-images.githubusercontent.com/39134128/124238040-62645880-db42-11eb-9731-779ee7f11e89.png)


</br>
</br>

## **OVERVIEW**

End the we can see sample screenshot running project with android like below.

</br>

<h3>TV Shows</h3>

<p float="left">
<img src="https://user-images.githubusercontent.com/39134128/124235114-1368f400-db3f-11eb-9238-c30734917494.jpeg" width="25%"/>
<img src="https://user-images.githubusercontent.com/39134128/124235432-6b9ff600-db3f-11eb-9c67-be3ac562fe76.jpeg" width="25%"/>
<img src="https://user-images.githubusercontent.com/39134128/124235442-6e025000-db3f-11eb-841a-47fa1486fa4a.jpeg" width="25%"/>
</p>

</br>
</br>

<h3>Movie</h3>

<p float="left">
<img src="https://user-images.githubusercontent.com/39134128/124236060-38aa3200-db40-11eb-815f-106b2f98123f.jpeg" width="25%"/>
<img src="https://user-images.githubusercontent.com/39134128/124236017-2b8d4300-db40-11eb-87fb-b44541163932.jpeg" width="25%"/>
<img src="https://user-images.githubusercontent.com/39134128/124236047-3516ab00-db40-11eb-842b-1f3b0f83db16.jpeg" width="25%"/>
<img src="https://user-images.githubusercontent.com/39134128/124236074-3c3db900-db40-11eb-8ffb-90814a910ff6.jpeg" width="25%"/>
<img src="https://user-images.githubusercontent.com/39134128/124236002-27612580-db40-11eb-9c77-18e00b2170a4.jpeg" width="25%"/>
</p>

</br>
</br>

<h3>Popular People</h3>

<p float="left">
<img src="https://user-images.githubusercontent.com/39134128/124236030-2f20ca00-db40-11eb-8ed6-91a42ac4ebb5.jpeg" width="25%"/>
</p>

## **CREDIT**

**GraphQL Playground TMDB**
- [Drake Costa Saeris](https://github.com/Saeris/tmdb-api)

```fix
Happy Coding 💻  | 2021
```

