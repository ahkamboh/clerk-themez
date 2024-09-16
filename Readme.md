# Clerk-Themez

**Clerk-Themez** is a collection of custom themes designed specifically for Clerk authentication components. With these themes, you can style Clerk’s sign-in, sign-up, and user button management sections globally by importing the theme once in your root or layout file.

## Features

- 25 custom themes to choose from
- Global application of themes across all Clerk auth sections
- Works with Next.js and other frameworks

## Installation

To install the `clerk-themez` package, run:

```bash
npm install clerk-themez
```

## Usage

Once installed, you can easily apply a theme globally by importing it into your root or layout file.

### Step 1: Import the Theme Globally

In a **Next.js** project, import the theme in your `layout.tsx` file for it to apply across all Clerk components (such as `SignIn`, `SignUp`, and the `UserButton`).

**Example (Next.js):**

```tsx
// src/app/layout.tsx

import 'clerk-themez/themes/<themename>.css'; // Import the chosen theme

export default function RootLayout({ children }: { children: React.ReactNode }) {
  return (
    <html lang="en">
      <body>
        {children}
      </body>
    </html>
  );
}
```

Replace `<themename>` with the name of your preferred theme from the list below.

### Step 2: Apply to Clerk Components

By importing the theme in the root file (`layout.tsx` for Next.js), the styles will automatically apply to all Clerk authentication components across your app, including:

- Sign-in page
- Sign-up page
- User management sections (e.g., `UserButton`)

### Next.js Clerk Auth Example:

**Sign-in Page (`src/app/(auth)/sign-in/page.tsx`):**

```tsx
import { SignIn } from '@clerk/nextjs';
import React from 'react';

const SignInPage = () => {
  return (
    <main className="flex items-center justify-center min-h-screen relative sign-bg">
      <SignIn />
    </main>
  );
};

export default SignInPage;
```

**Sign-up Page (`src/app/(auth)/sign-up/page.tsx`):**

```tsx
import { SignUp } from "@clerk/nextjs";
import React from "react";

const SignUpPage = () => {
  return (
    <main className="flex items-center justify-center min-h-screen relative sign-bg">
      <SignUp />
    </main>
  );
};

export default SignUpPage;
```

This structure allows you to globally style all Clerk auth pages by simply importing your chosen theme in the layout file.

### Other Frameworks

In other frameworks (e.g., React, Vue, etc.), you can achieve the same effect by importing the theme in your root component or the entry point of your application.

For example, in a **React** project, import the theme in the `App.js` or `App.tsx` file:

```jsx
// App.js

import 'clerk-themez/themes/<themename>.css';

function App() {
  return (
    <div className="App">
      {/* Your components */}
    </div>
  );
}

export default App;
```

### Available Themes

Here is a list of available themes:

Here is the list with all the themes arranged in the same format:

---

- **cosmicflux**
![output-onlinegiftools](https://github.com/user-attachments/assets/d4cd0224-c758-4aaf-bcd3-f608d81d6074)

```js
   import 'clerk-themez/themes/cosmicflux.css';
```

---

- **blackbluish**
![image](https://github.com/user-attachments/assets/580ec24b-9a4a-46ac-8eea-18662de99cb9)

```js
   import 'clerk-themez/themes/blackbluish.css';
```

---

- **blueblush**
![image](https://github.com/user-attachments/assets/4c8646bb-7bf3-46ea-a6b1-4c83136b1374)

```js
   import 'clerk-themez/themes/blueblush.css';
```

---

- **bluresh**
![image](https://github.com/user-attachments/assets/66c1ff9f-8d84-4efc-8b3c-77fa42044319)

```js
   import 'clerk-themez/themes/bluresh.css';
```

---

- **darklitflux**
![output-onlinegiftools (1)](https://github.com/user-attachments/assets/469ef08d-5715-4d3a-bbb4-fb3ff8bf2836)

```js
   import 'clerk-themez/themes/darklitflux.css';
```

---

- **dreamscape**
![image](https://github.com/user-attachments/assets/f719cfcc-a53f-44c9-b6a7-fa5f2a5b6615)

```js
   import 'clerk-themez/themes/dreamscape.css';
```

---

- **ember**
![image](https://github.com/user-attachments/assets/09d44752-dafd-4eea-9186-fbff401f10ce)

```js
   import 'clerk-themez/themes/ember.css';
```

---

- **floatball**
![image](https://github.com/user-attachments/assets/7d5cdf3a-d194-4fc2-951a-eaead76d63b1)

```js
   import 'clerk-themez/themes/floatball.css';
```

---

- **glassyblack**
  ![image](https://github.com/user-attachments/assets/c74f8694-edf0-43e2-a778-2e176121927b)

```js
   import 'clerk-themez/themes/glassyblack.css';
```

---

- **glassybluesh**
  ![image](https://github.com/user-attachments/assets/44def755-63bf-45af-9a50-6916fdb55883)

```js
   import 'clerk-themez/themes/glassybluesh.css';
```

---

- **glassygreesh**
![image](https://github.com/user-attachments/assets/a890b3d5-3380-4e85-8dc9-f90d5a3f1d90)

```js
   import 'clerk-themez/themes/glassygreesh.css';
```

---

- **leafgreen**
![image](https://github.com/user-attachments/assets/a847db9c-5a6a-4082-adc2-66dd6f18a3d0)

```js
   import 'clerk-themez/themes/leafgreen.css';
```

---

- **moonlit**
![image](https://github.com/user-attachments/assets/e591c85d-8d62-4d8e-80ac-97efe3446ea4)

```js
   import 'clerk-themez/themes/moonlit.css';
```

---

- **moonlitflux**
![output-onlinegiftools (2)](https://github.com/user-attachments/assets/ed72f073-5037-4e64-a015-9ca6efcbde0c)

```js
   import 'clerk-themez/themes/moonlitflux.css';
```

---

- **neonwave**
![image](https://github.com/user-attachments/assets/17427c1f-20ea-4e5f-bf68-b52e207ddea4)

```js
   import 'clerk-themez/themes/neonwave.css';
```

---

- **nightdream**
![image](https://github.com/user-attachments/assets/1973a2b7-2984-4273-addb-336440480e3f)

```js
   import 'clerk-themez/themes/nightdream.css';
```

---

- **pinkbless**
 ![image](https://github.com/user-attachments/assets/9a6eb003-bc83-4f19-a3d9-8337e51f02fe)

```js
   import 'clerk-themez/themes/pinkbless.css';
```

---

- **pinkdrish**
![image](https://github.com/user-attachments/assets/22ffd54b-975c-4f2d-8ac5-6f9602919d0e)

```js
   import 'clerk-themez/themes/pinkdrish.css';
```

---

- **pinkesh**
![image](https://github.com/user-attachments/assets/556979d4-f2af-4c26-b16c-1e06d61f08fb)

```js
   import 'clerk-themez/themes/pinkesh.css';
```

---

- **prismatic**
![image](https://github.com/user-attachments/assets/b0621ba2-b857-4688-80d4-44d39d2a63b3)

```js
   import 'clerk-themez/themes/prismatic.css';
```

---

- **sunsetblaze**
![image](https://github.com/user-attachments/assets/6d96d530-695a-4926-b23e-b33352c58995)

```js
   import 'clerk-themez/themes/sunsetblaze.css';
```

---

- **waveflux**
![output-onlinegiftools (3)](https://github.com/user-attachments/assets/f122ff71-2776-4004-b6ce-ecf833bc819a)

```js
   import 'clerk-themez/themes/waveflux.css';
```

---

- **whisperflux**
![output-onlinegiftools (4)](https://github.com/user-attachments/assets/5108fc92-c1a3-4a8f-9933-a1757c0bf8cd)

```js
   import 'clerk-themez/themes/whisperflux.css';
```

---

- **whitegrain**
  ![image](https://github.com/user-attachments/assets/a48d4ae8-15b3-4a98-b31b-611997b3cafd)


```js
   import 'clerk-themez/themes/whitegrain.css';
```

---

- **zestful**
![image](https://github.com/user-attachments/assets/fdeada2a-8692-4686-b9c4-c2bec2d9664f)

```js
   import 'clerk-themez/themes/zestful.css';
```

#  Theme Customization

If you want to tweak the themes to match your app's branding, you can modify the CSS Class directly or use the provided styles as a base.

```css
.cl-backLink,.cl-button,.cl-button:focus,.cl-button:hover,.cl-dividerLine,.cl-dividerText,.cl-footer,.cl-footerActionText,.cl-formFieldInput,.cl-formFieldInputShowPasswordButton,.cl-formFieldInputShowPasswordButton:hover,.cl-formFieldLabel,.cl-formFieldRadioLabelTitle,.cl-formResendCodeLink,.cl-headerSubtitle,.cl-headerTitle,.cl-identityPreviewEditButton,.cl-identityPreviewText,.cl-internal-10vqj2v,.cl-internal-1338bh3,.cl-internal-13lvar6,.cl-internal-13u79ez,.cl-internal-162hn3d,.cl-internal-178xxbv,.cl-internal-17jfncx,.cl-internal-18msqv3,.cl-internal-1b2ebjn,.cl-internal-1dauvpw,.cl-internal-1e86so8,.cl-internal-1e86so8:focus,.cl-internal-1e86so8:hover,.cl-internal-1fsy72e,.cl-internal-1fy2g6e,.cl-internal-1fy2g6e:hover,.cl-internal-1hp5nqm,.cl-internal-1jcsuiw,.cl-internal-1jokxdd,.cl-internal-1k60c9o,.cl-internal-1mwxfst,.cl-internal-1y71s3o,.cl-internal-3f8jnx,.cl-internal-617r0v,.cl-internal-6ni1dv,.cl-internal-6ni1dv:hover,.cl-internal-bzdfjc,.cl-internal-csc3r5,.cl-internal-d2hd6e:hover,.cl-internal-d5dzke,.cl-internal-df7v37,.cl-internal-hy4pby,.cl-internal-k7p5wl,.cl-internal-mg5k16 .bg-white,.cl-internal-n0yayv,.cl-internal-s825v9 .cl-internal-1agciv4,.cl-internal-s825v9:hover,.cl-internal-xpydm8,.cl-internal-zqxz1f,.cl-menuItem:hover,.cl-navbarMobileMenuRow,.cl-otpCodeFieldInput,.cl-profileSectionTitleText,.cl-signIn-root,.cl-signIn-start,.cl-signUp-root,.cl-signUp-start,.cl-socialButtonsBlockButton,.cl-socialButtonsBlockButton:hover,.cl-socialButtonsBlockButtonText,.cl-userButtonPopoverActionButton,.cl-userButtonPopoverActionButton:hover,.cl-userButtonTrigger,.cl-userPreview,.cl-userPreviewSecondaryIdentifier
```

## Contributing 

If you'd like to contribute to this collection of themes, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.