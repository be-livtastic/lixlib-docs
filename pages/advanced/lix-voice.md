# Lix Voice 

**Lix Voice** is a powerful and versatile tool that brings voice-driven
interaction to your website. This plugin enables users to navigate, fill
forms, and search content using just their voice, making your site more
accessible and user-friendly. Lix Voice is part of the Lix Components
Library by Threed Software, designed to extend Wix\'s basic
functionality with advanced, interactive components.

------------------------------------------------------------------------

## Table of Contents

-   [Installation](#installation)
-   [Features](#features)
-   [Usage](#usage)
-   [Demo](#demo)
-   [Requirements](#requirements)
-   [Support](#support)
-   [License](#license)

------------------------------------------------------------------------

## Installation

To install **Lix Voice** on your website and start capturing voice
input:

1.  **Add to Site:**

    -   Open your website in the Wix Editor.
    -   Go to the **App Market**, search for \"Lix Voice,\" and click on
        \"Add to Site.\"
    -   Select the website you wish to enhance with voice commands if
        you manage multiple sites.

2.  **Place Lix Voice on Your Page:**

    -   Once installed, go to the **Elements** tab, locate Lix Voice,
        and add it to your homepage or any other page where you'd like
        users to access voice commands.
    -   Lix Voice will automatically adopt your site\'s theme, but you
        can also customize its appearance to align with your website\'s
        design.

3.  **Language and Speech Settings:**

    -   Set your initial language by selecting **English** or any other
        preferred language in the Lix Voice settings. You can modify
        this language setting at any time to accommodate multilingual
        support.

4.  **Testing Voice Recognition:**

    -   Publish your site to ensure the app is fully functional. Open
        the site in a new tab, and you should see the Lix Voice icon.
    -   Grant microphone access when prompted, and test by speaking
        commands or phrases. Confirm that the spoken text is accurately
        displayed on your site.

5.  **Utilize Captured Text with JavaScript:**

    -   Enable **Dev Mode** in the Wix Editor to access coding
        capabilities.
    -   Use JavaScript to interact with the captured voice text:
        -   Find the Lix Voice element's ID (e.g., `#voiceCore1`).
        -   Add the following code in Dev Mode:

**FOR EXAMPLE**

1.  **Listening to the event and logging the message**:

    `$w("#voiceCore1").onResponse((event) => {
        console.log(event.data.message); // Logs the message from voice input
        // Use event.data.message to handle specific commands or actions
    });`

2.  **Storing the message in a variable**:

    Alternatively, if you want to store the message in a variable for further processing, you can do:

    `$w("#voiceCore1").onResponse((event) => {
        const message = event.data.message; // Store the voice input message
        console.log(message); // Logs the message
        // Now you can use the 'message' variable to execute specific actions
    });`


-  This approach quickly ensures that you're capturing and logging the message. If there's an issue with how the voice data is being processed, this will help debug the problem.
 
*   Publish your changes and test by speaking into the Lix Voice tool. The spoken input should appear in the console log.


------------------------------------------------------------------------

## Usage

To enable voice recognition on your website:

1.  **Set Up Voice Recognition:**

    -   Add a text element to your page and take note of its ID.
    -   Use the Wix code panel to create a script that listens for voice
        input, populating the text element as users speak.

2.  **Build Voice-Powered Forms:**

    -   After testing, replace the text element with a Wix form
        containing input fields.
    -   Use an \"on click\" listener to determine which input field is
        active.
    -   Capture voice input and apply it directly to the active input
        field, streamlining user interaction.

3.  **Test and Publish:**

    -   Publish your site to a live environment.
    -   Verify that the voice-powered form works accurately and test for
        any updates in real-time voice input and field population.

------------------------------------------------------------------------

## Demo

Experience Lix Voice in action with our live demo. See how it enables hands-free navigation, voice-powered form filling, and seamless language switching.

[Live Demo](https://derrellchristopher.wixstudio.com/lixlibrary/components/lix-voice#:~:text=Install%20Now-,Live%20Demo)

------------------------------------------------------------------------

## Features

-   **Multilingual Support:** Lix Voice enables real-time voice
    interaction in multiple languages, making your website accessible to
    a global audience. Users can switch languages seamlessly, enhancing
    usability for diverse visitors.

-   **Seamless Integration:** Designed for easy implementation, Lix
    Voice integrates smoothly with your website and automatically
    matches your site's theme. It requires minimal setup and can be
    customized to suit your branding.

-   **Offline Functionality:** Lix Voice remains functional even
    offline. Preloaded language files allow users to continue
    interacting with your site through voice commands without needing an
    internet connection, making it reliable and accessible anywhere.

------------------------------------------------------------------------

## Requirements

-   **Browser Compatibility:**\
    Lix Voice is compatible with all major browsers that support the Web
    Speech API, including Chrome, Firefox, and Edge.

-   **Device Requirements:**\
    Ensure the device has a functional microphone for voice recognition.
    Sufficient storage is also required for offline language support.

------------------------------------------------------------------------

## Support

For general inquiries, technical support, or billing issues, please
reach out:

-   **Support Email:** <contact+lix@threedsoftware.com>
-   **Billing Email:** <contact@threedsoftware.com>

------------------------------------------------------------------------

## License

Lix Voice was developed using **Wix Blocks**, Wix's tool for creating
custom applications and components. For terms of use, please refer to
Wix's [Terms of Service](https://www.wix.com/about/terms-of-use) and the
[Wix Blocks
documentation](https://support.wix.com/en/article/wix-blocks-creating-custom-elements).

For specific licensing inquiries related to Lix Voice, please contact
our support team or visit [Lix Library](https://derrellchristopher.wixstudio.com/lixlibrary/components/lix-voice).

------------------------------------------------------------------------

This app is part of the **Lix Components Library** by Threed Software,
designed to empower websites with advanced interactive tools. Keep
exploring and building with **Lix Voice** to elevate your website's
functionality and user experience with cutting-edge, voice-driven
features.
