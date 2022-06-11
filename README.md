<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
-->

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
    <img src="Resources/icon.png" alt="Logo" width="80" height="80">

  <h3 align="center">Monekin - Official repository</h3>

  <p>
    Welcome to the official repository of the most complete purchase management application in the market. In this repository you can collaborate with the project by helping us to complete translations or new currencies. <br/> <br/>You can also ask questions, make suggestions, report errors... For all that, check the following <a href="https://github.com/enriqueloz88/Monekin/issues">link</a>. There you will see a list of suggestions for improvement, as well as known bugs. You can add new issues, as long as no other user has already posted the same issue.
  </p>
</p>

[<img src="https://play.google.com/intl/en_us/badges/images/generic/en-play-badge.png"
     alt="Get it on Google Play"
     height="80">](https://play.google.com/store/apps/details?id=com.monekin.app)
     
<!-- CONTRIBUTING -->

## Contributing 🙋🏻

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Translation

The translations are in a json format <a href="https://github.com/enriqueloz88/Monekin/tree/main/i18n">here</a>. To generate a new language you only have to create a new file _lang.json_ where you must replace "lang" by the code of the language in question. You can extract these codes from this <a href="https://www.loc.gov/standards/iso639-2/php/code_list.php">link</a> looking at the ISO 639-1 Code column.

It is important that all new json files generated have exactly the same keys as the files already exposed. It is recommended to look at the _en.json_ file for reference. You can also modify any existing translation file, if you consider that any translation can be improved.

### Default Categories

When adding a language you may also want to translate the home categories, the categories that the user will see as soon as they enter the app. To do this, go to this <a href="https://github.com/enriqueloz88/Monekin/tree/main/constants/default-categories.ts">file</a>, look at the "names" attributes of each of the categories, and add a new name. Remember that you have to add it in all possible categories and subcategories.

### Currencies

Another good way to help the project is by adding new currencies. Each currency must have a code (any code that is returned by the <a href="https://docs.cloud.coinbase.com/sign-in-with-coinbase/docs/api-exchange-rates">Coinbase API</a> is supported), and a names object, in the different languages of the application. Well, consult and add the currencies supported by our app <a href="https://github.com/enriqueloz88/Monekin/tree/main/constants/app-currencies.ts">here</a>

### Google Play presentation

This is one of the parts where we most appreciate your help. The presentation in the application stores is important to achieve a greater number of downloads. You can find everything related to this part in the "Resources" folder of this project.

Within "Resources", you will see a folder for each supported language in the google play tab. Inside each language folder we have a screenshots directory, where the screenshots used to create the presentation images are found, a powerpoint, with which these screenshots have been laid out, and finally, a "mockups" folder with the slides of this exported powerpoint png format.Mas detalladamente, la estructura es la siguiente

```
- lang1
    - powerpoint (used to create the png images)
    - mockups
         - final_image1.png
         - final_image2.png
    - screenshots
         - screenshot_to_insert_in_ppt1.png
         - screenshot_to_insert_in_ppt2.png
- lang2
    - powerpoint (used to create the png images)
    ......
    ......
````

If you are going to add or modify any files, please try to keep this pattern as much as possible (it does not matter how the images are named within the directories)

<!-- CONTACT -->

## Contact 📧

Enrique Lozano - kikelozano8@gmail.com

Project Link: [https://github.com/enriqueloz88/SnackScan](https://github.com/enriqueloz88/Monekin)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/enrique-lozano-cebriano/
