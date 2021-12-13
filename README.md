# Walkthrough Flow in React Native
This is my first react js template I made learning react. It's a simple carousel design onboarding with three pages. 

## Get Started

```
const WalkthroughAppConfig = {
  onboardingConfig: {
    walkthroughScreens: [
      {
        icon: require("../assets/react-native.png"),
        title: "React Native Walkthrough",
        description: "Welcome your users with a beautiful app walkthrough.",
      },
      {
        icon: require("../assets/educate.png"),
        title: "Educate",
        description:
          "Showcase features to new users so that they get to love your app.",
      },
      {
        icon: require("../assets/bell.png"),
        title: "Get Notified",
        description: "Describe the value proposition of each core feature.",
      },
    ],
  },
};

const lightColorSet = {
  mainThemeBackgroundColor: "#ffffff",
  mainThemeForegroundColor: "#788eec",
};

const darkColorSet = {
  mainThemeBackgroundColor: "#121212",
  mainThemeForegroundColor: "#788eec",
};

const colorSet = {
  ...lightColorSet,
  light: lightColorSet,
  dark: darkColorSet,
  "no-preference": lightColorSet,
};

const DynamicAppStyles = {
  colorSet,
};

<WalkthroughScreen
  appConfig={WalkthroughAppConfig}
  appStyles={DynamicAppStyles}
/>

```

